Mathematics is a language we invented to teach ourselves about the world. Euler's Identity seems to have what we need to begin our thought experiment.

###### Euler's Identity
```javascript
// Euler's Identity
[ e^(i*PI) ] + 1 = 0
```

###### Incompleteness Theorem Representation - in draft
```javascript
// Incompleteness Theorem Representation - in draft

function init(n = 0) {
  const map = new Map();
  if (isFinite(!isNaN(n))) {
    const chimes = Array.from({length: n}, (v, i) => i);
    chimes.forEach((chime, index) => map.set(() => n ? 1 : 0, index));
  };
  return map;
};

init(429178800);
// [Function] => 0, [Function] => 1, ..., [Function] => n
init(-1);
// Map {}
```
