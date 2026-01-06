# GitHub Engagement Drivers (R)

A data science project analyzing what drives GitHub repository engagement (watchers) using statistical modeling in R.

## Project Overview
- Dataset: GitHub repository metadata (Kaggle)
- Sample size: 500 repositories
- Goal: Identify key factors influencing engagement

## Methods Used
- Data cleaning: tidyverse, janitor
- Multiple Linear Regression
- One-Way ANOVA (Programming Language)
- Two-Way ANOVA (Language × Popularity)

## Key Insights
- Stars are the strongest predictor of engagement
- Programming language has a statistically significant but smaller effect
- Popularity outweighs technical characteristics like age
## How to Run
1. Place the dataset in `Data/`
2. Open the `.Rproj` file in RStudio
3. Knit the R Markdown file

## Output
- HTML report included in this repository