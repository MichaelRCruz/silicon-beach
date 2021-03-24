# Not Actual Math

My mentor, a bright engineer, politely listened to my description of the concepts of functional programming the weeks I wrote that representation of all possible functions in JavaScript.

My friend rode his bike and I rode my electric scooter along the Los Angeles River until the location the river empties into the Pacific Ocean. We sat on top of the boulders on the coast of California near the marina. That day I met a bird. He never told me his name, but he was in bad shape. On one leg, the bird hopped just as fine as the other birds. I felt so bad for the bird that I had to mention it to my friend. I thought about the bird once or twice later that day, but I saw him again. If I cannot remember the second place we met, but we did. That time he never told me why. I guess what that little bird _did_ tell me something.

If the only thing recalling a memory is the recollection of the moment, then what does that say about a story untold? One moment I said this.

_Any_ software, simple or complex, designed to compute state requires a moment to run the process. Given any level of complexity, you will have an initial `input`, a resulting `state`, and the process it took to render should be described as a `lifecycle`. If integer 10 is computed with a result of integer `xyz`, then integer `10` represents the input and integer `xyz` represents the resulting state.

## Symbols of Logic

`a`, `x`, `z` all symbolize time in a linear fashion form `a` to `z` likewise for `x` and `o` but as intermediate states with x being within any incremental scope.

## Assumptions of Logic

A sequence of `n`, where `n =/= 0` || `n != 1`, lifecycle units represent faultless operation of the software. Whereby the **Factor of Five** is defined after if and only if the following is true.

`a _is_ state sub(0)`

`z _is_ state sub(n)`

`input _is_ n*(2FoF)`

`state  input + 0 + 1`

## Axioms of Logic

* a base unit, `10`, cannot be error by nature.
* `0` (null) cannot be `1` "error" by nature or hold any value.
* **contractions** can only exist through the factor of five thing.

## Theories

1. null will always be zero
2. "error" will always exponentially approach zero and therefore always exist

---

## Approach

###### Factor of Five, notation
>`a ~ input + 0 + 1 ~ z`

Imagine any base ten integer ,10, as a symbol representing the simplest data structure available in this environment. Consider the next graphic depicting the very first **lifecycle**.

```
a ~ (70+0+1) ~ z
```

##### Factor of Five, treatment

At this point, I want to depict the next concept by destructuring the states into smaller structures for further visualization and more explanation after.

```
a  ~ ( 20+30+20+0+1 ) ~~~~~~~~~~~~~~~ o     <-- destructure
o  ~ ( 10+10+10+10+10+10+10+0+1 ) ~~~ o     <-- further destructure
o  ~ ( 2+2+2+2+2+2+2+0+1/5 ) ~~~~~~~~ o     <-- first factor of 5 treatment
o  ~ ( (2/25)+ ... + 0 + 1/25 ) ~~~~~ o     <-- second factor of 5 treatment
. . .
o  ~ ( (2/n*5)+ ... + 0 + (1/n*5) ) ~ z     <-- nth factor of 5 treatment
```

Notice how the last lifecycle listed contains only symbols `2, 0, 1`. Each supposed data structure has been contracted down by a mathematical factor of five. Remember this is just an illustration. :) The anti-pattern here being a product of 5 distributed back through the lifecycle which serves no purpose other than to reinforce the symbolism and notation.

The last detail on the **contraction** is the `0` and `1`. These each will represent null state, respectively. The symbol, `1`, was chosen because it represents "half-baked" state or nearly no state at all, but ultimately has value of some kind. `0` was chosen because it represents null and any factor of five treatment will never make it not 0. It's unchanging.

### Example

Consider three side-by-side-by-side comparisons of a set of contracted lifecyles with a bit of null state and error state mixed in as a requirement.

```
a ~ (10+0+1) ~ z
a ~ (20+0+1) ~ z
a ~ (30+0+1) ~ z
```

Applying the factor of five rule reduces our state into the following notation.

```
a ~ (2+0+1/5) ~ o
o ~ (4+0+1/5) ~ o
o ~ (6+0+1/5) ~ z
```

After reduction we are left with an incremental notation that exercises two theories. Null is zero.

### Scope

Before any reduction (factor of five), you can scope your state by a factor of the base unit, but cannot scope the base unit itself.

```
a ~ (10+0+1) ~ o | a ~ (1+0+1/10) ~ x   <--- "error", you can't gauge the base unit, 10
o ~ (20+0+1) ~ o | x ~ (2+0+1/10) ~ x
o ~ (30+0+1) ~ o | x ~ (3+0+1/10) ~ x
o ~ (40+0+1) ~ z | x ~ (4+0+1/10) ~ z
```

### Limited reduction

Now what you see above is a pretty straightforward way to represent some sort of meta-like substate "gauging" up or "gauging" down the scope. Take a look at the first lifecycle. You cannot gauge base unit, 10. 10 is the _least_ complex state can be.