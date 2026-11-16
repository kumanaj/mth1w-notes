# Practice Quiz: Data

> [⬅ Strand D: Data](README.md) · Covers textbook Ch. 2 (§2.1–2.5, Review pp. 95–97, Practice Test pp. 98–99), Ch. 5 equations of lines of best fit, and the non-textbook topics D1.1–D1.2

Try every question on paper **before** opening the solution. For graphing questions, sketch the scatter plot on grid paper or in Desmos.

## Part A: One-variable data ([topic 01](01-one-variable-data/))

**1.** Find the mean, median, mode and range: 14, 9, 11, 20, 9, 16, 13

<details><summary>Solution</summary>

Ordered: 9, 9, 11, **13**, 14, 16, 20
- Mean $= \frac{92}{7} \approx 13.1$
- Median $= 13$ (4th of 7 values)
- Mode $= 9$
- Range $= 20 - 9 = 11$

</details>

**2.** Find the five-number summary and the IQR: 3, 5, 6, 8, 9, 10, 12, 15

<details><summary>Solution</summary>

8 values, so the median is between the 4th and 5th: $\frac{8 + 9}{2} = 8.5$.
Lower half 3, 5, 6, 8 → $Q_1 = \frac{5 + 6}{2} = 5.5$. Upper half 9, 10, 12, 15 → $Q_3 = \frac{10 + 12}{2} = 11$.

**Min 3, $Q_1$ 5.5, median 8.5, $Q_3$ 11, max 15.** $IQR = 11 - 5.5 = 5.5$

</details>

**3.** Is 42 an outlier in this data set? 22, 25, 26, 28, 30, 31, 42

<details><summary>Solution</summary>

Median $= 28$. Lower half 22, 25, 26 → $Q_1 = 25$. Upper half 30, 31, 42 → $Q_3 = 31$. $IQR = 6$.
Upper fence $= 31 + 1.5(6) = 40$. Since $42 > 40$, **yes, 42 is an outlier**.

</details>

**4.** About what percent of the data in a box plot lies **inside the box**? About what percent lies to the left of the median?

<details><summary>Solution</summary>

**50%** inside the box (from $Q_1$ to $Q_3$). **50%** is to the left of the median.

</details>

**5.** A news site shows a bar graph of two candidates' support, 48% and 52%, with the vertical axis starting at 45%. Explain why the graph is misleading.

<details><summary>Solution</summary>

Because the axis starts at 45%, the bars look like 3 units and 7 units tall, so the second candidate seems to have **more than twice** the support. The real difference is only 4 percentage points. The axis should start at 0 (or the break should be clearly marked).

</details>

## Part B: Hypotheses and sources of data ([topic 04](04-hypotheses-and-data-sources/))

**6.** Write the opposite of each hypothesis.
a) Caffeine can affect your sleep.
b) At least half of the students in your school have a part-time job.

<details><summary>Solution</summary>

a) Caffeine **cannot** affect your sleep.
b) **Fewer than half** of the students in your school have a part-time job.

</details>

**7.** Which is a **primary** data source?
A. a list of the year's top-grossing films in the newspaper
B. having 20 of your friends ask their family members for their favourite colour
C. the lengths of the world's longest rivers from an atlas
D. the latest Paralympic results from the Internet

<details><summary>Solution</summary>

**B.** You are collecting the data yourself, for your own purpose. A, C and D were collected by someone else.

</details>

**8.** To decide how many of each size of school uniform to buy, a principal phones 200 students. Is this primary or secondary data? Is it a good choice?

<details><summary>Solution</summary>

**Primary** (the principal collects it). It's a good choice because no one else has this data. To be fair, the 200 students should be chosen randomly (e.g. stratified by grade), and students without a listed phone number could be missed.

</details>

## Part C: Sampling ([topic 05](05-sampling/))

**9.** Which is **not** random sampling?
A. using a random-number generator to pick 10% of players in each division of a soccer league
B. picking every 10th name on a list, starting from a random number between 1 and 10
C. standing on a street corner and asking every 10th person who walks by
D. drawing 10% of the names out of a well-shaken box

<details><summary>Solution</summary>

**C.** Only people who happen to walk past that corner can be chosen, so not every member of the population has an equal chance.
(A is stratified, B is systematic, D is simple random.)

</details>

**10.** A school board has 1200 elementary teachers and 800 secondary teachers. Describe a stratified random sample of 100 teachers.

<details><summary>Solution</summary>

Fraction $= \frac{100}{2000} = \frac{1}{20}$.
Elementary: $\frac{1}{20} \times 1200 = 60$. Secondary: $\frac{1}{20} \times 800 = 40$.
**Randomly choose 60 elementary and 40 secondary teachers** (e.g. random numbers from each list).

</details>

**11.** A gaming website posts a poll: "Do teens play too many video games?" Give two reasons the results will be biased.

<details><summary>Solution</summary>

1. **Voluntary response:** only people who choose to answer reply, usually those with strong opinions.
2. **Not representative:** visitors to a gaming site probably play more games than the average person, so they're likely to answer "no".

</details>

## Part D: Scatter plots and correlation ([topic 02](02-scatter-plots/))

**12.** Identify the independent and dependent variables: hours of basketball practice per week, and free throws made out of 20.

<details><summary>Solution</summary>

**Independent:** hours of practice. **Dependent:** free throws made (the number made *depends on* how much you practise).

</details>

**13.** Describe the relationship.

| Temperature (°C) | −10 | −5 | 0 | 5 | 10 | 15 |
|---|---|---|---|---|---|---|
| Hot chocolates sold | 85 | 72 | 60 | 41 | 30 | 18 |

<details><summary>Solution</summary>

As the temperature increases, the number of hot chocolates sold **decreases**. The points lie close to a straight line, so the relation is a **strong negative linear** correlation. (The sales drop by 11 to 19 each time the temperature goes up 5°, which is roughly steady.)

</details>

**14.** Ferry data (Chapter 2 Review Q7): ferries 100.0 m, 115.5 m and 167.2 m long carry 150, 205 and 600 cars. A 110.8 m ferry carries only 80 cars. Is it an outlier? What could cause it? Should you discard it?

<details><summary>Solution</summary>

**Yes.** Based on the 100 m and 115.5 m ferries, a 110.8 m ferry should carry about 190 cars, not 80. Possible causes: it is mainly a passenger ferry, it carries large trucks instead of cars, or it has more cabins and restaurants. **Don't discard it**: it is a real ferry, not a measurement error.

</details>

## Part E: Trends, interpolation and extrapolation ([topic 03](03-trends-interpolation-extrapolation/))

**15.** Estimating values **beyond** the known data for a relation is called
A. extrapolation  B. interpolation  C. a line of best fit  D. discarding outliers

<details><summary>Solution</summary>

**A. Extrapolation.**

</details>

**16.** A movie ticket cost 10.50 dollars in 2010 and 12.10 dollars in 2014. Estimate the 2012 price. Is this interpolation or extrapolation?

<details><summary>Solution</summary>

2012 is halfway, so use the mean: $\frac{10.50 + 12.10}{2} = 11.30$ dollars. **Interpolation** (2012 is between the data values).

</details>

**17.** On a scatter plot, a line of best fit has the middle points all **below** it and the points at both ends **above** it. Is it a good model? What should you use instead?

<details><summary>Solution</summary>

**No.** The points aren't balanced above and below the line; they follow a **curve** (the relation is non-linear). Use a **curve of best fit**.

</details>

**18.** Water temperature below a research ship (§2.5 Q10):

| Depth (m) | 100 | 200 | 300 | 400 | 500 | 800 | 1000 | 1200 |
|---|---|---|---|---|---|---|---|---|
| Temperature (°C) | 19.4 | 19.0 | 18.1 | 17.5 | 16.0 | 9.7 | 6.2 | 6.0 |

a) Describe the relationship. b) Estimate the temperature at 700 m and at 1600 m. c) Which estimate is more reliable?

<details><summary>Solution</summary>

a) As depth increases, temperature decreases. It is **non-linear**: it falls slowly to 500 m, then quickly to 1000 m, then **levels off** near 6 °C.
b) 700 m is between 500 m (16.0) and 800 m (9.7). The temperature drops about 2.1 °C per 100 m there, so about $16.0 - 2(2.1) \approx$ **12 °C**. At 1600 m the curve has levelled off, so about **6 °C** (or slightly less).
c) The **700 m** estimate is more reliable, because it's an **interpolation** inside the data. 1600 m is an extrapolation, so we have to *assume* the curve stays level.

</details>

## Part F: Mathematical modelling ([topic 06](06-mathematical-modelling/))

**19.** A line of best fit for canoe rental data passes through $(2, 15)$ and $(10, 55)$, where $h$ is hours and $C$ is the cost in dollars.
a) Find the equation of the line. b) Is it direct or partial variation? What do $m$ and $b$ mean? c) Predict the cost for 6 h.

<details><summary>Solution</summary>

a) $m = \frac{55 - 15}{10 - 2} = \frac{40}{8} = 5$. Substitute $(2, 15)$: $15 = 5(2) + b$, so $b = 5$. **$C = 5h + 5$**
b) **Partial variation** ($b \ne 0$). The rental costs **5 dollars per hour** ($m$) plus a **5 dollar starting fee** ($b$).
c) $C = 5(6) + 5 =$ **35 dollars**.

</details>

**20.** (Practice Test Q9) Outline an experiment to investigate how the distance a person stands from a ceiling light affects the length of their shadow. Include a hypothesis, a procedure, how you'll analyse the data, and how you'll tell whether the relation is linear.

<details><summary>Solution</summary>

**Hypothesis:** The farther a person stands from the point directly below the light, the longer their shadow.

**Procedure:**
1. Mark the floor point directly under the light. Turn off other lights.
2. The **same person** (controlled variable) stands at 0.5 m, 1.0 m, 1.5 m, … 4.0 m from the mark.
3. A partner measures the shadow length (cm) with a tape measure each time. Repeat each measurement twice and take the mean.

**Analysis:** record a table; make a scatter plot with **distance** (independent) on the $x$-axis and **shadow length** (dependent) on the $y$-axis; draw a line or curve of best fit; compare the result with the hypothesis.

**Linear?** The points lie close to a straight line, *or* the shadow length increases by about the same amount each time the distance goes up 0.5 m (constant **first differences**).

**Limitations to mention:** measurement error, the light isn't a perfect point, only one person was tested.

</details>

---
**Scoring yourself:** 18–20 means you're ready 🎉 · 14–17 means you should redo the topics where you missed questions · under 14 means you should go back through the [Strand D topics](README.md#topics) in order.

[⬅ The Mathematical Modelling Process](06-mathematical-modelling/) · [Strand D](README.md)
