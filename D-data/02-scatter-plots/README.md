# Scatter Plots and Correlation

> 📘 **Curriculum:** D1.3 · 📖 **Textbook:** §2.3, pp. 56–67 · [⬅ Strand D: Data](../)

## Big idea
A **scatter plot** shows whether two variables are related. Put the **independent** variable
on the horizontal axis and the **dependent** variable on the vertical axis.

## Vocabulary
| Term | Meaning |
|------|---------|
| **independent variable** | a variable that affects the value of another variable (horizontal axis, $x$) |
| **dependent variable** | a variable that is affected by some other variable (vertical axis, $y$) |
| **outlier** | a measurement that differs significantly from the rest of the data |
| **inference** | a conclusion based on reasoning and data |

## Key concepts
- Ask: *which one depends on the other?* The thing you change or control is independent.
- Each data pair becomes an ordered pair $(x, y)$, plotted as one point.
- Always give the scatter plot a **title**, **axis labels** and **units**.
- **Outliers:** you may discard one *only* if you can show it is inaccurate or unrepresentative
  (e.g. a measurement error). Otherwise keep it.
- **Steps of an experiment:**
  1. **Objective**: the purpose
  2. **Hypothesis**: what you expect
  3. **Procedure**: how you will collect data
  4. **Observations**: the data, in tables and graphs
  5. **Conclusion**: the inference, and whether it supports the hypothesis
  6. **Evaluation**: did it meet the objective, and how could it be improved?

## Worked examples

### Example 1: Identify related variables
| Situation | Independent | Dependent |
|-----------|-------------|-----------|
| Outdoor temperature vs. fuel to heat a house | outdoor temperature | fuel needed |
| Age vs. height | age | height |
| Latitude vs. rainfall | latitude | amount of rain |

### Example 2: Skateboarder on a ramp
| Initial height (m) | 2.0 | 2.7 | 3.4 | 3.8 | 4.0 | 4.5 | 4.7 | 5.0 |
|---|---|---|---|---|---|---|---|---|
| Speed (m/s) | 4.4 | 5.2 | 5.8 | 6.1 | **4.5** | 6.5 | 6.6 | 6.9 |

- **Independent:** initial height (the speed *depends on* where he starts).
- **Relationship:** as height increases, speed increases. The points follow a gentle **curve**, not a straight line.
- **Outlier:** $(4.0, 4.5)$. The speed is much lower than the pattern predicts; he may have dragged a foot or started at an angle.

```
Speed (m/s)
 7 |                         •  •  •
 6 |                •  •
 5 |          •
 4 |    •                 o  ← outlier (4.0, 4.5)
   +----+-----+-----+-----+-----+---- Initial height (m)
       2.0   3.0   4.0   5.0
```

## Curriculum add-on: correlation and regression (D1.3)
> MTH1W also asks you to describe the **correlation** and to test regression models with technology.

| Pattern on the scatter plot | Correlation |
|-----------------------------|-------------|
| Points rise from left to right | **positive** (as $x$ increases, $y$ increases) |
| Points fall from left to right | **negative** (as $x$ increases, $y$ decreases) |
| No clear direction | **none** |
| Points packed tightly around a line | **strong** |
| Points loosely scattered around a line | **weak** |

- **Correlation is not causation.** Ice-cream sales and drownings both rise in summer, but one doesn't cause the other (heat causes both).
- **Testing regression models:** in Desmos, a spreadsheet, or a graphing calculator, try a linear model ($y = ax + b$) and a non-linear one (e.g. quadratic or exponential). The model whose curve passes closest to the points (the larger $r^2$ value, which runs from 0 to 1) fits better.
  - Desmos: put the data in a table, then type `y1 ~ m x1 + b` (linear) or `y1 ~ a x1^2 + b x1 + c` (quadratic).
- Only use a model to make **predictions** when it fits the data well and the prediction is close to the data range.

## Watch out
- ⚠️ Don't discard an outlier just because it "looks wrong". You need a reason.
- ⚠️ Treating one variable as independent doesn't prove it *causes* the change (latitude might not actually cause rain).

## Quick check
Identify the independent and dependent variables:
1. Blood pressure and physical fitness
2. Income and level of education
3. Load in an airplane and runway length needed for takeoff

<details><summary>Answers</summary>

1. Independent: physical fitness; dependent: blood pressure.
2. Independent: level of education; dependent: income.
3. Independent: load; dependent: runway length.

</details>

---
[⬅ Data in the Real World and One-Variable Data](../01-one-variable-data/) · [Strand D](../) · [Next: Trends, Interpolation, and Extrapolation ➡](../03-trends-interpolation-extrapolation/)
