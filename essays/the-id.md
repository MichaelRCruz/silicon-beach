# id NOT DONE SO CHILL, please

Mathematics is a language we invented to teach ourselves about the world. Euler's Identity seems to have what we need to begin our thought experiment.

### Euler's Identity
```text
// Euler's Identity
[ e^(i*PI) ] + 1 = 0
```

### Incompleteness Theorem Representation - in draft
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

init(429178800); // [Function] => 0, [Function] => 1, ..., [Function] => n
init(-1); // Map {}
```

Above represents all possible ways, I can think of, to declare a function in JavaScript. This implementation has a system of well-defined rules and all functions, within this system, that can return `0` or `1`.

These are the only two possible return values from above function - `0` and `1`

If `init(n)` can only equal `0` or `1`, then this is what I see.

### axioms 🙄

* n is a Real number
* init(n) returns 0 or 1
* 1 - 0 = 1
* 1 - 1 = 0

0 should be equal to `(1 - init(1)) === 1) - 0 === 1)` <-- nuh, uh! call the cops!





###### React Identity - in draft
1. a presentational layer of identity
2. shapes found in architecture to guide understanding and utility of form

```javascript
// React Identity - in draft
// https://reactjs.org
const myFunc = ({pop, crackle, snap}) => ({pop, crackle, snap})(myFunc)(this.state);

. . .

const myState = this.state;
const myFunc = ({pop, crackle, snap}) => {
  return {pop, crackle, snap};
}
myFunc(myState);

. . .

const myState = this.state
const myFunc = props => {
  const { pop, crackle, snap } = props;
  return {pop, crackle, snap};
}
myFunc(myState);

. . .

this.state = {
  pop: 'sup, world',
  crackle: 'michaelcruz.io',
  snap: 'functional programming'
};
const myState = this.state;
const myFunc = props => {
  return props;
};
myFunc(myState);
```
