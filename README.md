# Data-Wrangling-project-with-Udacity
Data Analysis Project

## Project Overview
This project is a comprehensive data analysis endeavor completed as part of the Udacity Data Analyst Nanodegree in collaboration with Palestinian Launchpad. The project involves gathering, assessing, cleaning, and analyzing a car dataset to answer specific research questions and draw meaningful insights. The entire process is documented using Jupyter Notebooks.

## Project Steps

### Step 1: Gather Data
#### 1.1. Problem Statement
In this project, I aim to analyze various attributes of cars, including fuel efficiency, engine size, horsepower, and other specifications. Specifically, I will investigate trends and correlations among these attributes to understand what factors influence car performance and efficiency. To accomplish this, I will wrangle datasets from multiple sources.

#### 1.2. Data Collection Methods
I gathered the car dataset using different methods:
1. **Car Specifications Dataset**: Downloaded manually from a reputable online dataset repository.

This dataset was chosen due to its comprehensive coverage of various car attributes and relevance to the research question.

### Step 2: Assess Data
The dataset was assessed for quality and structural issues using the following attributes:
- **Completeness**: Ensuring no critical data is missing.
- **Validity**: Verifying data conforms to the expected formats and ranges.
- **Accuracy**: Checking for correct and precise data entries.
- **Consistency**: Ensuring uniformity across the dataset.
- **Uniqueness**: Removing duplicate records.

### Step 3: Clean Data
Data cleaning involved addressing the identified issues to enhance data quality and tidiness:
- Missing values were handled using appropriate imputation methods.
- Inconsistent data formats were standardized.
- Duplicate entries were removed.
- Irrelevant columns were dropped to streamline the analysis.

The cleaned data was validated both visually and programmatically to ensure the cleaning process was successful.

### Step 4: Update the Data Store
The cleaned datasets were saved in a structured format:
- Different versions of the data (raw and cleaned) were maintained.
- Informative names were used for dataset files to indicate their contents and processing stage.
- The cleaned data was stored in CSV files for easy access and further analysis.

### Step 5: Answer the Research Question
#### 5.1. Define and Answer the Research Question
Using the cleaned data, I explored the research question: "What factors influence car performance and efficiency?" Two visualizations were produced to illustrate the findings:
1. A scatter plot showing the relationship between engine size and fuel efficiency.
2. A bar chart comparing horsepower and fuel efficiency across different car models.

#### 5.2. Reflection
Given more time, I would delve deeper into additional data quality and structural issues, such as exploring outliers and potential confounding variables. Further, I would expand the analysis to include other car attributes and explore their impact on performance and efficiency.

## Project Files
- **data_gathering.ipynb**: Jupyter Notebook documenting the data gathering process.
- **data_assessment.ipynb**: Jupyter Notebook for assessing data quality and structure.
- **data_cleaning.ipynb**: Jupyter Notebook detailing the data cleaning steps.
- **data_analysis.ipynb**: Jupyter Notebook for analyzing the cleaned data and answering the research question.
- **data/**: Directory containing the raw and cleaned datasets.

## Getting Started
To run the project on your local machine, ensure you have the following software installed:
- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, and other necessary Python packages (see requirements.txt for details)

Clone the repository and open the Jupyter Notebooks to explore the project steps in detail.

## Acknowledgements
This project is part of the Udacity Data Analyst Nanodegree program in collaboration with Palestinian Launchpad. Special thanks to the course instructors and my peers for their support and guidance.
