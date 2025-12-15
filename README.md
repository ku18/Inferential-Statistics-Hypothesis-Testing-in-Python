# Inferential Statistics & Hypothesis Testing in Python

This repository contains a practical, analyst-focused implementation of **inferential statistics and hypothesis testing** using Python.  
The project is designed to demonstrate how statistical tests are actually applied in real data analysis workflows — not just theory.

The notebook walks through **when to use which test, why it is chosen, how assumptions are checked, and how results are interpreted** from a data analyst’s perspective.

---

## Objective

To build a strong, interview-ready and job-ready understanding of hypothesis testing by:
- Applying statistical tests on real numerical and categorical data
- Validating assumptions instead of blindly applying tests
- Interpreting statistical outputs in business/educational context
- Distinguishing between parametric and non-parametric approaches

---

## Contents

The notebook covers the following major areas:

### 1. Data Preparation & Exploration
- Data import and inspection
- Basic EDA
- Handling nulls and data types
- Understanding distributions

### 2. Assumption Checks
- Normality testing (Shapiro-Wilk, KS Test)
- Homogeneity of variance
- Sample size and balance considerations
- Why assumption violations matter

### 3. Parametric Tests
- One-sample Z-test
- One-sample t-test
- Two-sample independent t-test
- Paired t-test
- One-way ANOVA
- Effect size (Eta Squared)
- Post-hoc analysis (Tukey HSD)

### 4. Non-Parametric Tests
- Mann–Whitney U Test
- Wilcoxon Signed-Rank Test
- Kruskal–Wallis Test
- Why non-parametric tests are often more realistic in real data

### 5. Categorical Data Analysis
- Chi-Square Test of Independence
- Expected vs Observed frequencies
- Cramér’s V for effect size

### 6. Correlation Analysis
- Pearson correlation (linear relationships)
- Spearman correlation (monotonic relationships)
- Why Spearman is preferred for non-normal data

---

##  Key Learnings

- Statistical tests are **decision tools**, not formulas
- Assumptions decide the test — not convenience
- Most real-world datasets violate normality
- Effect size matters as much as p-values
- Non-parametric tests are often more reliable for analysts
- Interpretation is more important than computation

---

##  Tools & Libraries Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib / Seaborn (for exploratory analysis)

---

##  How to Use

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/inferential-statistics-hypothesis-testing.git
