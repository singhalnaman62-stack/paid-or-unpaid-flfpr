# Paid or Unpaid?

What decides whether a working rural Indian woman earns an income?

## Question
Among rural Indian women who are already working, what determines
whether she is paid (self-employment or wages) versus an unpaid
helper in a family enterprise?

## Data
Periodic Labour Force Survey (PLFS), Calendar Year 2025,
Ministry of Statistics and Programme Implementation (MoSPI).
Free download: https://microdata.gov.in

## Method
Weighted logistic regression (primary model) and a Random Forest
(used only as a diagnostic check), on ~68,500 rural working women
aged 25-54.

## Key findings
- Household type is the largest factor: women in wage-earning
  households are 36 points more likely to be paid than women in
  farming households.
- Marriage lowers paid probability by 28 points.
- Graduate education raises paid probability by ~10 points.
- Land ownership showed an unexpected small positive association,
  flagged as an open question.

## Repository structure
- `code/` — Python notebook with the full analysis
- `charts/` — exported chart images
- `report/` — written report (if added)

Raw survey data is not included, per MoSPI's terms of use.
Download it yourself from the link above to reproduce this analysis.