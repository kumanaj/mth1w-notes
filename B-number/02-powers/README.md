# Powers and Exponents

> 📘 **Curriculum:** B2.1 · 📖 **Textbook:** §3.2, pp. 110–118 · [⬅ Strand B: Number](../)

## Big idea
A **power** is shorthand for repeated multiplication. Exponents describe fast growth
(doubling) and fast decay (halving).

## Vocabulary
| Term | Meaning |
|------|---------|
| **power** | a product of identical factors, e.g. $2^4$ |
| **base** | the identical factor (in $2^4$, the base is 2) |
| **exponent** | how many factors there are (in $2^4$, the exponent is 4) |

$$\underbrace{2^4}_{\text{exponential form}} = \underbrace{2 \times 2 \times 2 \times 2}_{\text{expanded form}} = 16$$

## Key concepts
- **Negative bases:** an *even* number of negative factors gives a positive answer; an *odd* number gives a negative one.
- **Brackets matter!**
  - $(-3)^4 = (-3)(-3)(-3)(-3) = 81$, because the base is $-3$
  - $-3^4 = -(3 \times 3 \times 3 \times 3) = -81$, because the base is $3$ and the minus sign is applied after
- **Fraction bases:** apply the exponent to the numerator *and* the denominator. $\left(\frac{2}{3}\right)^3 = \frac{8}{27}$
- Powers appear in formulas: $A = s^2$, $V = s^3$, $A = \pi r^2$, $V = \pi r^2 h$. Follow BEDMAS: exponents come before multiplication.
- **Growth/decay models:** doubling $= \text{start} \times 2^n$; halving (half-life) $= \text{start} \times \left(\frac{1}{2}\right)^n$.
- **Scientific notation:** a number from 1 to 10 times a power of 10. $56\,000\,000\,000 = 5.6 \times 10^{10}$

## Worked examples

### Example 1: Evaluate powers
| Power | Expanded | Value |
|-------|----------|-------|
| $2^5$ | $2 \times 2 \times 2 \times 2 \times 2$ | $32$ |
| $(-3)^3$ | $(-3)(-3)(-3)$ | $-27$ (odd count → negative) |
| $(-3)^4$ | $(-3)(-3)(-3)(-3)$ | $81$ (even count → positive) |
| $-3^4$ | $-(3 \times 3 \times 3 \times 3)$ | $-81$ |
| $3.5^3$ | $3.5 \times 3.5 \times 3.5$ | $42.875$ |
| $\left(\frac{2}{3}\right)^3$ | $\frac{2}{3} \times \frac{2}{3} \times \frac{2}{3}$ | $\frac{8}{27}$ |

### Example 2: Which popcorn container holds more?
- **Mega-Box** (cube, side 9.2 cm): $V = s^3 = 9.2^3 = 778.688 \approx 779 \text{ cm}^3$
- **Jumbo Drum** (cylinder, diameter 10.4 cm, height 9.0 cm): $r = 5.2$,
  $V = \pi r^2 h = \pi (5.2)^2 (9.0) \approx 764.54 \approx 765 \text{ cm}^3$

The Mega-Box holds about $779 - 765 = 14 \text{ cm}^3$ more.

### Example 3: Doubling bacteria
Listeria doubles every hour, starting at 800. After $n$ hours: $P = 800 \times 2^n$.
After 4 h: $800 \times 2^4 = 800 \times 16 = 12\,800$.

## Curriculum add-on: zero and negative exponents (B2.1)
> The textbook only uses positive exponents, but MTH1W asks you to look at how the **sign and size**
> of the exponent change the value of a power.

Follow the pattern: each step down in the exponent **divides by the base**.

| Power | $2^3$ | $2^2$ | $2^1$ | $2^0$ | $2^{-1}$ | $2^{-2}$ | $2^{-3}$ |
|-------|---|---|---|---|---|---|---|
| Value | 8 | 4 | 2 | **1** | $\frac{1}{2}$ | $\frac{1}{4}$ | $\frac{1}{8}$ |

$$x^0 = 1 \;(x \ne 0) \qquad x^{-n} = \frac{1}{x^n}$$

- A **negative exponent does not make the answer negative**: $2^{-3} = \frac{1}{8}$, which is still positive.
- For a base greater than 1, a bigger exponent gives a bigger value. For a base between 0 and 1, it gives a smaller value: $0.5^2 = 0.25 < 0.5$.
- **Scientific notation for small numbers** uses negative exponents: $0.000\,342 = 3.42 \times 10^{-4}$.
  Large numbers use positive ones: $4\,500\,000\,000 = 4.5 \times 10^{9}$.

## Watch out
- ⚠️ $2^3 \ne 2 \times 3$. The exponent counts factors; it doesn't multiply the base.
- ⚠️ On a calculator, type `(-3)^4` with brackets, or you'll get $-81$.
- ⚠️ The radius is half the diameter. Don't square the diameter.

## Quick check
1. Evaluate $(-2)^5$.
2. Evaluate $\left(-\frac{3}{4}\right)^2$.
3. Evaluate $2^5 - 4^2$.
4. 100 mg of U-235 has a half-life of 23 min. How much is left after 92 min?
5. Evaluate $5^{-2}$ and $10^0$.
6. Write $0.000\,07$ in scientific notation.

<details><summary>Answers</summary>

1. $-32$
2. $\frac{9}{16}$
3. $32 - 16 = 16$
4. $92 \div 23 = 4$ half-lives, so $100 \times \left(\frac{1}{2}\right)^4 = 100 \times \frac{1}{16} = 6.25$ mg.
5. $\frac{1}{25}$ and $1$
6. $7 \times 10^{-5}$

</details>

---
[⬅ Number Sets](../01-number-sets/) · [Strand B](../) · [Next: Exponent Laws ➡](../03-exponent-laws/)
