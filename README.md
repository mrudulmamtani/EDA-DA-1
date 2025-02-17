# Exploratory Data Analysis (EDA) Assignment

## Overview

This repository contains the Exploratory Data Analysis (EDA) assignment, which focuses on analyzing smoking habits and their associated factors. The analysis is conducted using Python, leveraging libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## Dataset

The dataset used in this analysis is sourced from the [smoking.csv](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/smoking.csv) file. It includes the following variables:

- **Demographic Information:**
  - `gender`: Gender of the individual
  - `age`: Age of the individual
  - `marital_status`: Marital status
  - `highest_qualification`: Educational qualification
  - `nationality`: Nationality
  - `ethnicity`: Ethnic background
  - `gross_income`: Income level
  - `region`: Geographical region

- **Smoking Habits:**
  - `smoke`: Smoking status (Yes/No)
  - `amt_weekends`: Amount smoked on weekends
  - `amt_weekdays`: Amount smoked on weekdays
  - `type`: Type of tobacco used (e.g., packets, hand-rolled)

## Analysis Objectives

The primary objectives of this analysis are:

1. **Prevalence of Smokers:** Calculate the proportion of smokers versus non-smokers in the dataset.
2. **Smoking Frequency:** Analyze the average amount smoked on weekdays and weekends, and determine if there's a significant difference.
3. **Type of Tobacco Used:** Investigate the distribution of tobacco types among smokers.
4. **Education and Smoking:** Assess how different levels of education correlate with smoking habits.
5. **Identifying Relationships:** Calculate correlations between variables such as age, income, education, and amount smoked to identify significant associations.
6. **Age Trends:** Investigate if smoking habits change with age, such as starting or quitting smoking at certain age ranges.

## Repository Structure

- `Data/`: Contains the `smoking.csv` dataset.
- `Notebooks/`: Jupyter notebooks with detailed analysis and visualizations.
- `Scripts/`: Python scripts used for data processing and analysis.
- `README.md`: This file, providing an overview of the project.

## Getting Started

To replicate the analysis:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/salemprakash/EDA.git
   cd EDA
   ```

2. **Set Up the Environment:**
   - It's recommended to use a virtual environment:
     ```bash
     python -m venv eda_env
     source eda_env/bin/activate  # On Windows, use `eda_env\Scripts\activate`
     ```
   - Install the required packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Notebooks:**
   - Navigate to the `Notebooks/` directory and open the desired notebook using Jupyter:
     ```bash
     jupyter notebook
     ```
   - Execute the cells to perform the analysis.

## Results and Findings

The analysis yielded several insights:

- **Prevalence of Smokers:** The dataset indicates a certain percentage of individuals are smokers versus non-smokers.
- **Smoking Frequency:** On average, the amount smoked varies between weekdays and weekends, with statistical tests indicating whether the difference is significant.
- **Type of Tobacco Used:** Among smokers, there's a distribution across different types of tobacco products.
- **Education and Smoking:** Smoking habits show a correlation with educational levels, suggesting trends in smoking prevalence across different educational backgrounds.
- **Identifying Relationships:** Correlation analysis reveals associations between age, income, education, and smoking amounts.
- **Age Trends:** Smoking habits exhibit changes across different age groups, indicating patterns in initiation or cessation.

For detailed visualizations and statistical analyses, refer to the notebooks in the `Notebooks/` directory.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.


---

*Note: This analysis is for educational purposes and is based on the provided dataset. Interpretations and conclusions are drawn from the data and may not generalize beyond this dataset.* 
