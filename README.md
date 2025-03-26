# Chemistry Dataset Analysis

This repository contains an interactive analysis of a chemistry dataset, examining student performance, exercise difficulty, time spent, and feedback impact.

## Overview

The analysis explores a comprehensive chemistry dataset containing student answers, scores, response times, and feedback for various chemistry exercises. The goal is to identify patterns in student performance and provide insights for improving chemistry education.

## Key Findings

- **Average score** across exercises is 60.98, with 55.12% of submissions achieving perfect scores
- **Significant variation in exercise difficulty**, with success rates ranging from 7% to 97%
- **Time spent on exercises** varies widely, with an average of 28.43 minutes per exercise
- **Feedback appears to be provided** primarily for incorrect answers or challenging exercises
- **Very weak correlation** between time spent and scores achieved (-0.0842)

## Interactive Dashboard

You can also view the GitHub Pages version of this analysis at:
[[https://chemistry-dataset-analysis.github.io](https://ocalak.github.io/chemistry-dataset-analysis/)]([https://chemistry-dataset-analysis.github.io](https://ocalak.github.io/chemistry-dataset-analysis/))


## Analysis Components

### 1. Student Performance Analysis

- Identification of top-performing students
- Analysis of success rates across different student groups
- Examination of time efficiency in relation to performance

### 2. Exercise Difficulty Analysis

- Ranking of exercises by difficulty level
- Identification of the most challenging concepts
- Analysis of success rates across different exercise types

### 3. Time Analysis

- Distribution of time spent on exercises
- Identification of most time-consuming exercises
- Analysis of the relationship between time spent and performance

### 4. Feedback Impact Assessment

- Analysis of exercises with and without feedback
- Comparison of performance with and without feedback
- Statistical significance testing of feedback effects


## Repository Contents

- `index.html`: Main interactive dashboard page
- `visualizations.html`: Interactive data exploration tools
- `test.html`: Functionality test page
- `data.csv`: Dataset file (sample data)
- `README.md`: This documentation file
- `_config.yml`: GitHub Pages configuration

## How to Use - R Analysis

To run the analysis locally:

1. Clone this repository
2. Place your `dataset.csv` file in the repository directory
3. Open `chemistry_analysis.Rmd` in RStudio
4. Install required packages if prompted
5. Click "Knit" to generate an interactive HTML report

## Technologies Used

- **Web Dashboard**: HTML, CSS (Tailwind), JavaScript, Chart.js
- **Data Analysis**: R, tidyverse, plotly, DT
- **R Markdown**: For reproducible research document
- **GitHub Pages**: For hosting the interactive web version
