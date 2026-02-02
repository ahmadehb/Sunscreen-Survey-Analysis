# Sunscreen Usage and Attitudes Statistical Analysis

This project presents a full end-to-end statistical analysis of a large-scale sunscreen usage and attitudes survey conducted in collaboration with a Stony Brook University School of Medicine research team. The goal was to identify behavioral, knowledge-based, and structural drivers of sunscreen use, producing clinically interpretable results suitable for publication.

## Project Overview
* **Objective**: Identify key drivers and barriers to sunscreen use and prevention behaviors.
* **Collaboration**: Conducted with Stony Brook University School of Medicine research team.
* **Output**: Comprehensive statistical analysis with publication-ready results.

## Features
* **Data Processing**:
  * Comprehensive cleaning and transformation of raw survey data.
  * Reduction of 67 original variables into analyzable features.
  * Validation of multi-select responses and identification of invalid combinations.
* **Exploratory Data Analysis**:
  * Distributional analysis and contingency tables.
  * Visualization of usage patterns, seasonality, and incentives.
* **Statistical Modeling**:
  * **Ordinal Logistic Regression**: For modeling ordered outcomes (e.g., frequency of use).
  * **Multinomial Logistic Regression**: For categorical behavioral outcomes.
  * Multiple-testing control using Benjamini–Hochberg-adjusted p-values.
* **Model Diagnostics**:
  * Association measures (Cramér's V).
  * Multicollinearity checks (Variance Inflation Factor).

## Tools and Technologies
* **R**: Primary language for all statistical analysis and visualization.
* **R Markdown**: For reproducible analysis and report generation.
* **Statistical Packages**: `tidyverse`, `MASS`, `nnet`, `car`, `vcd`.
* **Visualization**: `ggplot2`, `ggpubr` for publication-quality graphics.

## Dataset
* **Sample Size**: 1,008 respondents.
* **Variables**: 67 original survey variables.
* **Content Areas**:
  * Demographics and school affiliation
  * Sunscreen usage frequency and seasonality
  * Application locations and body coverage
  * Perceived incentives and barriers
  * Knowledge and prevention beliefs
  * Awareness of free sunscreen dispensers

**Note**: For privacy and IRB compliance, the raw dataset and original survey instrument are not publicly shared
