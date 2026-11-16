# Data in the Real World and One-Variable Data

> 📘 **Curriculum:** D1.1, D1.2 · 📖 **Textbook:** not covered (see note below) · [⬅ Strand D: Data](../)

> ⚠️ **This topic is not in the textbook.** *Principles of Mathematics 9* was written before the
> MTH1W curriculum, so it has no lessons on big data, quartiles or box plots. These notes cover what
> the curriculum asks for. Check your class notes for your teacher's quartile method.

## Big idea
**One-variable data** is a list of measurements of *one* thing (test marks, heights, minutes of screen
time). You summarize it with a **centre** (mean, median, mode) and a **spread** (range, IQR), and you
show it with a graph such as a **box plot** or **histogram**.

## Vocabulary
| Term | Meaning |
|------|---------|
| **data set** | a collection of values for one variable |
| **categorical data** | data that names a group (favourite sport, eye colour) |
| **numerical data** | data that is a number: **discrete** if counted (number of siblings), **continuous** if measured (height, time) |
| **mean** | the sum of the values divided by the number of values (the "average") |
| **median** | the middle value when the data are in order |
| **mode** | the value that occurs most often (there can be more than one, or none) |
| **range** | maximum − minimum |
| **quartiles** | the three values that split ordered data into four equal parts: $Q_1$, $Q_2$ (the median), $Q_3$ |
| **interquartile range (IQR)** | $Q_3 - Q_1$, the spread of the middle 50% of the data |
| **five-number summary** | minimum, $Q_1$, median, $Q_3$, maximum |
| **box plot** | a graph of the five-number summary (also called a box-and-whisker plot) |
| **outlier** | a value far away from the rest of the data |
| **big data** | data sets so large they are collected and analysed by computers (e.g. every tap in a fitness app) |

## Part 1: Data in the real world (D1.1)

Big data sets are everywhere. For any example, be ready to explain **how the data is collected,
stored, shown and used**, and the **good and bad consequences**.

| Context | What's collected | Benefits | Concerns |
|---------|------------------|----------|----------|
| Social media / streaming apps | likes, watch time, location | recommendations you enjoy | privacy, addictive design, data sold to advertisers |
| Fitness trackers & health records | heart rate, steps, sleep | spotting illness early, medical research | who can see your health data? hacking |
| Store loyalty cards | everything you buy | discounts, stores stock what people want | tracking habits, targeted pricing |
| Sports analytics | every shot, pass, speed | better coaching and strategy | player privacy, over-reliance on numbers |
| Census (Statistics Canada) | population, income, language | planning schools, hospitals, transit | must be kept confidential and secure |

**Questions to ask about any data set:**
1. **Collection:** Who collected it? Did people give permission (consent)? Is the sample biased? (see [Sampling](../05-sampling/))
2. **Storage:** Where is it kept? Is it secure? How long is it kept?
3. **Representation:** Is the graph honest? Watch for axes that don't start at 0, missing labels, or cherry-picked time periods.
4. **Use:** Who benefits? Could the decision be unfair to some groups?

```
 Misleading (axis starts at 90)        Honest (axis starts at 0)
 100 |        ███                      100 |  ███   ███
  95 |  ███   ███                       50 |  ███   ███
  90 |  ███   ███                        0 |  ███   ███
       A      B                                A     B
 "B looks twice as big!"               A = 95, B = 100: almost the same
```

## Part 2: Measures of centre and spread (D1.2)

| Measure | How to find it | Best when… |
|---------|---------------|-----------|
| **Mean** | add all values, divide by how many | data has no outliers |
| **Median** | put in order, take the middle (average the two middle values if $n$ is even) | data has outliers or is skewed (e.g. house prices, incomes) |
| **Mode** | most frequent value | categorical data ("most popular flavour") |
| **Range** | max − min | quick look at spread, but one outlier changes it a lot |
| **IQR** | $Q_3 - Q_1$ | spread that ignores outliers |

### Finding quartiles (the "split in half" method)
1. Put the data **in order**.
2. Find the **median** ($Q_2$).
3. $Q_1$ = median of the **lower half**; $Q_3$ = median of the **upper half**.
   If $n$ is odd, **leave the median out** of both halves.

> 💡 Calculators and spreadsheets sometimes use slightly different quartile rules, so their answers
> can differ a little from your hand calculation. That's fine. Just say which method you used.

### Outliers: the 1.5 × IQR rule
A value is an outlier if it is

$$\text{below } Q_1 - 1.5 \times IQR \qquad \text{or} \qquad \text{above } Q_3 + 1.5 \times IQR$$

## Worked examples

### Example 1: Odd number of values, with an outlier
Daily screen time (hours) for 11 students: 5, 3, 8, 2, 18, 4, 6, 3, 9, 5, 7

**Order:** 2, 3, 3, 4, 5, **5**, 6, 7, 8, 9, 18

| Statistic | Work | Answer |
|-----------|------|--------|
| Mean | $\frac{2+3+3+4+5+5+6+7+8+9+18}{11} = \frac{70}{11}$ | ≈ 6.4 h |
| Median | 6th value of 11 | 5 h |
| Mode | 3 and 5 both appear twice | 3 h and 5 h |
| Range | $18 - 2$ | 16 h |
| $Q_1$ | lower half 2, 3, **3**, 4, 5 | 3 h |
| $Q_3$ | upper half 6, 7, **8**, 9, 18 | 8 h |
| IQR | $8 - 3$ | 5 h |

**Outlier test:** upper fence $= 8 + 1.5(5) = 15.5$. Since $18 > 15.5$, **18 h is an outlier**.
(Lower fence $= 3 - 7.5 = -4.5$, so nothing is too low.)

**Which centre is better?** The outlier pulls the **mean** up to 6.4 h, higher than 8 of the 11
students. The **median** (5 h) better describes a typical student.

### Example 2: Even number of values
Minutes to get to school for 10 students: 12, 15, 17, 18, 20, 22, 23, 25, 28, 30

- **Median:** the two middle values are 20 and 22, so median $= \frac{20 + 22}{2} = 21$ min.
- Lower half: 12, 15, **17**, 18, 20 → $Q_1 = 17$. Upper half: 22, 23, **25**, 28, 30 → $Q_3 = 25$.
- $IQR = 25 - 17 = 8$ min. Fences: $17 - 12 = 5$ and $25 + 12 = 37$, so **no outliers**.

### Example 3: Draw a box plot
Five-number summary from Example 1: **min 2, $Q_1$ 3, median 5, $Q_3$ 8, max 18**.
Because 18 is an outlier, draw the whisker to the largest value that is *not* an outlier (9)
and mark 18 with a dot.

```
      Q1    Med    Q3
      ┌─────┬──────┐
    ├─│     │      │──┤                     •  ← outlier (18)
      └─────┴──────┘
  ──┼────┼────┼────┼────┼────┼────┼────┼────┼──
    2    4    6    8   10   12   14   16   18    Screen time (h)
```

**Reading a box plot:**
- The **box** holds the middle 50% of the data. Each whisker holds 25%.
- A **longer** box or whisker means the data is more **spread out** there, not that there is more data.
- If the median line is **not** in the middle of the box, the data is **skewed**.

### Example 4: Compare two classes
| | Min | $Q_1$ | Median | $Q_3$ | Max |
|---|---|---|---|---|---|
| Class A test marks | 52 | 64 | 71 | 78 | 90 |
| Class B test marks | 40 | 70 | 76 | 80 | 98 |

- **Centre:** Class B's median (76) is higher, so a typical B student did better.
- **Spread:** IQR of A $= 14$, IQR of B $= 10$. The middle half of Class B is **more consistent**.
- But B's **range** (58) is bigger than A's (38), because B has one very low and one very high mark.

### Choosing a display
| Display | Use it for |
|---------|-----------|
| **Bar graph** | categorical data (favourite sport) |
| **Histogram** | numerical data grouped into intervals (heights 150–159 cm, 160–169 cm, …) where the bars **touch** |
| **Box plot** | showing spread and outliers, and **comparing** groups |
| **Circle graph** | parts of a whole (percentages adding to 100%) |
| **Scatter plot** | *two*-variable data (see [Scatter Plots](../02-scatter-plots/)) |

## Technology
| Tool | How |
|------|-----|
| Desmos | type `L = [2,3,3,4,5,5,6,7,8,9,18]`, then `mean(L)`, `median(L)`, `quartile(L,1)`, `quartile(L,3)`; draw with `boxplot(L)` |
| Spreadsheet | `=AVERAGE(A1:A11)`, `=MEDIAN(...)`, `=MODE(...)`, `=QUARTILE(A1:A11,1)`; Insert → Chart → Box and whisker |
| TI-83/84 | enter data in L1, then `STAT → CALC → 1:1-Var Stats` (shows $\bar{x}$, Q1, Med, Q3); `2nd STATPLOT` → box plot icon |

## Watch out
- ⚠️ **Always put the data in order** before finding the median or quartiles.
- ⚠️ With an even number of values, the median is the **average of the two middle values**, and it may not be one of the data values.
- ⚠️ The **mean** is pulled toward outliers; the **median** is not.
- ⚠️ A long whisker doesn't mean "more data". Each section of a box plot holds about 25% of the values.

## Quick check
Data: number of books read last summer by 9 students: 4, 0, 2, 7, 3, 1, 3, 12, 5

1. Find the mean, median and mode.
2. Find $Q_1$, $Q_3$ and the IQR.
3. Is 12 an outlier? Show your test.
4. Which is a better "typical" value here, the mean or the median? Why?
5. Give one benefit and one concern about a school app that records every book students borrow.

<details><summary>Answers</summary>

Ordered: 0, 1, 2, 3, **3**, 4, 5, 7, 12

1. Mean $= \frac{37}{9} \approx 4.1$ books. Median $= 3$ (5th value). Mode $= 3$.
2. Lower half 0, 1, 2, 3 → $Q_1 = \frac{1+2}{2} = 1.5$. Upper half 4, 5, 7, 12 → $Q_3 = \frac{5+7}{2} = 6$. $IQR = 4.5$.
3. Upper fence $= 6 + 1.5(4.5) = 12.75$. Since $12 < 12.75$, **12 is not an outlier** (but it's close).
4. The median (3). The value 12 pulls the mean up to 4.1, which is more than 6 of the 9 students read.
5. Benefit: the library can buy books students actually want. Concern: privacy, since reading records could be seen by others or used without permission.

</details>

---
[Strand D](../) · [Next: Scatter Plots and Correlation ➡](../02-scatter-plots/)
