# 2.2 Sampling Principles

> 📖 Textbook pp. 48–55 · [⬅ Chapter 2](../)

## Big idea
You usually can't survey everyone, so you survey a **sample**. A **random** sample is the
best way to make it represent the whole population and avoid **bias**.

## Vocabulary
| Term | Meaning |
|------|---------|
| **population** | the whole group of people or items being studied |
| **sample** | any group of people or items selected from a population |
| **census** | a survey of *all* members of a population |
| **random sample** | a sample in which all members of the population have an equal chance of being chosen |
| **simple random sampling** | choosing a specific number of members randomly from the entire population |
| **systematic random sampling** | choosing members at fixed intervals, starting from a randomly selected member |
| **stratified random sampling** | dividing the population into distinct groups, then randomly choosing the same fraction from each group |
| **non-random sampling** | using a method that is not random to choose a sample |
| **bias** | error resulting from choosing a sample that does not represent the whole population |

## Key concepts
- **Census or sample?** Census if the population is small and easy to reach (your class).
  Sample if it's large, expensive or impossible to reach everyone (all Canadians).
- The four sampling methods:

| Method | How (school of 1600, sample of 200) |
|--------|--------------------------------------|
| Simple random | Number the students 1–1600 and use a random number generator to pick 200 |
| Systematic random | Pick a random start, then take every $1600 \div 200 = 8$th name |
| Stratified random | Take the same fraction $\frac{200}{1600} = \frac{1}{8}$ from **each grade**, e.g. $\frac{1}{8}\times 480 = 60$ grade 9s |
| Non-random | e.g. ask the first 200 students at the front door (convenient but likely biased) |

- Other sources of bias: **voluntary** samples (only people with strong opinions reply),
  **convenience** samples (mall shoppers), and missing groups (e.g. phone-book surveys miss people without listed phones).
- TI-83/84 random integers: `MATH → PRB → 5:randInt(low, high, count)`, e.g. `randInt(1,10,20)`.

## Worked examples

### Example 1: Identify the sampling technique
- 75 employees randomly chosen from a list of all employees → **simple random**
- Random name, then every 25th person before and after it → **systematic random**
- Restaurant president interviews staff at **one** branch → **non-random**, biased (one branch may not represent the chain)
- Random students from each class, in proportion to class size → **stratified random**

### Example 2: Stratified sample sizes
Enrolment: Gr 9 = 330, Gr 10 = 308, Gr 11 = 295, Gr 12 = 283 (total 1216). Sample 150 students.

$$\text{fraction} = \frac{150}{1216} \approx 0.1234$$

| Grade | Calculation | Sample |
|-------|-------------|--------|
| 9 | $330 \times 0.1234 \approx 40.7$ | 41 |
| 10 | $308 \times 0.1234 \approx 38.0$ | 38 |
| 11 | $295 \times 0.1234 \approx 36.4$ | 36 |
| 12 | $283 \times 0.1234 \approx 34.9$ | 35 |
| | **Total** | **150** ✓ |

## Watch out
- ⚠️ "Random" doesn't mean "whoever is handy". Every member needs an **equal chance**.
- ⚠️ Stratified ≠ "5 from each grade". Each group gets the **same fraction**, so bigger groups get more people.

## Quick check
1. Identify the population: "The mean mark on yesterday's test was 72%."
2. A company wants 50 of its 325 employees for a survey. Describe a systematic random sample.
3. What type of sample is "every fifth person entering the cafeteria"? Is it biased?

<details><summary>Answers</summary>

1. All the students who wrote yesterday's test.
2. $325 \div 50 = 6.5$, so use an interval of 6: pick a random start from 1 to 6 on the numbered employee list, then take every 6th name until you have 50 ($6 \times 50 = 300 \le 325$, so it fits).
3. Systematic sampling. It's only random if the starting person is chosen randomly. It's biased toward students who *use* the cafeteria, so it misses those who don't.

</details>

---
[⬅ 2.1 Hypotheses](../2.1-hypotheses-and-data-sources/) · [Chapter 2](../) · [Next: 2.3 Scatter Plots ➡](../2.3-scatter-plots/)
