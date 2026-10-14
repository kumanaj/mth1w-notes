# Linear and Non-Linear Relations

> 📘 **Curriculum:** C3.1, C4.1 · 📖 **Textbook:** §2.5, pp. 77–87 · [⬅ Strand C: Algebra](../)

## Big idea
If the points form a roughly straight line, the relation is **linear** and you can model it with
a **line of best fit**. If they bend, use a **curve of best fit**.

## Vocabulary
| Term | Meaning |
|------|---------|
| **linear relation** | a relation between two variables that forms a straight line when graphed |
| **line of best fit** | a straight line that comes closest to the points on a scatter plot |
| **curve of best fit** | a curve that comes closest to the points on a scatter plot of a non-linear relation |

## Key concepts
**Drawing a line (or curve) of best fit:**
- It passes **through or close to as many points as possible**.
- Points not on it are **evenly distributed above and below** it.
- It does **not** have to pass through any data point, or through the origin.

**When is a line of best fit a *bad* model?**
1. Too few data points to tell.
2. The points follow a curve: the middle points are all on one side of the line and the end points on the other.
3. The points show no pattern at all.

**Test for linear without graphing (table of values):** if $x$ goes up by equal steps,
check the **differences** in $y$. Constant differences → linear.

| $t$ | −2 | −1 | 0 | 1 | 2 |
|---|---|---|---|---|---|
| $d$ | −9 | −4 | 1 | 6 | 11 |
| difference | | +5 | +5 | +5 | +5 → **linear** |

| $t$ | −3 | −2 | −1 | 0 | 1 | 2 |
|---|---|---|---|---|---|---|
| $h$ | 5 | 0 | −3 | −4 | −3 | 0 |
| difference | | −5 | −3 | −1 | +1 | +3 → **non-linear** |

## Worked examples

### Example 1: Lizard temperatures (line of best fit)
A lizard's body temperature was measured at different surrounding temperatures (24.8 °C to 30.3 °C).
- **Relationship:** as the surrounding temperature rises, so does the lizard's. The points lie close to a straight line, so the relation is **linear**.
- **Interpolate** at 26 °C: read up to the line, then across → about **28 °C**.
- **Extrapolate** at 35 °C: extend the line → about **33 °C**. This is reasonable *only if* the relation stays linear above the measured range.

### Example 2: Skydiver (why extrapolation can fail)
| Time (s) | 0 | 1 | 2 | 3 | 4 | … | 9 | 10 | 11 | 12 |
|---|---|---|---|---|---|---|---|---|---|---|
| Speed (m/s) | 0 | 6 | 12 | 18 | 23 | … | 42 | 43 | 43 | 43 |

The first 4 s look linear (≈6 m/s faster each second). Extrapolating that gives ≈72 m/s at 12 s,
but air resistance makes the speed level off at about 43 m/s (*terminal velocity*). The full relation is **non-linear**.

## Watch out
- ⚠️ Don't just connect the dots. A line of best fit is **one smooth line**.
- ⚠️ Don't force the line through the first and last points.

## Quick check
1. Is $(0,0), (1,1), (2,4), (3,9), (4,16)$ linear? Why?
2. Is $(-6,-4), (-5,-2), (-4,0), (-3,2), (-2,4)$ linear? Why?
3. Can a line of best fit miss every data point? Give a reason.

<details><summary>Answers</summary>

1. No. Differences are $1, 3, 5, 7$, which are not constant (these are $y = x^2$).
2. Yes. $y$ increases by 2 every time $x$ increases by 1.
3. Yes. It only needs to be as close as possible to the points overall, with points balanced above and below it.

</details>

---
[⬅ Coding](../07-coding/) · [Strand C](../) · [Next: Distance-Time Graphs ➡](../09-distance-time-graphs/)
