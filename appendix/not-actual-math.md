# Not Actual Math

The one-legged seagull lives like this.

My scooter is a bird. I left him in Los Angeles because my car was full of everything except the stuff I kept it all in. Along the Bollona Creek Bike Path, bird and I landed on the shore of the Pacific Ocean after the warehouse we visited because of warmth of a particular parking lot near the end of the cul de sac on the west by Marina Del Rey.

// The Army Core of Engineers

...brb

He never told me his name, but he was in bad shape. This was the bird on the street that asked you for a dollar for fun and that is just what they did. If he caught you peaking with the corner of his eye, then you could be certain he was going to say hello to make sure you remembered him even if you felt a little tense in your shoulders the first time he began speaking to you. You would never understand it if he tried to explain why he has only one leg. He asked why I could not see both his legs even in the sunlight. The cool thing about the one-legged seagull is he makes effort. When


see you at the ocean, but also he will get a good look at you to see what else you need to learn. So, that is what he does. He asks you for a dollar once at 10am and once at 2pm for a few days. That gives him a feel on how you are getting along. If you are crabby, he understands. If you have the spare change, then by all means throw a dog a bone. If you do not have it at 2pm he just wants those two acknowledgements for traveling all that way to check on you: the up-nod at 10am and the down-nod at 2pm.

I cannot remember the second place we met, but we did. That time he did tell me something. He did not ask for a dollar that day because that was goodbye. He only needed one day to see how you would fair on your journey at sea this season because him and his friends saw it first. He did not see my down-nod as he flew away that afternoon, but he was still able to liftoff with as much force as two legs. The sun peaked through, what looked like holes in his wings, but the missing feathers have been scattered further than any seagull on earth. From that day forward I was convinced I would never meet a wiser individual. If you are reading this, then thanks for that glare because it was not as disapproving as I thought. Remembering what it looked like these days reveals that smile and the little tear under that left pupil. Sometimes at sea the wind makes just one of my eyes water like yours was or when cutting onions, so, no worries. When I get out of this mess, I will try to save a dollar for you.

If the only thing recalling a memory is the recollection of the moment, then what does that say about a story untold? One moment I lived like this.

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

...brb
