# Bellabeat Case Study  
Data Analysis of Smart Device Usage Trends

---

## Project Overview

This case study analyzes smart device usage data to identify behavioral and physiological trends that can inform Bellabeat’s marketing strategy.

Using Fitbit activity data, the study evaluates relationships between:

- Daily physical activity (step count)
- Resting heart rate (approximated)
- Sleep efficiency
- Metabolic intensity (METs)

The objective is to generate evidence-based strategic recommendations for Bellabeat’s Membership platform.

---

## Business Context

Bellabeat is a high-tech wellness company focused on women's health. The company collects behavioral and physiological data through smart devices to provide personalized wellness insights.

This analysis supports the marketing analytics team in identifying trends that can drive:

- User engagement
- Behavioral segmentation
- Subscription growth
- Long-term retention

---

## Business Questions

1. What trends exist in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends influence Bellabeat’s marketing strategy?

---

## Dataset

Source:  
FitBit Fitness Tracker Data – Kaggle (CC0 Public Domain)

- 30 users
- Approximately 30 days of activity
- Daily and minute-level records
- Variables include steps, heart rate, sleep, and METs
- Data collected in 2016

---

## Tools & Technologies Used

- R
- tidyverse (dplyr, ggplot2)
- R Markdown
- Git & GitHub

---

## Methodology

The analysis followed the Google Data Analytics Case Study framework:

- Ask
- Prepare
- Process
- Analyze
- Share
- Act

Key processing steps included:

- Date standardization
- Daily aggregation of heart rate and METs
- Sleep efficiency calculation
- Left joins to preserve primary activity records
- Step-based behavioral segmentation (<5k, 5k–9,999, ≥10k)

---

## Key Insights

- Most users fall into Low or Moderately Active categories.
- Users achieving ≥5,000 daily steps show lower average resting heart rates.
- Higher activity levels correlate with improved sleep efficiency.
- Highly active users demonstrate greater metabolic intensity.
- Sleep tracking is inconsistently used across the sample.

---

## Top Three Strategic Recommendations

### 1. Promote the 5,000-Step Milestone

Position 5,000 daily steps as an achievable and meaningful health benchmark to increase engagement among low-active users.

### 2. Implement Activity-Based Segmentation

Leverage behavioral clustering (Low, Moderate, High Activity) to personalize marketing communication and membership content.

### 3. Strengthen Sleep Feature Engagement

Enhance onboarding and educational messaging to increase sleep tracking adoption and reinforce holistic wellness positioning.

---

## Project Structure


---

## Author

Andres Diaz  
Junior Data Analyst  
Portfolio Project – 2026

---

## Disclaimer

This project is an independent academic case study conducted for portfolio purposes. Bellabeat is used as a hypothetical business scenario.