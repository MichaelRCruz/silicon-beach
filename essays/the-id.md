# The Incompleteness Theorem Representation

Mathematics is a language we invented to teach ourselves about the world. Euler's Identity seems to have what we need to begin our thought experiment.

```javascript
// https://dvt.name/2018/03/12/godels-first-incompleteness-theorem-programmers/
// Incompleteness Theorem Representation - in draft
function init(n = 0) {
  const map = new Map();
  if (isFinite(!isNaN(n))) {
    const chimes = Array.from({length: n}, (v, i) => i);
    chimes.forEach((chime, index) => map.set(() => n ? 1 : 0, index));
  };
  return map;
};

init(1);

// Above represents all possible ways, I can think of, to declare a function in JavaScript. This implementation has a system of well-defined rules and all functions, within this system, that can return `0` or `1`.

// These are the only two possible return values from above function - `0` and `1`

// If `init(n)` can only equal `0` or `1`, then this is what I see.

// ### axioms 🙄

// * n is a Real number
// * init(n) returns 0 or 1
// * 1 - 0 = 1
// * 1 - 1 = 0

// 0 should be equal to `(1 - init(1)) === 1) - 0 === 1)` <-- nuh, uh! call the cops!
```
