# Job Market Skill Radar 📊

## Project Overview

Job Market Skill Radar is a data analysis project that investigates the technical skills mentioned in job postings for Data Analyst, Data Scientist, and Business Analyst roles.

The goal is to understand skill demand, compare job roles, and help beginners identify useful learning priorities based on job-posting evidence.

## Objectives

- Identify frequently mentioned technical skills.
- Compare skill requirements across job roles.
- Visualize skill demand using charts and heatmaps.
- Build a simple personal skill gap analyzer.
- Extend the analysis into machine learning.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Regular expressions
- Google Colab

## Dataset

This project initially uses a historical Glassdoor data science job-postings dataset.

Source: https://github.com/PlayingNumbers/ds_salary_proj

The dataset is a historical snapshot and does not represent current job-market demand. Findings will be interpreted within the limitations of the available sample.

## Methodology

1. Load and inspect the dataset.
2. Clean missing values and duplicate records.
3. Categorize selected job titles.
4. Extract skill mentions from job descriptions.
5. Calculate skill frequencies and percentages.
6. Compare skills across job roles.
7. Visualize results and document findings.

## Visualizations

Planned visualizations include:

- Overall skill-demand ranking
- Skill comparison heatmap by job role
- Personal skill gap analysis

## Future Improvements

- Add more recent job-posting data from authorized sources.
- Improve skill extraction using natural language processing.
- Build an interactive dashboard.
- Train and evaluate a job-role classification model.
- Explore skill demand over time when suitable historical data is available.

## Limitations

Keyword matching can miss synonyms, context, and skills mentioned in negative statements. Job titles may also be classified incorrectly. Results describe the analyzed dataset and should not be treated as definitive measures of the entire job market.

## Author

Created as a learning project to develop practical Data Analytics and Data Science skills.
