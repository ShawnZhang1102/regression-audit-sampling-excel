# Regression & Audit Sampling (Excel)

> Class Project · CIS 211, University of Rochester

Uses regression to explain charitable contributions — and to flag suspicious tax returns in an audit sample.

## What It Does

- **Multiple regression** on 719 tax returns: charitable contributions vs. adjusted gross income, number of dependents, age, and filing status (with dummy variables). R² = 0.74.
- **Single-variable regression** on the same data for comparison. R² = 0.69.
- **Prediction intervals**: builds 95% prediction intervals (using TINV) around the regression predictions.
- **Audit sampling**: applies the model to a 10,000-return audit sample and flags returns that fall outside their prediction intervals as outliers worth investigating.

## Tech Stack

Excel · Multiple linear regression · Dummy variables · Prediction intervals

## How to Run

Download `Regression-Audit-Sampling.xlsx` and open it in Excel. (GitHub cannot preview Excel files — download the file to view it.)

## Files

| File | What it is |
| --- | --- |
| `Regression-Audit-Sampling.xlsx` | Regressions, prediction intervals, and the audit sample |
