# The Impact of Economic Downturns on Mothers' and Fathers' Time Usage in Households

This project analyzes how economic downturns, particularly the COVID-19 pandemic-induced recession, impacted the time usage of mothers and fathers in the United States. Using data from the American Time Use Survey (ATUS) for the years 2019, 2020, and 2021, the study examines differences in childcare, eldercare, and overall care time, as well as the gender-based disparities that emerged during this period.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Discussion and Implications](#discussion-and-implications)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction
Economic downturns significantly impact labor markets and household dynamics. This study investigates:
1. How economic downturns impact parental time usage.
2. Differences in time allocation between men and women during recessions.
3. How factors like age and employment status influence time spent on childcare and eldercare.

### Research Context
The COVID-19 pandemic recession caused dramatic shifts in unemployment rates and household responsibilities. This project builds on past research to analyze these impacts and understand how caregiving responsibilities shifted during and after the recession.

## Data
The analysis uses data from the **American Time Use Survey (ATUS)** for the years 2019, 2020, and 2021. Key statistics:
- **2019**: Pre-recession baseline
- **2020**: During the COVID-19 recession
- **2021**: Post-recession recovery

**Key Metrics Analyzed**:
- **Childcare Time**: Time spent on caring for children.
- **Eldercare Time**: Time spent on caring for elderly family members.
- **Total Care Time**: Combined childcare and eldercare time.

### Data Cleaning
- Invalid observations with care time ≤ 0 were excluded.
- The dataset includes approximately 6,300 valid observations for childcare and 1,000+ observations for eldercare.

## Methodology
A regression model was used to analyze how economic downturns influenced time usage. The model controls for:
- Gender
- Age
- Employment status (both respondent and spouse)

**Regression Model**:
Time = α + δ(Recession) + γ(Sex) + Xβ + ε

Where:
- `Recession` = Pre-recession, Recession, Post-recession
- `X` = Control variables like age, employment status, spouse employment status

## Key Findings
### Childcare Time
- Childcare time increased by **44.8 minutes** in 2020 compared to 2019.
- The increase persisted in 2021 but at a reduced level (**22 minutes** compared to 2019).

### Eldercare Time
- No significant change in eldercare time during or after the recession.
- Eldercare time increased with the respondent's age (+2.6 minutes per year).

### Gender Disparities
- Women consistently spent more time on childcare and total care than men, but the gap narrowed during the recession.
- The gender gap in childcare time followed a U-shaped trend, decreasing during the recession and widening again post-recession.

### Total Care Time
- The recession led to an increase in total care time, which partially reverted after the economy began recovering.

## Discussion and Implications
- Economic downturns redistribute time usage within households, with notable increases in childcare responsibilities.
- Gender disparities remain persistent, though they narrow during crises.
- Employment status significantly affects care time:
  - Full-time work reduces care time.
  - Spouse employment increases the respondent's care time.

These findings highlight the need for policies supporting work-life balance and gender equality in caregiving responsibilities, particularly during economic crises.

## Conclusion
This study reveals the lasting impact of the COVID-19 recession on household time allocation:
- Childcare responsibilities significantly increased and remained elevated post-recession.
- Gender disparities in care time persist but show resilience during crises.

Future research should examine long-term effects using more extensive datasets and consider additional variables like regional differences and income levels.

## References
1. American Time Use Survey (ATUS) Data: [Bureau of Labor Statistics](https://www.bls.gov/tus/)
2. Berik, G., & Kongar, E. (2011). Time use of mothers and fathers in hard times and better times.
3. Craig, L., & Mullan, K. (2011). How mothers and fathers share childcare.
4. Hartmann, H., English, A., & Hayes, J. (2010). Women and Men’s Employment and Unemployment in the Great Recession.

---

For more details, see the full analysis and results in this repository.
