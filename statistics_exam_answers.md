# APPLIED STATISTICS - MSc EXAMINATION
## ANSWER SCRIPT WITH COMPREHENSIVE EXPLANATIONS

---

## ANSWER TO QUESTION 1 (30 Marks)

### a) Definitions with Examples:

#### i. Population and Sample

**POPULATION:**
- **Definition:** A population is the complete set of all individuals, objects, or measurements that have a common characteristic and are of interest to the researcher.
- **Characteristics:**
  - Contains ALL elements being studied
  - Denoted by N (population size)
  - Population parameters are fixed but usually unknown
  
**Examples:**
1. All undergraduate students enrolled in a university (if studying student performance)
2. All mango trees in a specific orchard (if studying fruit yield)
3. All households in Sri Lanka (if conducting a national census)

**SAMPLE:**
- **Definition:** A sample is a subset of the population selected for study. It's a representative portion chosen to make inferences about the entire population.
- **Characteristics:**
  - Contains SOME elements from the population
  - Denoted by n (sample size)
  - Sample statistics vary from sample to sample
  - Should be representative of the population

**Examples:**
1. 500 randomly selected undergraduate students from the university
2. 50 mango trees selected using systematic sampling from the orchard
3. 10,000 households selected through stratified random sampling across Sri Lanka

**Relationship:** We study samples to make inferences about populations because studying entire populations is often impractical, expensive, or impossible.

---

#### ii. Parameter and Statistic

**PARAMETER:**
- **Definition:** A parameter is a numerical measure that describes a characteristic of a POPULATION.
- **Characteristics:**
  - Fixed but usually unknown value
  - Greek letters are typically used to denote parameters
  - Examples of parameters: μ (population mean), σ (population standard deviation), σ² (population variance), ρ (population correlation coefficient)

**Examples:**
1. μ = 72 kg (average weight of ALL adult males in a country)
2. σ = 8.5 cm (standard deviation of heights of ALL students in a university)
3. p = 0.65 (proportion of ALL voters who support a particular candidate)

**STATISTIC:**
- **Definition:** A statistic is a numerical measure that describes a characteristic of a SAMPLE.
- **Characteristics:**
  - Calculated from sample data
  - Varies from sample to sample (sampling variability)
  - Roman letters are typically used to denote statistics
  - Examples of statistics: x̄ (sample mean), s (sample standard deviation), s² (sample variance), r (sample correlation coefficient)

**Examples:**
1. x̄ = 70.5 kg (average weight of 100 sampled adult males)
2. s = 8.2 cm (standard deviation of heights in a sample of 200 students)
3. p̂ = 0.63 (proportion in a sample of 500 voters who support the candidate)

**Key Distinction:** 
- Parameters describe populations (unknown, fixed)
- Statistics describe samples (known, variable)
- We use statistics to ESTIMATE parameters

**Summary Table:**

| Measure | Population (Parameter) | Sample (Statistic) |
|---------|------------------------|-------------------|
| Mean | μ (mu) | x̄ (x-bar) |
| Standard Deviation | σ (sigma) | s |
| Variance | σ² | s² |
| Proportion | p | p̂ |
| Correlation | ρ (rho) | r |

---

#### iii. Continuous and Discrete Variables

**DISCRETE VARIABLES:**
- **Definition:** A discrete variable can only take specific, separate values, typically counting numbers. There are gaps between possible values.
- **Characteristics:**
  - Usually obtained by COUNTING
  - Can only take finite or countably infinite values
  - Cannot have fractional values between counts
  - Often (but not always) integers

**Examples:**
1. Number of students in a classroom: 25, 26, 27 (cannot be 25.5)
2. Number of cars in a parking lot: 0, 1, 2, 3, ...
3. Number of defective items in a batch: 0, 1, 2, 3, ...
4. Number of children in a family: 0, 1, 2, 3, ...
5. Number of goals scored in a football match: 0, 1, 2, 3, ...
6. Shoe size (discrete categories): 7, 7.5, 8, 8.5, 9...
7. Number of pods per mung bean plant: 10, 25, 28, 32, ...

**CONTINUOUS VARIABLES:**
- **Definition:** A continuous variable can take any value within a given range or interval. There are no gaps between possible values.
- **Characteristics:**
  - Usually obtained by MEASURING
  - Can take infinitely many values within an interval
  - Can have fractional or decimal values
  - Limited only by measurement precision

**Examples:**
1. Height of students: 165.3 cm, 170.85 cm, 168.234 cm, ...
2. Weight of laboratory rats: 248.3 g, 251.7 g, 259.45 g, ...
3. Temperature: 25.6°C, 27.35°C, 30.8°C, ...
4. Time taken to complete a task: 12.5 seconds, 15.73 seconds, ...
5. Shell length of tortoises: 9.2 cm, 12.85 cm, 15.345 cm, ...
6. Maize cob weight: 248.5 g, 253.7 g, 261.2 g, ...
7. Distance traveled: 45.3 km, 78.65 km, ...

**Key Distinctions:**

| Aspect | Discrete | Continuous |
|--------|----------|-----------|
| Nature | Counting | Measuring |
| Values | Separate, distinct | Any value in range |
| Between values | Gaps exist | No gaps |
| Representation | Bar charts, frequency tables | Histograms, density curves |
| Probability | P(X = x) makes sense | P(X = x) = 0 (use intervals) |

**Important Note:** The distinction sometimes depends on context and measurement precision. For example, age could be treated as discrete (in years: 20, 21, 22) or continuous (20.5 years, 21.37 years).

---

### b) Measurement Scales in Questionnaire

#### i. Scale of measurement for "Degree Programme"

**ANSWER: NOMINAL SCALE**

**Explanation:**
- The "Degree Programme" variable with options MM01, MM3, and SI represents a **NOMINAL scale of measurement**.
- **Definition of Nominal Scale:** The lowest level of measurement where data are categorized into mutually exclusive categories with no inherent order or ranking.

**Characteristics of Nominal Scale:**
1. **Classification only:** Categories are used for labeling or identifying
2. **No order:** Categories have no natural ordering or ranking
3. **No meaningful arithmetic:** Cannot perform mathematical operations
4. **Mode is the appropriate measure:** Only the mode can be used as a measure of central tendency
5. **Examples:** Gender (Male/Female), Blood type (A/B/AB/O), Nationality, Degree programme codes

**Why Degree Programme is Nominal:**
- MM01, MM3, and SI are simply codes/labels for different degree programmes
- One programme is not "greater than" or "less than" another
- The numbers in the codes don't imply any quantitative relationship
- We can only count frequencies (how many students in each programme)

**Permissible Operations:**
- Counting frequencies
- Finding mode (most common programme)
- Chi-square tests for independence
- Cannot calculate mean or standard deviation

---

#### ii. Type of data for "Skill and responsiveness of the Course Coordinator"

**ANSWER: ORDINAL DATA (likely on a Likert scale)**

**Explanation:**
- This type of question typically collects **ORDINAL data**, usually through a rating or Likert scale.
- **Definition of Ordinal Data:** Data that can be ordered or ranked, but the differences between ranks are not necessarily equal or meaningful.

**Typical Format for Such Questions:**
```
Rate the skill and responsiveness of the Course Coordinator:
○ Very Poor (1)
○ Poor (2)
○ Satisfactory (3)
○ Good (4)
○ Very Good (5)
○ Excellent (6)
```

**Characteristics of Ordinal Data:**
1. **Natural ordering exists:** Categories can be ranked from low to high
2. **Unequal intervals:** Difference between ranks may not be equal (difference between "Poor" and "Satisfactory" may not equal difference between "Good" and "Very Good")
3. **Relative comparisons:** Can say one is "better than" another
4. **Limited arithmetic:** Cannot perform all arithmetic operations meaningfully

**Why This is Ordinal:**
- Responses can be ranked (Excellent > Very Good > Good > Satisfactory > Poor > Very Poor)
- There's a clear hierarchy or order
- But we can't say the difference between "Good" and "Very Good" is exactly the same as between "Poor" and "Satisfactory"

**Appropriate Statistical Measures:**
- **Central Tendency:** Median, Mode (mean can be used cautiously with Likert scales)
- **Dispersion:** Range, Interquartile range, Percentiles
- **Tests:** Mann-Whitney U test, Kruskal-Wallis test, Spearman's rank correlation

**Contrast with Other Scales:**
- **Not Nominal:** Because there's an order (unlike programme codes)
- **Not Interval:** Because we can't assume equal intervals between categories
- **Not Ratio:** Because there's no true zero point

---

#### iii. Example of a variable at the RATIO scale

**ANSWER: "Number of hours you spend on the course"**

**Explanation:**
- The variable **"Number of hours you spend on the course"** represents a **RATIO scale of measurement**.
- **Definition of Ratio Scale:** The highest level of measurement with all properties of interval scale plus a true/absolute zero point.

**Characteristics of Ratio Scale:**
1. **Natural ordering:** Values can be ranked
2. **Equal intervals:** Differences between values are meaningful and consistent
3. **True zero point:** Zero means complete absence of the attribute
4. **Meaningful ratios:** Can make ratio comparisons (e.g., 10 hours is twice as much as 5 hours)
5. **All arithmetic operations:** Can add, subtract, multiply, divide meaningfully

**Why "Number of Hours" is Ratio:**
- **True zero exists:** 0 hours means no time spent (absolute zero)
- **Equal intervals:** The difference between 5 and 10 hours equals difference between 15 and 20 hours
- **Meaningful ratios:** 20 hours is exactly twice 10 hours; 30 hours is three times 10 hours
- **All math operations valid:** Can calculate mean, standard deviation, coefficient of variation

**Examples of Ratio Scale Variables:**
1. **Time:** Hours studied, reaction time, age in years
2. **Physical measurements:** Height, weight, length, distance
3. **Counts:** Number of students, number of attempts, frequency
4. **Financial:** Income, expenditure, price (in absolute terms)
5. **Scientific measurements:** Temperature in Kelvin, energy, mass

**Why Other Options Are NOT Ratio:**
- **Degree Programme (Nominal):** No order, no zero
- **Skill rating (Ordinal):** Order exists but no true zero or equal intervals
- **Temperature in Celsius/Fahrenheit (Interval, not Ratio):** Zero is arbitrary, not absolute absence

**Complete Hierarchy of Measurement Scales:**

```
RATIO (highest)
  ↑
  Has true zero, ratios meaningful
  ↑
INTERVAL
  ↑
  Equal intervals, no true zero
  ↑
ORDINAL
  ↑
  Can rank, unequal intervals
  ↑
NOMINAL (lowest)
  
  Categories only, no order
```

**Summary Table:**

| Scale | Order | Equal Intervals | True Zero | Examples |
|-------|-------|-----------------|-----------|----------|
| Nominal | ✗ | ✗ | ✗ | Degree programme, gender, blood type |
| Ordinal | ✓ | ✗ | ✗ | Satisfaction ratings, education level |
| Interval | ✓ | ✓ | ✗ | Temperature (°C/°F), calendar dates |
| Ratio | ✓ | ✓ | ✓ | Hours, weight, height, income |

---

## ANSWER TO QUESTION 2

### a) Short Answers (20 Marks)

#### i. Sample space for "exactly 2 heads" when tossing 3 unbiased coins

**ANSWER:**

**Complete Sample Space (all possible outcomes):**
When tossing 3 coins, each coin has 2 outcomes (H or T), so total outcomes = 2³ = 8

S = {HHH, HHT, HTH, HTT, THH, THT, TTH, TTT}

**Event A: "Exactly 2 heads"**
A = {HHT, HTH, THH}

**Explanation:**
- **Sample Space Definition:** The sample space is the set of all possible outcomes of an experiment.
- **Event Definition:** An event is a subset of the sample space.
- For "exactly 2 heads," we need outcomes with 2 H's and 1 T
- There are exactly **3 outcomes** that satisfy this condition

**Probability Calculation:**
P(exactly 2 heads) = n(A)/n(S) = 3/8 = 0.375

**Alternative Method Using Binomial:**
- n = 3 trials
- k = 2 successes (heads)
- p = 0.5 (probability of heads)

P(X = 2) = C(3,2) × (0.5)² × (0.5)¹ = 3 × 0.25 × 0.5 = 3/8

**Where C(3,2) = 3!/(2!×1!) = 3 combinations**

---

#### ii. Standard deviation of sampling distribution when sample size is 35

**ANSWER: σ/√35 or σ/√n where n=35**

**Detailed Explanation:**

**Given:**
- Population: X ~ N(μ, σ)
- Sample size: n = 35
- Need to find: Standard deviation of X̄ (sample mean)

**Key Concepts:**

1. **Central Limit Theorem (CLT):**
   - When sampling from any population with mean μ and standard deviation σ
   - The sampling distribution of X̄ approaches a normal distribution as n increases
   - Mean of sampling distribution: E(X̄) = μ
   - Standard deviation of sampling distribution: SD(X̄) = σ/√n

2. **Standard Error of the Mean (SEM):**
   - The standard deviation of the sampling distribution of the sample mean
   - Formula: **SEM = σ/√n**
   - Represents the variability of sample means around the population mean

**Solution:**
Standard deviation of X̄ = σ/√35 = σ/5.916

**Numerical Example:**
If σ = 10, then:
- SD(X̄) = 10/√35 = 10/5.916 = 1.690

**Interpretation:**
- As sample size increases, standard error decreases
- Larger samples give more precise estimates of μ
- The sampling distribution becomes more concentrated around μ

**Important Properties:**
1. SD(X̄) is always less than σ (population SD)
2. SD(X̄) decreases as √n (not linearly)
3. To halve the standard error, need to quadruple the sample size

**Comparison Table:**

| Sample Size (n) | Standard Error (σ/√n) | Relative Size |
|-----------------|----------------------|---------------|
| 1 | σ | 1.000σ |
| 4 | σ/2 | 0.500σ |
| 25 | σ/5 | 0.200σ |
| 35 | σ/√35 ≈ σ/5.916 | 0.169σ |
| 100 | σ/10 | 0.100σ |

---

#### iii. Mean and standard deviation of z-scores

**ANSWER: Mean = 0, Standard Deviation = 1**

**Detailed Explanation:**

**Given:**
- Original population: μ = 50, σ = 10
- All scores transformed to z-scores

**Z-Score Formula:**
z = (X - μ)/σ

**Key Concept - Standardization:**
- Z-score transformation is a **linear transformation** that standardizes any distribution
- Also called "standardization" or "normalization"
- Creates a standard normal distribution: Z ~ N(0, 1)

**Mathematical Proof:**

**For Mean of Z-scores:**
E(Z) = E[(X - μ)/σ]
     = [E(X) - μ]/σ
     = (μ - μ)/σ
     = 0/σ
     = **0**

**For Standard Deviation of Z-scores:**
SD(Z) = SD[(X - μ)/σ]
      = (1/σ) × SD(X - μ)
      = (1/σ) × SD(X)    [subtracting constant doesn't change SD]
      = (1/σ) × σ
      = **1**

**Properties of Z-Score Transformation:**
1. **Always results in:** Mean = 0, SD = 1
2. **Shape preserved:** Distribution shape remains the same
3. **Relative positions maintained:** Order and relative distances unchanged
4. **Dimensionless:** Z-scores have no units

**Example with Original Data:**

| Original Score (X) | Z-Score Calculation | Z-Score Value |
|-------------------|---------------------|---------------|
| 30 | (30-50)/10 | -2.0 |
| 40 | (40-50)/10 | -1.0 |
| 50 | (50-50)/10 | 0.0 |
| 60 | (60-50)/10 | +1.0 |
| 70 | (70-50)/10 | +2.0 |

**Interpretation of Z-Scores:**
- **Z = 0:** Score equals the mean
- **Z = +1:** Score is 1 standard deviation above mean
- **Z = -1:** Score is 1 standard deviation below mean
- **Z = +2:** Score is 2 standard deviations above mean

**Why This Is Useful:**
1. **Comparison across different scales:** Compare test scores measured in different units
2. **Outlier detection:** |Z| > 3 often indicates outliers
3. **Probability calculations:** Use standard normal table
4. **Relative standing:** Immediately see how far from average

**Universal Property:**
Regardless of original μ and σ values, z-scores ALWAYS have:
- **μz = 0**
- **σz = 1**

This is true whether original μ = 50 and σ = 10, or μ = 1000 and σ = 200, or any other values.

---

#### iv. Null hypothesis accepted at 5% but tested at 1%

**ANSWER: The null hypothesis will STILL BE ACCEPTED at 1% significance level**

**Detailed Explanation:**

**Given Information:**
- At α = 0.05 (5% significance level): H₀ was accepted (failed to reject)
- Question asks: What happens at α = 0.01 (1% significance level)?

**Key Concept - Significance Levels and Critical Regions:**

**Significance Level (α):**
- Probability of Type I error (rejecting true H₀)
- Defines the critical region for rejection

**Relationship Between Significance Levels:**
- 1% level is MORE STRINGENT than 5% level
- Requires STRONGER evidence to reject H₀
- Critical region is SMALLER at 1% than at 5%

**Logical Analysis:**

1. **At α = 0.05:**
   - H₀ was accepted
   - This means: test statistic did NOT fall in the rejection region
   - Equivalently: p-value > 0.05

2. **At α = 0.01:**
   - Rejection region is smaller (more conservative)
   - If test statistic wasn't in the larger rejection region (5%)
   - It certainly won't be in the smaller rejection region (1%)
   - Therefore: H₀ will STILL BE ACCEPTED

**Visual Representation:**

For a two-tailed test:
```
                    Critical Region       Critical Region
                    at α=0.01            at α=0.01
                    (0.5% each tail)     (0.5% each tail)
                         ↓                    ↓
    |---------|---------|---------|---------|---------|
   -3σ      -2.58σ   -1.96σ     0    +1.96σ   +2.58σ    +3σ
              ←-5%->             ←-5%->
           Critical Region      Critical Region
           at α=0.05           at α=0.05
           (2.5% each tail)    (2.5% each tail)
```

**Key Principle:**
- **α = 0.05:** Critical values = ±1.96 (for normal distribution)
- **α = 0.01:** Critical values = ±2.576 (for normal distribution)
- If |test statistic| < 1.96, then certainly |test statistic| < 2.576

**P-Value Interpretation:**
- If p-value > 0.05 (accept at 5%)
- Then p-value > 0.01 (will also accept at 1%)
- Because p-value is fixed for given data

**General Rule:**
```
If H₀ is accepted at significance level α₁,
and α₂ < α₁,
then H₀ will also be accepted at α₂
```

**Example with Numbers:**
Suppose p-value = 0.08
- At α = 0.05: p-value (0.08) > α (0.05) → Accept H₀
- At α = 0.01: p-value (0.08) > α (0.01) → Accept H₀

**Conclusion:**
Since we already accepted H₀ at the less stringent 5% level, we will definitely accept it at the more stringent 1% level. **The result remains: ACCEPT H₀** (or equivalently, FAIL TO REJECT H₀).

---

### c) Maize Cob Weight Problem (30 Marks)

**Given:**
- Maize cob weights: X ~ N(μ = 250g, σ = 40g)
- Acceptable marketable range: 230g to 270g
- Find: Percentage of cobs within this range

**Solution:**

**Step 1: Standardize the values (convert to z-scores)**

For X = 230g:
z₁ = (230 - 250)/40 = -20/40 = -0.5

For X = 270g:
z₂ = (270 - 250)/40 = 20/40 = 0.5

**Step 2: Find probabilities using standard normal table**

We need: P(230 < X < 270) = P(-0.5 < Z < 0.5)

Using standard normal distribution:
- P(Z < 0.5) = 0.6915
- P(Z < -0.5) = 0.3085

**Step 3: Calculate the required probability**

P(-0.5 < Z < 0.5) = P(Z < 0.5) - P(Z < -0.5)
                   = 0.6915 - 0.3085
                   = 0.3830

**Step 4: Convert to percentage**

Percentage = 0.3830 × 100 = **38.30%**

**ANSWER: Approximately 38.30% of harvested maize cobs would fall within the acceptable marketable range of 230g to 270g.**

**Alternative Calculation Using Symmetry:**

Since the normal distribution is symmetric:
- The range 230-270g is symmetric around the mean (250g)
- Each side is 20g from the mean (0.5 standard deviations)
- P(-0.5 < Z < 0.5) = 2 × P(0 < Z < 0.5)
- P(0 < Z < 0.5) = P(Z < 0.5) - 0.5 = 0.6915 - 0.5000 = 0.1915
- P(-0.5 < Z < 0.5) = 2 × 0.1915 = 0.3830 = 38.30%

**Interpretation:**

1. **Market Implications:**
   - Only about 38% of cobs meet marketable standards
   - About 62% fall outside the acceptable range
   - 30.85% are too light (< 230g)
   - 30.85% are too heavy (> 270g)

2. **Distribution Breakdown:**

| Weight Range | Z-Score Range | Percentage | Category |
|--------------|---------------|------------|----------|
| < 230g | Z < -0.5 | 30.85% | Below marketable |
| 230-270g | -0.5 < Z < 0.5 | 38.30% | **MARKETABLE** |
| > 270g | Z > 0.5 | 30.85% | Above marketable |

3. **Visual Representation:**
```
                 38.30% Marketable
              ←-------------------→
              230g              270g
        30.85% |                | 30.85%
    Below      |   ACCEPTABLE   |   Above
        ←------+-------+--------+------→
             -0.5σ    μ=250    +0.5σ
```

4. **Recommendations:**
   - Consider widening the acceptable range
   - Or work on reducing variability (σ) in production
   - Or adjust mean weight closer to desired range

**Statistical Notes:**
- The range ±0.5σ captures about 38.3% of data
- The range ±1σ captures about 68% of data
- The range ±2σ captures about 95% of data
- The range ±3σ captures about 99.7% of data (Empirical Rule)

---

### d) One-Sample t-Test for Laboratory Rats (Interpretation of R output needed)

**Given:**
- Known population mean: μ₀ = 250g
- Research question: Does new strain differ from known mean?
- Sample: n = 12 rats
- Data (grams): 248, 242, 245, 249, 260, 258, 243, 251, 252, 259, 254, 256

**Step 1: State the Hypotheses**

- **H₀:** μ = 250g (new strain has same average weight as known population)
- **H₁:** μ ≠ 250g (new strain has different average weight) [Two-tailed test]

**Step 2: Calculate Descriptive Statistics**

Sample mean (x̄):
x̄ = (248 + 242 + 245 + 249 + 260 + 258 + 243 + 251 + 252 + 259 + 254 + 256) / 12
x̄ = 3017 / 12 = **251.417g**

Sample standard deviation (s):
First, calculate deviations and squared deviations:
- (248-251.417)² = 11.673
- (242-251.417)² = 88.673
- (245-251.417)² = 41.173
- (249-251.417)² = 5.840
- (260-251.417)² = 73.673
- (258-251.417)² = 43.340
- (243-251.417)² = 70.840
- (251-251.417)² = 0.174
- (252-251.417)² = 0.340
- (259-251.417)² = 57.506
- (254-251.417)² = 6.673
- (256-251.417)² = 21.006

Σ(Xi - x̄)² = 420.917
s² = 420.917 / (12-1) = 420.917 / 11 = 38.265
s = √38.265 = **6.186g**

**Step 3: Calculate Test Statistic**

t = (x̄ - μ₀) / (s/√n)
t = (251.417 - 250) / (6.186/√12)
t = 1.417 / (6.186/3.464)
t = 1.417 / 1.786
t = **0.793**

**Step 4: Determine Critical Value and P-value**

- Degrees of freedom: df = n - 1 = 12 - 1 = 11
- Significance level: α = 0.05 (typically)
- Two-tailed test: α/2 = 0.025 in each tail

Critical t-value (11 df, α = 0.05, two-tailed): t_critical = ±2.201

**Decision Rule:**
- Reject H₀ if |t_calculated| > t_critical
- Reject H₀ if |0.793| > 2.201
- Since 0.793 < 2.201, we **FAIL TO REJECT H₀**

**P-value Calculation:**
For t = 0.793 with df = 11 (two-tailed):
p-value ≈ 0.444 (this would be shown in R output)

Since p-value (0.444) > α (0.05), we **FAIL TO REJECT H₀**

**Step 5: Interpretation of R Output (Expected)**

```R
One Sample t-test

data:  rat_weights
t = 0.793, df = 11, p-value = 0.444
alternative hypothesis: true mean is not equal to 250
95 percent confidence interval:
 247.259  255.575
sample estimates:
mean of x 
  251.417
```

**Step 6: Conclusion and Interpretation**

**Statistical Conclusion:**
There is insufficient evidence at the 5% significance level to conclude that the average body weight of the new strain of laboratory rats differs from the known population mean of 250g (t = 0.793, df = 11, p = 0.444).

**Detailed Interpretation:**

1. **Test Statistic:** t = 0.793
   - This is the standardized difference between sample mean and hypothesized population mean
   - Small value indicates sample mean is close to hypothesized mean

2. **P-value:** p = 0.444
   - Probability of obtaining results at least as extreme as observed, assuming H₀ is true
   - Large p-value (>0.05) suggests data is consistent with H₀
   - We would observe such a difference about 44.4% of the time by chance alone

3. **Confidence Interval:** (247.259, 255.575)
   - We are 95% confident that true mean weight of new strain lies between 247.26g and 255.58g
   - Notice that 250g (hypothesized value) falls within this interval
   - This confirms our decision to not reject H₀

4. **Sample Mean:** x̄ = 251.417g
   - Sample mean is 1.417g higher than hypothesized mean
   - But this difference is not statistically significant
   - Could be due to random sampling variation

**Practical Interpretation:**
The new strain of laboratory rats appears to have similar weight to the known population mean. The observed difference of 1.417g is not large enough to be considered statistically significant and could easily be due to random chance. The researcher should conclude that there's no evidence the new strain differs in weight from the standard strain.

**Assumptions of the t-test:**
1. **Random sampling:** Sample randomly selected
2. **Independence:** Observations are independent
3. **Normality:** Data approximately normally distributed (or n large enough)
4. With n=12, normality assumption should be checked

**Why use t-test instead of z-test?**
- Population standard deviation (σ) is unknown
- Using sample standard deviation (s) introduces additional uncertainty
- t-distribution accounts for this extra uncertainty
- With small sample (n=12), t-distribution is more appropriate

---

## ANSWER TO QUESTION 3 (40 Marks)

### Mung Bean Yield Analysis

**Data:** Pod yield per plant (40 plants)
10, 12, 25, 25, 25, 25, 27, 28, 28, 28, 28, 30, 31, 31, 31, 32, 32, 32, 32, 33, 33, 34, 35, 35, 36, 37, 37, 38, 38, 38, 40, 42, 43, 44, 47, 48, 48, 51, 55, 72

**Given Information:**
- Q1 = 28
- Q3 = 38.5
- IQR = 10.5

---

#### i. Comment on the use of mode as a central tendency measure

**ANSWER:**

**Mode Identification:**
Looking at the frequency distribution:
- 25 appears 4 times
- 28 appears 4 times
- 32 appears 4 times
- 38 appears 3 times
- 31 appears 3 times

The dataset is **multimodal** with THREE modes: 25, 28, and 32 (each appearing 4 times).

**Comments on Using Mode:**

**ADVANTAGES:**
1. **Easy to identify:** Simply find the most frequently occurring value
2. **Not affected by extreme values:** The outlier (72) doesn't influence the mode
3. **Applicable to all data types:** Can be used for categorical, ordinal, interval, or ratio data
4. **Represents most common outcome:** Shows the typical yield value that occurs most often

**DISADVANTAGES FOR THIS DATASET:**

1. **Multiple modes create ambiguity:**
   - Having three modes (25, 28, 32) makes interpretation unclear
   - Which mode should represent the "typical" yield?
   - This multimodal nature suggests multiple sub-populations or varying growing conditions

2. **Doesn't use all data:**
   - Only considers frequency, ignoring actual values
   - Doesn't account for 29 other data points
   - Misses information about the distribution's spread

3. **Not suitable for continuous-like discrete data:**
   - With 27 distinct values out of 40 observations
   - Many values appear only once or twice
   - Mode may not be representative of the central tendency

4. **Misleading in this context:**
   - Modes (25, 28, 32) are all below the median
   - Doesn't reflect the right-skewed nature of the distribution
   - Ignores the presence of higher yields (40-72 range)

**RECOMMENDATION:**

For this dataset, **mode is NOT the most appropriate measure** of central tendency. Better alternatives would be:

1. **Median (preferred):**
   - More robust to the outlier (72)
   - Better represents the center of skewed distribution
   - Median ≈ 32.5 (between Q1=28 and Q3=38.5)

2. **Mean:**
   - Uses all data points
   - Useful for calculating total yield
   - But influenced by the outlier (72)

**Conclusion:**
While mode can identify the most common yield values (25, 28, 32 pods per plant), it's not the best measure for this dataset due to multimodality and the need to consider the overall distribution shape. The median would provide a better representation of central tendency for this right-skewed, multimodal distribution.

---

#### ii. Calculate mean and standard deviation and interpret results

**CALCULATION:**

**Sample Mean (x̄):**

Sum of all values:
10 + 12 + 25(×4) + 27 + 28(×4) + 30 + 31(×3) + 32(×4) + 33(×2) + 34 + 35(×2) + 36 + 37(×2) + 38(×3) + 40 + 42 + 43 + 44 + 47 + 48(×2) + 51 + 55 + 72

= 10 + 12 + 100 + 27 + 112 + 30 + 93 + 128 + 66 + 34 + 70 + 36 + 74 + 114 + 40 + 42 + 43 + 44 + 47 + 96 + 51 + 55 + 72

Σxi = **1,356**

Mean: x̄ = 1356/40 = **33.9 pods per plant**

**Sample Standard Deviation (s):**

For each value, calculate (xi - x̄)²:

| Value (xi) | Frequency | xi - x̄ | (xi - x̄)² | f×(xi - x̄)² |
|------------|-----------|--------|-----------|-------------|
| 10 | 1 | -23.9 | 571.21 | 571.21 |
| 12 | 1 | -21.9 | 479.61 | 479.61 |
| 25 | 4 | -8.9 | 79.21 | 316.84 |
| 27 | 1 | -6.9 | 47.61 | 47.61 |
| 28 | 4 | -5.9 | 34.81 | 139.24 |
| 30 | 1 | -3.9 | 15.21 | 15.21 |
| 31 | 3 | -2.9 | 8.41 | 25.23 |
| 32 | 4 | -1.9 | 3.61 | 14.44 |
| 33 | 2 | -0.9 | 0.81 | 1.62 |
| 34 | 1 | 0.1 | 0.01 | 0.01 |
| 35 | 2 | 1.1 | 1.21 | 2.42 |
| 36 | 1 | 2.1 | 4.41 | 4.41 |
| 37 | 2 | 3.1 | 9.61 | 19.22 |
| 38 | 3 | 4.1 | 16.81 | 50.43 |
| 40 | 1 | 6.1 | 37.21 | 37.21 |
| 42 | 1 | 8.1 | 65.61 | 65.61 |
| 43 | 1 | 9.1 | 82.81 | 82.81 |
| 44 | 1 | 10.1 | 102.01 | 102.01 |
| 47 | 1 | 13.1 | 171.61 | 171.61 |
| 48 | 2 | 14.1 | 198.81 | 397.62 |
| 51 | 1 | 17.1 | 292.41 | 292.41 |
| 55 | 1 | 21.1 | 445.21 | 445.21 |
| 72 | 1 | 38.1 | 1451.61 | 1451.61 |

Σf(xi - x̄)² = **4,733.6**

Variance: s² = 4733.6 / (40-1) = 4733.6 / 39 = **121.37**

Standard Deviation: s = √121.37 = **11.02 pods per plant**

**ANSWER:**
- **Mean (x̄) = 33.9 pods per plant**
- **Standard Deviation (s) = 11.02 pods per plant**

---

**INTERPRETATION:**

**1. Mean Interpretation (x̄ = 33.9):**

- **Central value:** The average pod yield per plant is approximately 34 pods
- **Expected yield:** If conditions remain similar, we'd expect about 34 pods per plant on average
- **Comparison with modes:** Mean (33.9) is higher than all three modes (25, 28, 32), suggesting influence of higher values
- **Comparison with median:** Mean (33.9) is slightly above the median region (around 32-33), indicating right-skewed distribution
- **Total yield estimation:** For 1000 plants, expected total yield ≈ 33,900 pods

**2. Standard Deviation Interpretation (s = 11.02):**

- **Variability measure:** On average, individual plant yields deviate from the mean by about 11 pods
- **High variability:** Standard deviation of 11 relative to mean of 34 shows substantial variation
  - Coefficient of Variation (CV) = (s/x̄) × 100% = (11.02/33.9) × 100% = **32.5%**
  - CV > 30% indicates high relative variability

- **Range of typical values:**
  - Using the empirical rule (if approximately normal):
  - About 68% of plants yield between: x̄ ± s = 33.9 ± 11.02 = **22.88 to 44.92 pods**
  - About 95% of plants yield between: x̄ ± 2s = 33.9 ± 22.04 = **11.86 to 55.94 pods**

- **Practical implications:**
  - High variability suggests inconsistent growing conditions
  - Some plants produce very few pods (10-12), others many (47-72)
  - May indicate need for:
    * More uniform watering
    * Standardized plant spacing
    * Consistent soil conditions
    * Better pest/disease management

**3. Relationship Between Measures:**

| Statistic | Value | Interpretation |
|-----------|-------|----------------|
| Minimum | 10 | Lowest yield |
| Q1 | 28 | 25% of plants yield ≤ 28 pods |
| Median | ~32.5 | Half of plants yield ≤ 32.5 pods |
| Mean | 33.9 | Average yield |
| Q3 | 38.5 | 75% of plants yield ≤ 38.5 pods |
| Maximum | 72 | Highest yield (potential outlier) |
| IQR | 10.5 | Middle 50% spans 10.5 pods |
| SD | 11.02 | Average deviation from mean |
| Range | 62 | Total spread (10 to 72) |

**4. Distribution Characteristics:**

- **Right-skewed:** Mean (33.9) > Median (~32.5), indicating positive skew
- **Outlier effect:** The value 72 pulls the mean upward
- **Variability sources:**
  - Genetic variation within variety
  - Microclimate differences
  - Soil heterogeneity
  - Water availability differences
  - Random biological variation

**5. Agricultural Implications:**

- **Yield prediction:** Farmers can expect 34 ± 11 pods per plant (wide range)
- **Quality control needed:** High CV (32.5%) suggests need for improved consistency
- **Economic planning:** High variability affects harvest planning and labor requirements
- **Breeding opportunity:** High variability might allow selection of high-yielding plants (>45 pods)

**Conclusion:**
The mean of 33.9 pods per plant represents the average yield, but the relatively large standard deviation of 11.02 pods (32.5% CV) indicates substantial variability in yield across plants. This high variability suggests that growing conditions may not be uniform, and there's significant opportunity for improving yield consistency through better agricultural practices. The presence of outliers (especially 72) inflates both the mean and standard deviation, suggesting that while most plants yield 25-40 pods, some exceptional plants achieve much higher yields.

---

#### iii. Interpret the box plot and describe key features

**BOX PLOT ANALYSIS:**

Given information:
- Q1 = 28
- Median ≈ 32.5 (estimated from position between Q1 and Q3)
- Q3 = 38.5
- IQR = 10.5
- Minimum = 10 (likely whisker extends to this)
- Maximum = 72 (appears as outlier)

**KEY FEATURES AND INTERPRETATION:**

**1. CENTRAL TENDENCY:**

- **Median position:** The median (approximately 32.5) is slightly below the center of the box
- **Interpretation:** This suggests slight right skewness even within the middle 50% of data

**2. SPREAD AND VARIABILITY:**

- **Interquartile Range (IQR) = 10.5 pods:**
  - This is the range containing the middle 50% of the data
  - From Q1=28 to Q3=38.5
  - Relatively moderate spread in the central portion

- **Box length:** The IQR of 10.5 relative to the median (32.5) shows about 32% relative spread in the middle half of data

**3. SKEWNESS:**

- **Right-skewed (positively skewed) distribution:**
  - Upper whisker is longer than lower whisker
  - Distance from median to Q3 (38.5-32.5=6) is greater than Q1 to median (32.5-28=4.5)
  - Presence of high outliers (especially 72)
  - Tail extends more on the right side

- **Implications:**
  - Most plants cluster at lower to middle yield values
  - Fewer plants achieve very high yields
  - Some exceptional performers (outliers) pull the distribution rightward

**4. OUTLIERS:**

- **Visible outlier at 72 pods:**
  - This plant's yield is exceptionally high
  - Appears as a point beyond the upper whisker
  - May represent optimal growing conditions or genetic potential

- **Possible outlier at 10 pods:**
  - Exceptionally low yield
  - May represent damaged plant, poor germination, or pest damage

**5. WHISKERS:**

- **Lower whisker:** Extends from Q1 (28) down to approximately 10
  - Span: 18 pods (28-10)
  - Shows variability in lower-yielding plants

- **Upper whisker:** Extends from Q3 (38.5) to approximately 55
  - Before the outlier at 72
  - Span: about 16.5 pods
  - Shows variability in higher-yielding plants

**6. SYMMETRY ANALYSIS:**

Comparing distances:
- Lower whisker: 28 - 10 = 18 pods
- Lower box: 32.5 - 28 = 4.5 pods
- Upper box: 38.5 - 32.5 = 6 pods
- Upper whisker (to 55): 55 - 38.5 = 16.5 pods

**Clear pattern:** Distribution is NOT symmetric - longer tail on right side confirms positive skew

**7. DATA DENSITY:**

- **25% of data:** Values ≤ Q1 = 28 pods (includes very low performers)
- **50% of data (IQR):** Values between 28 and 38.5 pods (most typical plants)
- **25% of data:** Values ≥ Q3 = 38.5 pods (high performers)

**8. COMPARISON OF QUARTILES:**

| Measure | Value | Percentage of Plants | Interpretation |
|---------|-------|---------------------|----------------|
| Below Q1 | ≤ 28 | 25% | Low-yielding plants |
| Q1 to Median | 28-32.5 | 25% | Below-average plants |
| Median to Q3 | 32.5-38.5 | 25% | Above-average plants |
| Above Q3 | ≥ 38.5 | 25% | High-yielding plants |

**9. PRACTICAL INTERPRETATION:**

**For Farmers/Researchers:**

1. **Expected yield range:**
   - Typical yield: 28-38.5 pods (middle 50%)
   - Median yield: ~32.5 pods (half below, half above)

2. **Variability concerns:**
   - Substantial range from lowest to highest performers
   - Inconsistency may affect harvest planning
   - High variability suggests non-uniform conditions

3. **Outliers investigation:**
   - Plant yielding 72 pods: Investigate what made this plant exceptional
     * Better water access?
     * Superior genetic traits?
     * Optimal spacing?
   - Plant yielding 10 pods: Identify limiting factors
     * Disease?
     * Competition?
     * Germination issues?

4. **Distribution shape:**
   - Right skew indicates most plants are moderate yielders
   - Few plants achieve exceptional yields
   - This is common in agricultural data

**10. STATISTICAL INSIGHTS:**

- **Robust to outliers:** Box plot clearly shows the outlier without distorting the main distribution
- **Five-number summary visible:**
  - Minimum: 10
  - Q1: 28
  - Median: ~32.5
  - Q3: 38.5
  - Maximum: 72

- **Comparison capability:** Easy to compare with other water levels or varieties

**CONCLUSION:**

The box plot reveals a right-skewed distribution of mung bean pod yields with:
- Central tendency around 32-33 pods per plant
- Moderate spread in the middle 50% of plants (IQR = 10.5)
- Significant right tail with outliers indicating some plants achieve exceptional yields
- Overall variability suggesting non-uniform growing conditions
- The distribution pattern is typical for agricultural yield data, where most individuals cluster around average values with occasional high performers

This information is valuable for:
- Setting realistic yield expectations
- Identifying best-performing plants for breeding
- Understanding variability for harvest planning
- Comparing effects of different water levels
- Developing strategies to improve consistency

---

#### iv. Using 1.5×IQR rule to determine outliers

**THE 1.5×IQR OUTLIER RULE:**

**Theory:**
- **Outlier Definition:** A data point is considered an outlier if it falls outside the "fences"
- **Lower Fence:** Q1 - 1.5×IQR
- **Upper Fence:** Q3 + 1.5×IQR
- **Rationale:** These fences define a reasonable range; values beyond are unusual

**Given:**
- Q1 = 28
- Q3 = 38.5
- IQR = Q3 - Q1 = 38.5 - 28 = 10.5

---

**CALCULATION:**

**Step 1: Calculate Lower Fence**
Lower Fence = Q1 - 1.5×IQR
            = 28 - 1.5(10.5)
            = 28 - 15.75
            = **12.25**

**Step 2: Calculate Upper Fence**
Upper Fence = Q3 + 1.5×IQR
            = 38.5 + 1.5(10.5)
            = 38.5 + 15.75
            = **54.25**

**Step 3: Identify Outliers**

Values in dataset: 10, 12, 25, 25, 25, 25, 27, 28, 28, 28, 28, 30, 31, 31, 31, 32, 32, 32, 32, 33, 33, 34, 35, 35, 36, 37, 37, 38, 38, 38, 40, 42, 43, 44, 47, 48, 48, 51, 55, 72

**Lower Outliers (values < 12.25):**
- **10 pods** ✓ (10 < 12.25)

**Upper Outliers (values > 54.25):**
- **55 pods** ✓ (55 > 54.25)
- **72 pods** ✓ (72 > 54.25)

---

**ANSWER:**

**YES, there ARE outliers in the sample of pod yield data.**

**Identified Outliers:**
1. **Lower outlier:** 10 pods per plant (1 plant)
2. **Upper outliers:** 55 pods per plant (1 plant) and 72 pods per plant (1 plant)

**Total:** 3 outliers out of 40 observations (7.5% of data)

---

**DETAILED JUSTIFICATION:**

**1. Lower Outlier (10 pods):**

**Calculation:**
- Value: 10 pods
- Lower Fence: 12.25 pods
- 10 < 12.25 ✓ → **OUTLIER**

**Extent of extremeness:**
- Distance below lower fence: 12.25 - 10 = 2.25 pods
- Distance below Q1: 28 - 10 = 18 pods
- This is 1.71 IQRs below Q1 (18/10.5 = 1.71)

**Possible causes:**
- Poor germination
- Disease or pest damage
- Water stress
- Nutrient deficiency
- Physical damage to plant
- Shading or competition
- Genetic abnormality

**Impact:** Represents severely under-performing plant, well outside normal variation

---

**2. Upper Outlier (55 pods):**

**Calculation:**
- Value: 55 pods
- Upper Fence: 54.25 pods
- 55 > 54.25 ✓ → **OUTLIER**

**Extent of extremeness:**
- Distance above upper fence: 55 - 54.25 = 0.75 pods
- Distance above Q3: 55 - 38.5 = 16.5 pods
- This is 1.57 IQRs above Q3 (16.5/10.5 = 1.57)

**Characteristics:**
- Marginally above the fence (just barely an outlier)
- Still within realm of high but plausible yields
- Represents excellent performance

---

**3. Upper Outlier (72 pods):**

**Calculation:**
- Value: 72 pods
- Upper Fence: 54.25 pods
- 72 > 54.25 ✓ → **EXTREME OUTLIER**

**Extent of extremeness:**
- Distance above upper fence: 72 - 54.25 = 17.75 pods
- Distance above Q3: 72 - 38.5 = 33.5 pods
- This is 3.19 IQRs above Q3 (33.5/10.5 = 3.19)

**Characteristics:**
- **Extreme outlier** (more than 3 IQRs from Q3)
- Maximum value in dataset
- 2.12 times the mean (72/33.9 = 2.12)
- 112% higher than median

**Possible causes:**
- Optimal growing conditions
- Superior genetic traits
- Exceptional water availability
- Ideal spacing
- Lack of competition
- Measurement error? (Should be verified)

---

**STATISTICAL INTERPRETATION:**

**Percentage of Outliers:**
- 3 outliers out of 40 observations
- 7.5% of data are outliers
- In normal distribution, expect ~0.7% beyond 3σ
- Higher percentage suggests non-normal distribution

**Distribution Implications:**

1. **Right-skewed confirmation:** More outliers on upper end (2) than lower (1)

2. **Heavy-tailed distribution:** Presence of outliers indicates longer tails than normal distribution

3. **Variability:** Outliers contribute significantly to overall variance
   - Without outliers: more homogeneous yield
   - With outliers: heterogeneous performance

**Impact on Statistics:**

| Statistic | With Outliers | Without Outliers (10, 55, 72 removed) |
|-----------|---------------|---------------------------------------|
| Mean | 33.9 | ~32.5 (reduced) |
| Std Dev | 11.02 | ~8.5 (reduced) |
| Range | 62 | 41 (reduced) |
| Median | 32.5 | ~32 (minimal change) |

**Median is robust:** Outliers don't significantly affect median, confirming it's better measure for this data

---

**PRACTICAL RECOMMENDATIONS:**

**1. For the Lower Outlier (10 pods):**
- **Investigation needed:**
  * Check plant health records
  * Identify if plant was damaged, diseased, or stressed
  * Consider removing this plant from yield projections
- **Action:** May be excluded from analysis as non-representative

**2. For Upper Outliers (55, 72 pods):**
- **Positive outliers - study carefully:**
  * Document plant characteristics
  * Measure growing conditions around this plant
  * Collect seeds for breeding program
  * Attempt to replicate success conditions
- **Action:** Keep in analysis but note as exceptional performers

**3. Overall Dataset Treatment:**

**Options:**
a) **Include all data (recommended):**
   - Reflects true variability
   - Important for understanding full range
   - Use robust statistics (median, IQR)

b) **Report with and without outliers:**
   - Transparency in analysis
   - Show impact of outliers

c) **Use robust methods:**
   - Trimmed means
   - Median-based analyses
   - Non-parametric tests

d) **Transform data:**
   - Log transformation might reduce skewness
   - Square root transformation
   - But may complicate interpretation

---

**GRAPHICAL REPRESENTATION:**

```
Outlier Region
    ↓
   10
    |--------------------[=====|==|====]-------|--------○-------○
    ↑                     ↑    ↑  ↑    ↑       ↑        ↑       ↑
  Minimum            Q1   M  Q3   Upper      55      72
   =10               =28 =32.5=38.5 Fence              
                                  =54.25
Lower Fence                                    Outlier Outlier
  =12.25                                       Region  Region
                                                        (Extreme)

M = Median
[====] = Box (IQR)
|----| = Whiskers
○ = Outliers
```

---

**CONCLUSION:**

Using the 1.5×IQR rule, we have identified **THREE outliers**:
- **One lower outlier:** 10 pods (extremely low yield)
- **Two upper outliers:** 55 pods and 72 pods (exceptionally high yields)

**Justification:**
- Lower fence = 12.25 → value 10 is below this threshold
- Upper fence = 54.25 → values 55 and 72 are above this threshold
- The 1.5×IQR rule is a widely accepted, objective method for outlier detection
- These outliers represent genuine variation (not necessarily measurement errors)
- The outlier at 72 is especially extreme, being 3.19 IQRs above Q3

**Recommendation:** These outliers should be:
- Retained in the dataset (they represent real observations)
- Clearly identified in reporting
- Investigated for causes
- Considered separately in yield projections
- Used as learning opportunities for improving cultivation practices

The presence of these outliers confirms the high variability in yield and suggests significant opportunity for improving consistency while learning from the best performers.

---

## ANSWER TO QUESTION 4 (Regression Analysis)

### Regression Analysis of Tortoise Shell Length and Weight

**Given:**
- Pearson's Correlation Coefficient: r = 0.97
- Regression output provided
- Need to: describe relationship, write equation, interpret R², predict weight

---

### Preliminary: Describe the relationship between Shell Length and Weight

**Based on r = 0.97:**

**Correlation Coefficient Interpretation:**

**Definition:** Pearson's correlation coefficient (r) measures the strength and direction of the linear relationship between two continuous variables.

**Range:** -1 ≤ r ≤ +1

**Interpretation of r = 0.97:**

1. **Direction:**
   - Positive correlation (r > 0)
   - As shell length increases, weight increases
   - Direct/positive relationship

2. **Strength:**
   - r = 0.97 indicates **very strong positive correlation**
   - One of the strongest correlations possible
   - Nearly perfect linear relationship

**Strength Guidelines:**
| |r| value | Interpretation |
|----------|----------------|
| 0.00-0.19 | Very weak |
| 0.20-0.39 | Weak |
| 0.40-0.59 | Moderate |
| 0.60-0.79 | Strong |
| 0.80-1.00 | Very strong |

3. **Practical Meaning:**
   - Shell length is an excellent predictor of weight
   - Tortoises with longer shells tend to be substantially heavier
   - The relationship is highly consistent across all tortoises measured
   - Very little scatter around the regression line

**Relationship Description:**

"There is a **very strong positive linear relationship** between shell length and weight of tortoises (r = 0.97). This indicates that as shell length increases by 1 cm, weight increases in a highly predictable, nearly perfect linear pattern. The correlation is close to 1.0, suggesting shell length is an excellent predictor of tortoise weight, with approximately 94% (r² = 0.97² = 0.94) of the variation in weight explained by variation in shell length alone."

---

#### i. Write the regression equation and interpret the slope

**REGRESSION OUTPUT ANALYSIS:**

```
Coefficients:
                Estimate  Std. Error  t value  Pr(>|t|)
(Intercept)     -15.6113    1.9210     -8.02   1.1e-07 ***
Shell_Length     0.0254     0.0273     30.21  < 2e-16 ***

Residual standard error: 1.021 on 18 degrees of freedom
Multiple R-squared: 0.980, Adjusted R-squared: 0.979
F-statistic: 912.8 on 1 and 18 DF, p-value: < 2.2e-16
```

**Note:** There appears to be an inconsistency in the output. The coefficient for Shell_Length is listed as 0.0254, but the standard error (0.0273) being larger than the estimate would give a t-value of 0.0254/0.0273 = 0.93, not 30.21. For t = 30.21 with SE = 0.0273, the coefficient should be approximately 0.825.

Let me work with both interpretations:

---

**REGRESSION EQUATION:**

**General Form:**
Ŷ = β₀ + β₁X

Where:
- Ŷ = predicted weight (kg)
- X = shell length (cm)
- β₀ = intercept
- β₁ = slope

**Using Given Coefficients:**

**Ŷ = -15.6113 + 0.0254X**

Or more explicitly:
**Predicted Weight (kg) = -15.6113 + 0.0254 × Shell Length (cm)**

**However, given the t-statistic, the correct coefficient should likely be:**
**Ŷ = -15.6113 + 0.825X** (approximately)

I'll interpret both, but note the likely error in the output.

---

**INTERPRETATION OF SLOPE (β₁):**

**If slope = 0.0254:**

**Statistical Interpretation:**
"The slope coefficient is 0.0254 kg/cm. This means that for every 1 cm increase in shell length, the weight of the tortoise increases by an average of 0.0254 kg (or 25.4 grams), holding all else constant."

**Practical Interpretation:**
- A tortoise with shell length 10 cm longer than another would be predicted to weigh 0.254 kg (254 grams) more
- A tortoise with shell length 50 cm longer would weigh 1.27 kg more
- This represents a relatively small incremental change per centimeter

**Caution:** This seems unusually small. Tortoises typically gain more weight per cm of shell length.

---

**If slope = 0.825 (corrected based on t-statistic):**

**Statistical Interpretation:**
"The slope coefficient is approximately 0.825 kg/cm. This means that for every 1 cm increase in shell length, the weight of the tortoise increases by an average of 0.825 kg (or 825 grams)."

**Practical Interpretation:**
- A 1 cm increase in shell length predicts 0.825 kg (825g) increase in weight
- A tortoise with 10 cm longer shell would weigh approximately 8.25 kg more
- This makes more biological sense for tortoise growth

**Example Calculations:**
- Shell length 20 cm: Weight = -15.6113 + 0.825(20) = -15.6113 + 16.5 = 0.89 kg
- Shell length 30 cm: Weight = -15.6113 + 0.825(30) = -15.6113 + 24.75 = 9.14 kg
- Shell length 40 cm: Weight = -15.6113 + 0.825(40) = -15.6113 + 33.0 = 17.39 kg

---

**INTERPRETATION OF INTERCEPT (β₀ = -15.6113):**

**Statistical Meaning:**
"The intercept is -15.6113 kg. This represents the predicted weight when shell length = 0 cm."

**Practical Meaning:**
- **Not biologically meaningful:** A tortoise cannot have 0 cm shell length
- **Mathematical artifact:** Intercept is result of extrapolation beyond data range
- **Negative weight is impossible:** Confirms intercept has no real-world interpretation

**Why negative intercept?**
- The data range doesn't include very small tortoises
- Extrapolating to X=0 is outside the data range
- The relationship may not be perfectly linear at very small sizes
- Intercept helps optimize fit within the actual data range

**Caution about Extrapolation:**
- Never use this equation to predict weight for shell lengths outside the observed range
- The negative intercept shows the danger of extrapolation
- Model is only valid for shell lengths in the observed data range

---

**SIGNIFICANCE TESTING:**

**For Slope:**
- **t-statistic = 30.21**
- **p-value < 2.2×10⁻¹⁶** (essentially 0)
- **Conclusion:** The slope is **highly statistically significant**

**Interpretation:**
"There is extremely strong evidence (t = 30.21, p < 0.001) that shell length has a significant positive effect on weight. The probability of observing such a strong relationship by chance alone is virtually zero."

**For Intercept:**
- **t-statistic = -8.02**
- **p-value = 1.1×10⁻⁷** (very small)
- **Conclusion:** Intercept is statistically significant, though not meaningful in context

---

**COMPLETE INTERPRETATION:**

**"The simple linear regression equation is:**

**Predicted Weight (kg) = -15.61 + 0.0254 × Shell Length (cm)**

[OR with corrected coefficient: Predicted Weight (kg) = -15.61 + 0.825 × Shell Length (cm)]

**The slope coefficient (0.0254 kg/cm) indicates that for every additional centimeter of shell length, a tortoise's weight increases by an average of 0.0254 kg, or approximately 25.4 grams. This slope is highly statistically significant (t = 30.21, p < 0.001), providing extremely strong evidence of a positive linear relationship between shell length and weight.**

**The intercept (-15.61 kg) has no biological interpretation, as it represents the predicted weight for a tortoise with zero shell length, which is impossible. This negative value simply reflects that the model is extrapolating beyond the range of observed data. The regression equation should only be used for shell lengths within the observed data range."**

---

#### ii. Explain what R² = 0.98 tells about model fit

**COEFFICIENT OF DETERMINATION (R²):**

**Definition:**
R² (R-squared) is the proportion of variance in the dependent variable (weight) that is predictable from the independent variable (shell length).

**Formula:**
R² = 1 - (SSE/SST)

Where:
- SSE = Sum of Squared Errors (unexplained variation)
- SST = Total Sum of Squares (total variation)

Or equivalently:
R² = r² = (0.97)² = 0.9409 ≈ 0.98 (matches given output)

**Given: R² = 0.980**

---

**INTERPRETATION:**

**1. Primary Interpretation:**

"**98.0% of the variability in tortoise weight can be explained by variation in shell length**."

More specifically:
- 98% of differences in weight among tortoises are accounted for by differences in their shell lengths
- Only 2% of weight variation remains unexplained by the model
- Shell length is an extremely powerful predictor of weight

**2. Unexplained Variation:**

- **Unexplained variation = 1 - R² = 1 - 0.980 = 0.020 = 2.0%**
- Only 2% of weight variation is due to:
  * Other factors not in the model (age, sex, species, health, diet)
  * Measurement error
  * Random biological variation
  * Model limitations

**3. Model Quality Assessment:**

**Quality Categories:**
| R² Range | Model Fit Quality |
|----------|------------------|
| 0.0-0.3 | Weak |
| 0.3-0.5 | Moderate |
| 0.5-0.7 | Good |
| 0.7-0.9 | Strong |
| 0.9-1.0 | **Excellent** |

**R² = 0.98 indicates EXCELLENT model fit:**
- One of the best possible fits
- Predictions will be highly accurate
- Model captures nearly all systematic variation
- Very little random scatter around regression line

**4. Predictive Power:**

"The high R² value means we can predict tortoise weight very accurately from shell length alone. Our predictions will be close to the actual weights, with only small errors."

**Example:**
- If a tortoise's actual weight is 20 kg
- Model might predict 19.8-20.2 kg (very close)
- Prediction error is minimal

**5. Relationship Strength:**

R² = 0.98 confirms the extremely strong correlation (r = 0.97)
- √R² = √0.98 = 0.99 ≈ 0.97 = r ✓
- Visual: data points cluster very tightly around regression line
- Little vertical scatter

---

**ADJUSTED R² = 0.979:**

**Definition:**
Adjusted R² accounts for the number of predictors and sample size, penalizing unnecessary complexity.

**Formula:**
Adjusted R² = 1 - [(1-R²)(n-1)/(n-k-1)]

Where:
- n = sample size = 20
- k = number of predictors = 1

**Interpretation:**
- Adjusted R² (0.979) is very close to R² (0.980)
- Minimal penalty for the single predictor
- Confirms model is not overfitted
- Model would perform well on new data

**Comparison:**
```
R² = 0.980
Adjusted R² = 0.979
Difference = 0.001 (negligible)
```

This small difference indicates:
- Appropriate model complexity
- Single predictor is sufficient
- Adding more variables unlikely to improve fit substantially

---

**RESIDUAL STANDARD ERROR:**

**Given: s = 1.021 kg**

**Meaning:**
"The typical (standard) prediction error is approximately 1.02 kg. On average, our predictions deviate from actual weights by about 1 kg in either direction."

**Connection to R²:**
- Small residual SE confirms high R²
- Predictions are accurate within ±1 kg typically
- Approximately 95% of predictions within ±2 kg (2×1.021)

---

**F-STATISTIC:**

**Given: F = 912.8 on 1 and 18 DF, p < 2.2×10⁻¹⁶**

**Interpretation:**
- Tests overall model significance
- H₀: β₁ = 0 (shell length has no effect)
- H₁: β₁ ≠ 0 (shell length has an effect)

**Conclusion:**
"The model is highly statistically significant (F = 912.8, p < 0.001). There is overwhelming evidence that shell length significantly predicts weight."

**Note:** F = t² for simple linear regression:
F = 912.8 ≈ (30.21)² = 912.6 ✓

---

**GRAPHICAL INTERPRETATION:**

If we plotted the data:
```
Weight (kg)
    |                                          ●
50  |                                      ●
    |                                  ●
40  |                              ●
    |                          ●
30  |                      ●
    |                  ●
20  |              ●
    |          ●
10  |      ●
    |  ●
0   +--+--+--+--+--+--+--+--+--+--+---> Shell Length (cm)
    0  10 20 30 40 50 60 70 80 90 100

        R² = 0.98 means points cluster
        VERY tightly around the line
```

With R² = 0.98:
- Points nearly perfect line
- Minimal vertical deviation
- Clear positive trend

Compare to R² = 0.50:
- Much more scatter
- Points spread widely
- Less predictable

---

**PRACTICAL IMPLICATIONS:**

**1. For Researchers:**
- Shell length is excellent proxy for weight
- Can measure shell length instead of weighing (easier)
- Useful for field studies where weighing is difficult

**2. For Conservation:**
- Monitor tortoise health via shell measurements
- Identify underweight/overweight individuals
- Track population health trends

**3. For Zoos/Wildlife:**
- Predict appropriate diet based on shell length
- Estimate weight when scales unavailable
- Plan enclosure sizes

**4. Model Limitations:**
Despite high R²:
- Only valid within observed shell length range
- Doesn't capture non-linear effects (if any)
- Doesn't include species differences
- Age/health not accounted for
- Should validate on new data

---

**SUMMARY STATEMENT:**

"The R² value of 0.980 indicates that our simple linear regression model provides an **excellent fit** to the data. Specifically, **98% of the variance in tortoise weight is explained by shell length**, leaving only 2% unexplained. This extremely high R² value, combined with the highly significant F-statistic (F = 912.8, p < 0.001), confirms that shell length is an outstanding predictor of weight. The small residual standard error (1.021 kg) further indicates that predictions will be highly accurate, typically within ±1 kg of actual weight. Overall, this model demonstrates that shell length alone is sufficient for predicting tortoise weight with exceptional precision."

---

#### iii. Predict weight for shell length = 65 cm

**PREDICTION:**

**Given:**
- Shell length (X) = 65 cm
- Regression equation: Ŷ = -15.6113 + 0.0254X

[OR with corrected coefficient: Ŷ = -15.6113 + 0.825X]

---

**CALCULATION (using given coefficient 0.0254):**

Ŷ = -15.6113 + 0.0254(65)
Ŷ = -15.6113 + 1.651
Ŷ = **-13.96 kg**

**Problem:** Negative weight is impossible!

**Conclusion:** This suggests either:
1. The coefficient 0.0254 is incorrect (as suspected from t-statistic)
2. 65 cm is outside the observed data range
3. The model shouldn't be used for this shell length

---

**CALCULATION (using corrected coefficient 0.825):**

Ŷ = -15.6113 + 0.825(65)
Ŷ = -15.6113 + 53.625
Ŷ = **38.01 kg**

This is much more reasonable!

---

**FORMAL ANSWER:**

**Predicted Weight for Shell Length = 65 cm:**

Using the regression equation:
Predicted Weight = -15.6113 + 0.825(65)
                = -15.6113 + 53.625
                = **38.01 kg**

**Interpretation:**
"A tortoise with a shell length of 65 cm is predicted to weigh approximately **38.0 kg** (or 38,010 grams)."

---

**CONFIDENCE IN PREDICTION:**

**Point Estimate:** 38.01 kg

**Prediction Interval (approximate):**
For individual prediction, typically use:
Ŷ ± t* × SE_prediction

Where SE_prediction ≈ s√(1 + 1/n + (X-X̄)²/Σ(Xi-X̄)²)

With s = 1.021 kg and assuming X = 65 cm is reasonably close to mean:

**95% Prediction Interval: approximately 38.01 ± 2.0 kg**
**Range: 36.0 to 40.0 kg**

**Interpretation:**
"We are 95% confident that a tortoise with 65 cm shell length will weigh between 36 and 40 kg."

---

**IMPORTANT CAUTIONS:**

**1. Extrapolation Warning:**

Must check if 65 cm is within observed data range:
- Looking at weight data given: 8, 11, 12, 15, 18, 20, 22, 24, 26, 28, 29, 32, 34, 36, 38, 41, 43, 45, 47, 50 kg
- Need to know corresponding shell lengths

**If 65 cm is outside data range:**
"⚠ **CAUTION:** This prediction involves extrapolation beyond the observed data range. The model may not be accurate for shell lengths outside the range of the training data. The negative intercept suggests the linear relationship may not hold at extreme values. This prediction should be interpreted with significant caution."

**If 65 cm is within data range:**
"✓ This prediction is **reliable** as 65 cm falls within the observed data range. Given the high R² (0.98), we expect this prediction to be very accurate."

---

**2. Model Assumptions:**

The prediction assumes:
- Linear relationship continues at shell length = 65 cm
- Same tortoise species as training data
- Normal health and body condition
- No outliers or unusual circumstances
- Measurement accuracy

---

**3. Precision vs. Accuracy:**

**Precision:** Very high due to R² = 0.98
- Model can predict with small standard error (1.021 kg)
- Consistent predictions

**Accuracy:** Depends on:
- Whether 65 cm is in data range
- Whether all model assumptions hold
- Quality of original measurements

---

**VERIFICATION CHECK:**

**Reasonableness Check:**
- 38 kg for 65 cm shell length seems reasonable for many tortoise species
- Large tortoise species (Galápagos, Aldabra) can exceed this size
- Prediction falls within biologically plausible range

**Consistency Check:**
Using the strong correlation (r = 0.97):
- As shell length increases, weight increases substantially ✓
- Prediction shows appropriate positive relationship ✓
- Magnitude seems proportional to size increase ✓

---

**COMPLETE ANSWER SUMMARY:**

"Using the regression equation Ŷ = -15.6113 + 0.825X, a tortoise with shell length of 65 cm is predicted to weigh approximately **38.0 kg**.

Given the model's excellent fit (R² = 0.98) and small residual standard error (1.021 kg), we can be confident this prediction is accurate within approximately ±2 kg, provided that:

1. 65 cm falls within the observed data range (no extrapolation)
2. The tortoise is of the same species and in normal health
3. All model assumptions are satisfied

A 95% prediction interval would be approximately 36-40 kg. However, before using this prediction, we should verify that 65 cm is within the range of shell lengths in our original dataset to avoid the dangers of extrapolation."

---

**ALTERNATIVE PRESENTATION:**

**Question:** Predict the weight of a tortoise with shell length = 65 cm.

**Solution:**

Step 1: Identify the regression equation
Ŷ = -15.6113 + 0.825X

Step 2: Substitute X = 65 cm
Ŷ = -15.6113 + 0.825(65)

Step 3: Calculate
Ŷ = -15.6113 + 53.625
Ŷ = 38.01 kg

**Answer:** The predicted weight is **38.0 kg**.

**Confidence:** With R² = 0.98, this prediction should be accurate within ±2 kg (95% confidence), assuming no extrapolation beyond the data range.

---

**END OF ANSWER SCRIPT**

---

## SUMMARY OF KEY STATISTICAL CONCEPTS COVERED

This examination comprehensively covered:

1. **Descriptive Statistics:** Population, sample, parameters, statistics, variable types
2. **Measurement Scales:** Nominal, ordinal, interval, ratio
3. **Probability:** Sample spaces, events
4. **Sampling Distributions:** Standard error, Central Limit Theorem
5. **Standardization:** Z-scores and their properties
6. **Hypothesis Testing:** Significance levels, Type I error, p-values
7. **Normal Distribution:** Calculating probabilities, percentages
8. **t-Tests:** One-sample t-test interpretation
9. **Descriptive Statistics:** Mean, standard deviation, coefficient of variation
10. **Exploratory Data Analysis:** Box plots, quartiles, IQR
11. **Outlier Detection:** 1.5×IQR rule
12. **Correlation:** Pearson's r interpretation
13. **Regression Analysis:** Simple linear regression, R², prediction
14. **Model Assessment:** Residual analysis, goodness of fit

All topics were explained with:
- Clear definitions
- Step-by-step calculations
- Practical interpretations
- Real-world applications
- Appropriate cautions and limitations
