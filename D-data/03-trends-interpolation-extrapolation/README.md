# Trends, Interpolation, and Extrapolation

> 📘 **Curriculum:** D1.3 · 📖 **Textbook:** §2.4, pp. 68–76 · [⬅ Strand D: Data](../)

## Big idea
A pattern in a graph shows a **trend**. Use the trend to estimate values **between** your data
(interpolate) or **beyond** your data (extrapolate).

## Vocabulary
| Term | Meaning |
|------|---------|
| **interpolate** | estimate a value *between* two measurements in a set of data |
| **extrapolate** | estimate a value *beyond* the range of a set of data |

## Key concepts
- Trends can be **upward** (increasing), **downward** (decreasing), or show no clear pattern.
- **Bar graphs** suit data for intervals or categories (e.g. fiscal years). **Scatter plots** suit two numeric variables.
- **Interpolation is usually more reliable than extrapolation**, because extrapolating assumes the trend keeps going, and real life can change (prices, populations, epidemics).
- When you extrapolate, **state your assumption** (e.g. "assuming rents keep rising at the same rate").

```
 y                              y
 |          •  •               |  •  •
 |     •  •                    |       •  •
 |  •  •                       |            •  •
 +----------------- x          +----------------- x
   upward trend                  downward trend
```

## Worked examples

### Example 1: Movie attendance (interpolate, then think about extrapolating)
Statistics Canada skipped the April 2001 – March 2002 period.
Attendance was 125.4 million in 2000–01 and 119.6 million in 2002–03.

**Interpolate** using the mean of the neighbours:
$$\frac{125.4 + 119.6}{2} = 122.5 \approx 122 \text{ million}$$

**Extrapolate:** attendance grew by almost half from 1994 to 2000, then levelled off, so a reasonable
prediction is about 120 million. Real events matter: the 2003 SARS outbreak kept people away
from crowds, so that year is an outlier for the long-term trend.

### Example 2: Rent in Guelph (extrapolate)
| Year | 1996 | 1997 | 1998 | 1999 | 2000 | 2001 | 2002 | 2003 |
|---|---|---|---|---|---|---|---|---|
| Rent (dollars) | 658 | 678 | 686 | 702 | 736 | 764 | 801 | 823 |

Average yearly increase: $(823 - 658) \div 7 \approx 23.6$ dollars/year.
Prediction for 2010: $823 + 7 \times 23.6 \approx 988$, so **about 990 dollars**, *assuming the trend continues at the same rate*.

## Watch out
- ⚠️ "If the trend continues, no children will be born in 2030" is a silly extrapolation, because trends level off. Always ask whether the answer is realistic.
- ⚠️ Interpolate only *within* the data range; extrapolate only a little way beyond it.

## Quick check
1. Milk (4 L) cost 3.56 dollars in 1995 and 3.82 dollars in 2000. Estimate the 1998 price.
2. Is that interpolation or extrapolation?
3. World population was 2520 million in 1950 and 6060 million in 2000. Why is it risky to extrapolate this to 2200?

<details><summary>Answers</summary>

1. Increase $= 0.26$ over 5 years $= 0.052$/year. $3.56 + 3(0.052) \approx 3.72$ dollars.
2. Interpolation (1998 is between 1995 and 2000).
3. The growth is not steady. It is speeding up, and population can't grow forever (the UN predicts it will level off near 10 billion), so the trend will change.

</details>

---
[⬅ Scatter Plots and Correlation](../02-scatter-plots/) · [Strand D](../) · [Next: Hypotheses and Sources of Data ➡](../04-hypotheses-and-data-sources/)
