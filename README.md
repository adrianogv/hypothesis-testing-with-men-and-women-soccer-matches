# Hypothesis Test on Mean Goals in FIFA World Cup Matches

This project analyzes whether there is a significant difference in the mean number of goals scored in women's and men's FIFA World Cup matches. By performing statistical hypothesis testing, it determines if the mean number of goals is the same across both categories, providing insights that could be valuable for sports analysts, coaches, and enthusiasts.

## Project Overview

The objective of this project is to test the null hypothesis that the mean number of goals scored in women's international soccer matches is equal to that in men's matches. Using official FIFA World Cup match data since **2002-01-01**, the project employs statistical methods to analyze goal-scoring patterns, assuming each match is independent and team form is ignored. The hypothesis test is conducted at a **10% significance level**.

## Dataset

The dataset comprises official FIFA World Cup matches for both women's and men's tournaments since January 1, 2002. Key columns in the dataset include:

- **date**: Date of the match
- **competition**: Name of the competition (e.g., FIFA World Cup)
- **gender**: Gender category of the match (Men's or Women's)
- **home_team**: Name of the home team
- **away_team**: Name of the away team
- **home_score**: Goals scored by the home team
- **away_score**: Goals scored by the away team
- **total_goals**: Total number of goals scored in the match

## Key Findings

The hypothesis test revealed the following:

- **P-value**: *[Insert calculated p-value here, e.g., 0.08]*
- **Result**: *[Insert "reject" or "fail to reject" based on the p-value]*

Based on the p-value obtained, which is *[less than/greater than]* the significance level of 0.10, we *[reject/fail to reject]* the null hypothesis. This indicates that there **is/is not** a significant difference in the mean number of goals scored between women's and men's FIFA World Cup matches.

**Example Interpretation**:

If the p-value is 0.08 and less than the significance level:

> With a p-value of 0.08, which is less than our 10% significance level, we reject the null hypothesis. This suggests there is a statistically significant difference in the mean number of goals scored in women's and men's FIFA World Cup matches.

## Future Work

Potential areas for further exploration include:

- **Multivariate Analysis**: Incorporate additional variables such as match location, team rankings, and player statistics to understand their impact on goal scoring.
- **Time Series Analysis**: Examine how the mean number of goals has evolved over time within each category.
- **Predictive Modeling**: Develop models to predict match outcomes or total goals based on historical data.
- **Comparative Studies**: Extend the analysis to other international tournaments or include data prior to 2002 for a more comprehensive view.

---

*Note: The actual p-value and result should be inserted where indicated after running the analysis with the provided code.*
