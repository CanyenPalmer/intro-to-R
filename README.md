# Intro to R – Data Science Starter Guide

This project provides a practical introduction to using R for data analysis. It is designed for beginners in analytics or data science, as well as for professionals transitioning from spreadsheet or other programming environments.

The content walks through fundamental data science operations in R, with hands-on examples using base R and `tidyverse`. The format is structured as a Quarto (`.qmd`) document for literate programming and reproducible workflows.

## Project Purpose

To equip new users with the foundational skills needed to perform exploratory data analysis (EDA), basic data wrangling, and simple visualizations using R.

## Technologies and Tools

- **R** – Statistical programming language
- **RStudio** – IDE for R development
- **Quarto / R Markdown** – For documentation and reproducible reporting
- **Tidyverse** – Data science packages including `dplyr`, `ggplot2`, and `readr`

## Key Concepts Covered

### Data Types and Structures

- Vectors, lists, matrices, data frames, and tibbles
- Atomic types: numeric, character, logical
- Indexing and subsetting with `[]`

### Data Import and Inspection

- Reading CSV and Excel files using `read.csv()`, `read_excel()`
- Exploring data with `head()`, `tail()`, `str()`, `glimpse()`, `summary()`

### Vectorized Operations

- Performing calculations across vectors
- Logical indexing and conditional filtering

### Control Structures and Functions

- `if` / `else` statements for conditional logic
- `for` and `while` loops
- Writing custom functions to automate tasks

### Exploratory Data Analysis

- Computing descriptive statistics (mean, median, sd)
- Basic plotting: `hist()`, `boxplot()`, `barplot()`
- Introduction to `ggplot2` for layered, grammar-based visualizations

## Learning Outcomes

By completing this guide, learners will be able to:

- Use R effectively for importing, inspecting, and manipulating data
- Apply vectorized thinking and logic to solve analytical problems
- Perform exploratory data analysis on real-world datasets
- Generate reproducible outputs using Quarto or R Markdown
- Build a strong foundation for advanced topics such as modeling or machine learning

## Relevance to Analytics and Data Science

The skills covered are directly applicable to:

- Business intelligence reporting
- Clinical or operational analytics
- Pre-modeling data preparation
- Automated report generation

This project builds the groundwork for working on more advanced workflows involving statistical modeling, dashboards, or machine learning in R.

## Getting Started

To run this project:

1. Open the `.qmd` file in RStudio.
2. Ensure you have the `tidyverse` package installed:
   ```r
   install.packages("tidyverse")
