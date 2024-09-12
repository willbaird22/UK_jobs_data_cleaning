# Data Cleaning and Preparation: UK Data Science Job Postings

## Overview

This project focuses on cleaning and preparing a dataset of data science job postings in the United Kingdom. The goal of the project is to transform raw job posting data into a clean, structured format, enabling further analysis. Special attention was given to normalizing job titles and handling missing salary data.

## Dataset

The dataset includes the following columns:
- `Company`: Name of the hiring company.
- `Company Score`: Average rating of the company on Glassdoor.
- `Job Title`: Title of the job position.
- `Location`: Job location, including city and state.
- `Date`: Date the job was posted or updated.
- `Salary`: Estimated salary range for the position.
- `Skills`: Skills required for the position.

## Tools and Libraries

- **Python**
- **Pandas**
- **NumPy**
- **Regular Expressions (Regex)**

## Cleaning and Preparation Process

The project involves the following steps:
- Standardization of job titles (e.g., grouping similar roles like "data scientist" and "junior data scientist").
- Parsing and cleaning salary data, including handling missing values.
- Splitting the location column into separate city and country columns for better analysis.
- One-hot encoding of skills to allow skill frequency analysis.
  
## Getting Started

To reproduce this cleaning process or explore the dataset further, you will need the following libraries installed:

```bash
pip install pandas numpy
