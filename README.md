
# Student Stress Analysis
### Exploratory Data Analysis | Statistical Analysis | Python

## Project Overview

This project analyzes student stress levels across different academic stages using a real-world dataset obtained from Kaggle.

Academic stress can negatively affect students' well-being, learning experiences, and academic performance. Understanding the factors associated with stress is essential for educational institutions to develop effective student support strategies.

The project focuses on identifying differences in stress levels among **high school, undergraduate, and postgraduate students**, as well as examining the relationships between academic stress and contributing factors.

The analysis combines **Exploratory Data Analysis (EDA), data visualization, descriptive statistics, and inferential statistical testing** to generate actionable insights.

## Project Objectives

- Analyze the distribution of students across different academic stages.
- Compare average Stress Index values among high school, undergraduate, and postgraduate students.
- Investigate relationships between stress levels and academic pressures.
- Determine whether differences in average stress levels across academic stages are statistically significant.
- Identify the factors most strongly associated with student stress.
- Provide data-driven recommendations to help educational institutions improve student well-being.

## Dataset

**Source:** Kaggle – Student Academic Stress Dataset
https://www.kaggle.com/datasets/poushal02/student-academic-stress-real-world-dataset?resource=download

The dataset contains information about students from different academic stages, including:

- **Academic Stage:** High school, undergraduate, and postgraduate.
- **Stress Index:** A numerical measure of student stress.
- **Peer Pressure:** Pressure experienced from peers.
- **Academic Pressure from Home:** Academic expectations and pressure from family.
- **Academic Competition:** Competitive pressure experienced in academic environments.

The analysis focuses on identifying how these factors relate to students' reported stress levels.

## Exploratory Data Analysis

### 1. Student Distribution by Academic Stage

The dataset is dominated by undergraduate students, followed by high school and postgraduate students.

This unequal distribution is important when interpreting comparisons between academic stages.

### 2. Average Stress Index by Academic Stage

| Academic Stage | Average Stress Index |
|---|---:|
| High School | 3.83 |
| Undergraduate | 3.69 |
| Postgraduate | Approximately 3.70 |

**Key Insight:**
High school students have the highest average Stress Index, although the differences between academic stages are relatively small.

### 3. Academic Pressure from Home vs. Stress Index

Students experiencing higher levels of academic pressure from home generally report higher stress levels.

This suggests a positive relationship between family-related academic pressure and student stress.

### 4. Academic Competition vs. Stress Index

Higher levels of academic competition are generally associated with higher Stress Index values.

Students reporting stronger academic competition tend to experience greater academic stress.

## Descriptive Statistics

Central tendency measures were used to understand the overall characteristics of student stress.

**Key Findings:**

- High school students have the highest mean Stress Index (**3.83**).
- Undergraduate students have the lowest mean Stress Index (**3.69**).
- The median and mode are both **4** across all academic stages.

These findings indicate that a Stress Index of 4 is a common and representative value across the different student groups.

## Inferential Statistical Analysis

### 1. One-Way ANOVA

**Research Question:**

Is there a statistically significant difference in the mean Stress Index among high school, undergraduate, and postgraduate students?

**Hypotheses:**

- **H₀:** The mean Stress Index is equal across all academic stages.
- **H₁:** At least one academic stage has a different mean Stress Index.

**Results:**

| Metric | Value |
|---|---:|
| F-statistic | 0.198 |
| P-value | 0.821 |
| Significance Level (α) | 0.05 |

**Interpretation:**

Since the p-value (0.821) is greater than 0.05, we **fail to reject the null hypothesis**.

There is insufficient statistical evidence to conclude that average stress levels differ significantly across academic stages.

Although high school students have the highest average Stress Index, this difference is not statistically significant.

### 2. Spearman's Rank Correlation

Spearman's Rank Correlation was used to evaluate the strength and direction of relationships between the Stress Index and its contributing factors.

**Overall Findings:**

- **Peer Pressure:** Strongest positive correlation with Stress Index (ρ = 0.453).
- **Academic Pressure from Home:** Positive and statistically significant correlation.
- **Academic Competition:** Positive and statistically significant correlation.

**Findings by Academic Stage:**

| Academic Stage | Key Finding |
|---|---|
| High School | Peer Pressure shows the strongest correlation with Stress Index. |
| Undergraduate | All three factors show positive and statistically significant correlations. |
| Postgraduate | Only Academic Pressure from Home shows a statistically significant negative correlation. |

**Important Note:**

The postgraduate group contains only **11 students**, so the subgroup findings should be interpreted cautiously due to the small sample size.

## Key Insights

1. **Academic Stage Is Not a Significant Differentiator**
   - Although average stress levels vary slightly, One-Way ANOVA indicates no statistically significant differences across academic stages.

2. **Peer Pressure Has the Strongest Overall Association**
   - Peer Pressure demonstrates the strongest correlation with the Stress Index (ρ = 0.453).

3. **Academic and Social Pressures Are Associated with Stress**
   - Academic Pressure from Home and Academic Competition also show positive and statistically significant correlations with student stress.

4. **Stress-Related Factors Differ Across Academic Stages**
   - The relationships between stress and contributing factors vary across student groups, suggesting that student support strategies may need to be tailored to different academic stages.

## Recommendations

Based on the findings, educational institutions should consider the following strategies:

### 1. Reduce Peer Pressure
- Develop peer counseling and mentoring programs.
- Encourage supportive rather than excessively competitive learning environments.
- Promote student awareness of social pressure and stress management.

### 2. Improve Academic Support
- Provide academic counseling and stress management workshops.
- Help students develop effective study habits and time management skills.
- Encourage balanced academic expectations.

### 3. Strengthen Family and Student Communication
- Educate families about the potential effects of excessive academic pressure.
- Encourage constructive communication between students, parents, and educators.

### 4. Develop Targeted Student Support Programs
- Consider different stress-related factors across academic stages.
- Conduct additional research with more balanced sample sizes to improve the reliability of subgroup comparisons.

## Limitations

- The dataset contains an unequal number of students across academic stages.
- The postgraduate sample is relatively small, which may limit the reliability of subgroup findings.
- Correlation does not imply causation; statistically significant relationships do not establish that academic or social pressures directly cause stress.
- The findings are based on the available dataset and may not represent all student populations.

## Tech Stack

**Programming Language**
- Python

**Data Analysis**
- Pandas
- NumPy

**Data Visualization**
- Matplotlib
- Seaborn
- Tableau

**Statistical Analysis**
- SciPy
- Descriptive Statistics
- One-Way ANOVA
- Spearman's Rank Correlation

**Development Environment**
- Jupyter Notebook

## 🏁 Conclusion

This project demonstrates how data analytics and statistical methods can be used to investigate student stress and identify factors associated with academic well-being.

The analysis reveals that **academic stage does not significantly differentiate average student stress levels**, while **Peer Pressure, Academic Pressure from Home, and Academic Competition** are positively associated with the Stress Index overall.

Among these factors, **Peer Pressure shows the strongest overall correlation (ρ = 0.453)**.

These findings provide useful insights for educational institutions seeking to design more effective student support programs and promote healthier learning environments.


