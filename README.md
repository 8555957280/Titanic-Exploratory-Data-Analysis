# Titanic-Exploratory-Data-Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The objective is to explore the dataset, identify patterns and trends, analyze relationships between variables, and find important insights related to passenger survival.

## Objective

The main objectives of this project are:

- Understand the structure and characteristics of the Titanic dataset.
- Perform statistical analysis using Pandas.
- Identify missing values and handle them appropriately.
- Analyze distributions using histograms and boxplots.
- Explore relationships using scatterplots.
- Analyze correlations using a heatmap.
- Compare multiple variables using a pairplot.
- Identify patterns, trends, and anomalies in the dataset.
- Summarize the important findings from the analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The analysis uses the Titanic `train.csv` dataset.

The dataset contains **891 passenger records and 12 columns**, including information such as:

- Passenger ID
- Passenger Class
- Name
- Sex
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket
- Fare
- Cabin
- Port of Embarkation
- Survival Status

## EDA Process

The following steps were performed:

1. Loaded the Titanic dataset using Pandas.
2. Inspected the dataset using `info()` and `describe()`.
3. Analyzed categorical variables using `value_counts()`.
4. Identified missing values.
5. Handled missing values in Age, Cabin, and Embarked.
6. Created histograms to understand distributions.
7. Created boxplots to identify potential outliers.
8. Analyzed survival counts.
9. Compared survival by Sex and Passenger Class.
10. Created a scatterplot to analyze Age and Fare.
11. Created a correlation heatmap.
12. Created a pairplot to analyze relationships between numerical variables.
13. Summarized the major findings.

## Missing Value Handling

Missing values were found in:

- Age
- Cabin
- Embarked

The missing values were handled as follows:

- **Age:** Filled using the median.
- **Cabin:** Filled with `"Unknown"`.
- **Embarked:** Filled using the mode.

## Key Findings

- The Titanic dataset contains 891 passengers and 12 columns.
- Approximately 38% of passengers survived, while around 62% did not survive.
- Female passengers had a much higher survival rate than male passengers.
- Passengers in 1st class generally had better survival outcomes than passengers in 2nd and 3rd class.
- Most passengers were young or middle-aged, with the median age around 28 years.
- Fare distribution was strongly right-skewed, with most passengers paying relatively low fares.
- Passenger Class and Fare showed a moderate negative correlation of approximately -0.55.
- SibSp and Parch showed a moderate positive correlation of approximately 0.41.
- Age and Fare did not show a strong visible relationship.
- Missing values in Age, Cabin, and Embarked were handled using median, `"Unknown"`, and mode imputation respectively.

## Project Files

| File | Description |
|---|---|
| `Task5_EDA_Titanic.ipynb` | Jupyter Notebook containing the complete EDA analysis and visualizations |
| `Task5_EDA_Titanic final.pdf` | PDF report of the analysis and findings |
| `train.csv` | Titanic dataset used for the analysis |

## Conclusion

The exploratory data analysis helped identify important patterns and relationships in the Titanic dataset. Passenger sex and passenger class showed noticeable differences in survival outcomes. The analysis also revealed the distribution of age and fare, relationships between numerical variables, and potential outliers.

This project demonstrates the use of Python, Pandas, Matplotlib, and Seaborn for performing Exploratory Data Analysis.
