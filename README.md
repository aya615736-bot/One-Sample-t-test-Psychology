# One-Sample T-Test Analysis of Memory Scores

## Overview
This project evaluates whether the mean memory retention score of a sample differs significantly from a hypothesized population baseline standard using PSPP (an open-source alternative to IBM SPSS).

*Note: This analysis was conducted using a synthetic dataset created specifically for statistical practice and methodology demonstration.*

## Data Description
- **Data Source:** Synthetic / Demo Dataset (Created for SPSS/PSPP methodology practice purposes)
- **Sample Size (N):** 15 Participants
- **Variables:**
  - `Participant_ID`: Participant identifier (Nominal)
  - `Memory_Score`: Continuous scale score (Interval/Ratio)

## Key Findings (One-Sample T-Test Analysis)
- **Test Value (Hypothesized Population Mean):** $\mu = 20$
- **Statistical Test Result:** A one-sample t-test revealed that the average memory score was significantly higher than the baseline value of 20, $t(14) = 13.92, p < .001$.

## Software Used
- PSPP (IBM SPSS syntax compatible)

## Result (APA Style)
> A one-sample t-test was conducted to determine whether the average memory score of participants differed significantly from a baseline score of 20. The results indicated that the mean memory score ($M = 36.27, SD = 4.53$) was significantly higher than the baseline value of 20, $t(14) = 13.92, p < .001$ (Two-tailed). The mean difference was $16.27$ with a 95% confidence interval ranging from $13.76$ to $18.77$.
![PSPP output](Screenshot2026-11-05193627.png)
