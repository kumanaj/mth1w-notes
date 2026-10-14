# Reasoning and Proving

> 📘 **Curriculum:** A1 · 📖 **Textbook:** §1.6, pp. 29–33 · [⬅ Strand A: Mathematical Thinking and Making Connections](../)

## Big idea
Examples can *suggest* that something is true, but only a **proof** shows it is always true.
A single **counter-example** shows it is false.

## Vocabulary
| Term | Meaning |
|------|---------|
| **conjecture** | a general conclusion drawn from a number of individual facts; it may or may not be true |
| **counter-example** | an example that proves a conjecture is false |
| **mean** | the sum of the values in a data set divided by the number of values |

## Key concepts
- Use reasoning to choose the best process for a situation.
- **Systematic trial** (guess → check → improve) solves many problems before you learn algebra.
- To **prove** a conjecture, give a well-organized argument that works for *every* case.
  Using a variable such as $n$ is a good way to do this.
- To **disprove**, one counter-example is enough.

## Worked examples

### Example 1: Prove a conjecture
*Conjecture:* the sum of any two consecutive whole numbers is odd.

- Examples: $1 + 2 = 3$, $\;2 + 3 = 5$, $\;3 + 4 = 7$. These support it but don't prove it.
- Proof: let the numbers be $n$ and $n + 1$.
  $$n + (n + 1) = 2n + 1$$
  $2n$ is always even, and even $+ 1$ is always odd. ∎

### Example 2: Vending machine (reasoning)
90 coins in total. There are one third as many dimes as quarters and half as many dimes as nickels. How much money?

Let dimes $= d$. Then quarters $= 3d$ and nickels $= 2d$.
$d + 3d + 2d = 6d = 90$, so $d = 15$.
- 15 dimes = 150 ¢
- 45 quarters = 1125 ¢
- 30 nickels = 150 ¢

Total = 1425 ¢ = **14.25 dollars**.

### Example 3: Counter-examples
| Statement | Counter-example |
|-----------|-----------------|
| All prime numbers are odd. | 2 is prime and even |
| The sum of two integers is always negative. | $3 + 4 = 7$ |
| All fractions are less than 1. | $\frac{5}{3}$ |
| All quadrilaterals are rectangles. | a rhombus with no right angles |

## Watch out
- ⚠️ "It worked for 5 examples" is **not** a proof.
- ⚠️ Measuring a diagram is an estimate, not a proof.

## Quick check
1. Prove that the sum of three consecutive whole numbers is divisible by 3.
2. The mean of 30 temperatures is $-5^\circ\text{C}$. What must the 31st temperature be to make the mean of all 31 equal $-6^\circ\text{C}$?

<details><summary>Answers</summary>

1. $n + (n+1) + (n+2) = 3n + 3 = 3(n + 1)$, which is a multiple of 3. ∎
2. Sum of the 30 values $= 30 \times (-5) = -150$. Needed sum $= 31 \times (-6) = -186$. Day 31 $= -186 - (-150) = -36^\circ\text{C}$.

</details>

---
[⬅ Selecting Tools and Computational Strategies](../05-selecting-tools/) · [Strand A](../) · [Next: Reflecting ➡](../07-reflecting/)
