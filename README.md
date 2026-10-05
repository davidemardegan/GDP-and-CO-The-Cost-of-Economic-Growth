# GDP and CO₂: The Cost of Economic Growth

Two-person statistics research project completed for **Mathematical Statistics** at Bocconi University (2026).

**Authors:** Davide Mardegan and Ascanio Schena

**[Read the full report](./gdp-co2.pdf)**

## Overview

This project studies the relationship between **economic growth** and **CO₂ emissions** across Italy and the BRICS economies from 1980 to 2022.

Using data from **Our World in Data**, the analysis asks whether GDP and CO₂ emissions are statistically associated and whether that relationship changes over time.

## Methods

The project uses:

- data cleaning and visualisation in R
- cross-country exploratory analysis
- Welch two-sample t-test
- logarithmic transformations
- simple log-log linear regression
- multiple regression with a time interaction
- residual diagnostics and model interpretation

## Results

The baseline log-log model found a statistically significant positive association between GDP and CO₂ emissions, with **R² ≈ 0.60**.

The extended model including time and an interaction term improved fit to **R² ≈ 0.69**.

The analysis explicitly distinguishes **correlation from causation** and discusses limitations including serial dependence, omitted variables, technological change and energy structure.

## Technologies

R · statistical analysis · hypothesis testing · linear regression · data visualisation

## Course context

**Mathematical Statistics — Bocconi University, 2026**
