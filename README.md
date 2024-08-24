# Survey Data Analysis Project

Welcome to the Survey Data Analysis Project repository! This repository hosts the analysis and raw data from a comprehensive survey focused on technology usage, future trends, and demographic insights. The analysis is designed to provide valuable insights into the preferences and trends in the tech industry based on the responses collected.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
   - [m5_survey_data_technologies_normalised.csv](#m5_survey_data_technologies_normalisedcsv)
   - [m5_survey_data_demographics.csv](#m5_survey_data_demographicscsv)
3. [Report Details](#report-details)
4. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Usage](#usage)
5. [Data Analysis Summary](#data-analysis-summary)

## Project Overview

This project analyzes survey data to understand the current state of technology usage, predict future trends, and provide insights into the demographics of tech professionals. The survey covers various aspects, including:

- **Programming Languages:** The most used programming languages and those developers wish to learn next.
- **Databases:** Insights into the databases currently used and preferred for future projects.
- **Web Frameworks:** Popular web frameworks and those desired by developers in the near future.
- **Platforms:** Platforms commonly used in development and those expected to gain traction.
- **Demographics:** The demographic distribution of respondents, including age, gender, and education level.

The results of this analysis can help organizations and developers make informed decisions about the technologies they should focus on.

## Dataset Description

### m5_survey_data_technologies_normalised.csv

This CSV file contains normalized data related to the technologies used and desired by survey respondents. It includes fields such as:

- **Programming Languages:** The languages currently in use and those desired for the future.
- **Databases:** Types of databases currently in use and those that developers want to learn.
- **Web Frameworks:** The frameworks currently being used and those desired in the coming year.
- **Platforms:** Various platforms that respondents are working with or plan to work with.

### m5_survey_data_demographics.csv

This CSV file provides detailed demographic information of the survey respondents, including:

- **Gender:** Distribution of respondents by gender.
- **Age:** Age groups of respondents.
- **Education Level:** Educational background of respondents, categorized by degree types.
- **Country:** Geographical distribution of respondents.

## Report Details

The main report, `Survey_Data_Report_2024.pdf`, presents a detailed analysis of the survey data. It includes:

- **Visualizations:** Graphs and charts that illustrate key findings.
- **Trends:** Analysis of current and future technology trends.
- **Demographic Insights:** Breakdown of respondents by age, gender, and education.
- **Key Takeaways:** Summary of the most significant findings and their implications for the tech industry.

## Getting Started

### Prerequisites

To work with the data files and run any additional analysis, you'll need the following:

- Python 3.x
- Pandas
- Matplotlib or Seaborn for data visualization
- Jupyter Notebook (optional, for interactive analysis)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/survey-data-analysis.git
   cd survey-data-analysis

2. Install the required Python packages:

   ```bash
   pip install pandas matplotlib seaborn
   ```

### Usage

- **Viewing the Report:** Open `Survey_Data_Report_2024.pdf` to review the detailed findings.
- **Running Analysis:** Use the CSV files (`m5_survey_data_technologies_normalised.csv` and `m5_survey_data_demographics.csv`) to conduct your own analysis. You can load these files into a Python environment using Pandas and explore the data further.

Example code to load and preview the data:

```python
import pandas as pd

# Load the technologies data
tech_data = pd.read_csv('m5_survey_data_technologies_normalised.csv')
print(tech_data.head())

# Load the demographics data
demo_data = pd.read_csv('m5_survey_data_demographics.csv')
print(demo_data.head())
```

## Data Analysis Summary

The analysis revealed several key trends:

- **JavaScript** is the most widely used programming language, with strong demand for **Python** in the coming years.
- **PostgreSQL** and **MongoDB** are among the most desired databases for future projects.
- **React.js** and **Angular.js** are leading web frameworks, with significant interest in **Vue.js**.
- **Linux** and **Docker** are the top platforms used, with growing interest in **Kubernetes**.
