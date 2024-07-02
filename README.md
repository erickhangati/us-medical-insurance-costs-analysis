# U.S. Medical Insurance Costs Analysis

## Project Overview

This project involves investigating a medical insurance costs dataset using Python. The dataset includes information such as age, sex, BMI, number of children, smoking status, region, and charges. The goal is to perform independent analysis on the dataset to uncover insights, trends, and potential correlations.

## Project Objectives

- Work locally on your own computer
- Import a dataset into your program
- Analyze a dataset by building out functions or class methods
- Use libraries to assist in your analysis
- Optional: Document and organize your findings
- Optional: Make predictions about a dataset’s features based on your findings

## Files in This Repository

- `us-medical-insurance-costs.ipynb`: Jupyter Notebook containing the code and analysis.
- `insurance.csv`: The dataset file containing medical insurance cost data.

## Dataset Description

The dataset `insurance.csv` contains the following columns:

- `age`: Age of the primary beneficiary
- `sex`: Insurance contractor gender (male/female)
- `bmi`: Body mass index, providing an understanding of body fat
- `children`: Number of children/dependents covered by the insurance
- `smoker`: Smoking status (yes/no)
- `region`: The beneficiary’s residential area in the US (northeast, southeast, southwest, northwest)
- `charges`: Individual medical costs billed by health insurance

## Running the Project

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/erickhangati/us-medical-insurance-costs-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd us-medical-insurance-costs-analysis
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook us-medical-insurance-costs.ipynb
    ```

## Analysis Process

The analysis is structured as follows:

### Data Exploration:
- Load the dataset using the `csv` module.
- Extract relevant columns into lists for further analysis.

### Statistical Analysis:
- Calculate the average age of the individuals in the dataset.
- Determine the majority region where most individuals come from.
- Calculate the difference in average medical insurance costs between smokers and non-smokers.
- Calculate the average age of individuals who have one child.