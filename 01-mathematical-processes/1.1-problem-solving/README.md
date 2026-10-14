# 1.1 Focus on Problem Solving

> 📖 Textbook pp. 6–9 · [⬅ Chapter 1](../)

## Big idea
Follow a process: **understand** the problem, **plan** a strategy, **carry it out**, then
**look back** at your answer. You often need more than one strategy.

## Vocabulary
| Term | Meaning |
|------|---------|
| **natural number** | a number in the sequence $1, 2, 3, 4, \ldots$ |
| **prime number** | a number with exactly two factors, itself and 1 (e.g. 2, 3, 5, 7, 11) |
| **perfect square** | a number that is the product of two identical factors (e.g. $36 = 6 \times 6$) |

## Key concepts
- **The four-step process**
  1. *Understand*: read it twice and restate it in your own words. What is given? What is asked?
  2. *Plan*: pick a strategy (see the [strategy toolbox](../README.md#problem-solving-strategy-toolbox)).
  3. *Carry out*: work neatly and show each step.
  4. *Look back*: does the answer make sense? Can you check it another way?
- An **organized list or table** keeps information tidy so you don't miss or repeat cases.
- **Looking for a pattern** works when a sequence of numbers or diagrams repeats or grows.
- **Logic and reasoning**: use clues to cross out impossible values (an elimination table).

## Worked examples

### Example 1: Triangle of pennies (pattern + table)
How many pennies make a triangle with 10 pennies in its base?

| Base (pennies) | 1 | 2 | 3 | 4 | 5 | … | 10 |
|---|---|---|---|---|---|---|---|
| Total pennies | 1 | 3 | 6 | 10 | 15 | … | ? |

**Pattern:** each new row adds the base number: $1 + 2 + 3 + \cdots + 10$.
Pair the numbers: $(1+10) + (2+9) + \cdots + (5+6) = 5 \times 11 = 55$.
**Answer: 55 pennies.**

### Example 2: Chess tournament (simpler problem → pattern)
Every player plays every other player once. How many matches for 10 players?

| Players | 2 | 3 | 4 | 5 |
|---|---|---|---|---|
| Matches | 1 | 3 | 6 | 10 |

Each player plays $n - 1$ others, but that counts every match twice, so
$\text{matches} = \dfrac{n(n-1)}{2} = \dfrac{10 \times 9}{2} = 45$.

### Example 3: Logic grid (elimination table)
Clues such as "A, C and G are prime" let you mark ✗ under 1, 4, 6, 8, 9 for those letters.
Keep crossing out with each clue, put ✓ when only one value is left, then **verify** in the
original grid.

## Watch out
- ⚠️ 1 is **not** prime because it has only one factor.
- ⚠️ Don't stop after finding *one* pattern. Check that it works for every term you were given.

## Quick check
1. Continue the pattern for three more terms and give the rule: $4, 17, 30, 43, \ldots$
2. Continue: $1, 1, 2, 3, 5, 8, \ldots$
3. You have two quarters, a dime and a nickel. How many different sums of money can you make (using at least one coin)?

<details><summary>Answers</summary>

1. $56, 69, 82$. Add 13 each time.
2. $13, 21, 34$. Each term is the sum of the two before it (Fibonacci).
3. List them: 5, 10, 15, 25, 30, 35, 40, 50, 55, 60, 65 ¢ → **11 sums**.

</details>

---
[Chapter 1](../) · [Next: 1.2 Communicating ➡](../1.2-communicating/)
