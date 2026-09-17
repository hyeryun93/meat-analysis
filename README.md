# Meat pH Analysis

## Project Overview

This project investigates how meat pH changes over time.

Several statistical models were compared to determine an appropriate model for describing the relationship between storage time and pH.

The project also discusses how the analysis would differ depending on whether repeated measurements were collected from the same samples or from independent samples.

---

## Research Questions

1. Is a simple linear model sufficient to describe the pH–time relationship?

2. Does adding a quadratic term significantly improve model fit?

3. How should the data be analyzed if measurements are repeatedly collected from the same samples?

4. Can nonlinear regression provide a better description of the pH trajectory?

---

## Data

- `meat (1).csv`

---

## Statistical Methods

- Exploratory Data Analysis (EDA)
- Linear regression
- Quadratic regression
- ANOVA model comparison
- Firth logistic regression
- Asymptotic nonlinear regression
- Mixed-effects model (discussion)

---

## Main Findings

- The relationship between pH and time is nonlinear.

- Adding a quadratic term significantly improves model fit over a simple linear regression.

- An asymptotic nonlinear model provides an alternative description of pH decay.

- If measurements are repeatedly collected from the same samples, a mixed-effects model would be more appropriate than ordinary linear regression.

---

## Software

- R
- logistf
- tidyverse
