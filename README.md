# Penguins-Statistical-Analysis-and-Linear-Regression-Modeling

## Project Overview

This project explores the Palmer Penguins dataset using exploratory data analysis (EDA) and simple linear regression to investigate the relationship between penguin physical characteristics and body mass.

The analysis focuses on identifying meaningful feature relationships, building an interpretable regression model, and validating model assumptions through diagnostic evaluation.

---

## Project Objectives

- Explore and understand the structure of the Palmer Penguins dataset
- Perform data cleaning and preprocessing
- Analyze distributions and relationships between variables
- Develop a simple linear regression model
- Evaluate regression assumptions using residual diagnostics

---

## Dataset Information

This project uses the **Palmer Penguins dataset**, available through Seaborn’s built-in datasets.

The dataset contains biological measurements collected from penguins observed at **Palmer Station, Antarctica**.

### Dataset Summary

| Attribute | Value |
|----------|------|
| Dataset | Palmer Penguins |
| Records | 344 |
| Features | 7 |
| Source | Seaborn |

---

## Data Dictionary

| Column | Type | Description |
|--------|------|-------------|
| species | string | Penguin species |
| island | string | Island where penguin was observed |
| bill_length_mm | float | Bill length (mm) |
| bill_depth_mm | float | Bill depth (mm) |
| flipper_length_mm | float | Flipper length (mm) |
| body_mass_g | float | Body mass (g) |
| sex | string | Penguin sex |

---

## Methodology

### 1. Data Preparation
- Loaded dataset from Seaborn
- Removed missing observations
- Filtered data to retain Adelie and Gentoo penguins

### 2. Exploratory Data Analysis
- Summary statistics
- Missing value assessment
- Distribution analysis
- Pairwise relationship analysis

### 3. Statistical Modeling
A simple linear regression model was fitted:

\[
Body\ Mass = \beta_0 + \beta_1(Bill\ Length)
\]

### 4. Model Diagnostics
Regression assumptions were evaluated using:

- Residual distribution
- Q–Q Plot
- Residual vs Fitted analysis

---

## Key Findings

- Bill length demonstrated a strong positive relationship with body mass
- Linear regression achieved an **R² of 0.769**
- Approximately **76.9% of body mass variability** was explained by bill length
- Residual diagnostics suggested acceptable model behavior

Regression equation:

\[
body\_mass\_g = -1707.29 + 141.19 \times bill\_length\_mm
\]

Interpretation:

For every **1 mm increase in bill length**, predicted body mass increases by approximately **141 g**.

---

## Project Structure

```text
datasets/
│
notebooks/
│
outputs/
│
README.md
```

---

## Technologies Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Statsmodels
- Quarto

---

## Outputs

Project outputs include:

- Exploratory visualizations
- Regression summary statistics
- Residual diagnostics
- Rendered analytical report

---

## Repository

This repository contains the complete workflow from data preparation to statistical modeling and evaluation.
