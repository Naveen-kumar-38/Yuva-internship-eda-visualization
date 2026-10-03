# YUVA Internship – Week 2
## Exploratory Data Analysis and Visualization

This project was completed as part of the YUVA Internship – Virtual Data Science with Python Trainee program.

## Objective

The objective of this task is to perform Exploratory Data Analysis (EDA) on a public dataset and identify important patterns, trends, relationships, and insights using Python data analysis and visualization libraries.

## Dataset

The Automobile dataset from the UCI Machine Learning Repository was used for this project.

The dataset contains information about automobiles, including:

- Automobile make
- Fuel type
- Body style
- Engine size
- Horsepower
- Curb weight
- City MPG
- Highway MPG
- Price
- Other technical specifications

The cleaned dataset contains 205 records and 26 columns.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## EDA Performed

The following analysis was performed:

1. Dataset structure and statistical summary
2. Price distribution analysis
3. Automobile make distribution
4. Fuel type analysis
5. Body style analysis
6. Horsepower distribution
7. Engine size vs. price analysis
8. Horsepower vs. price analysis
9. City MPG vs. price analysis
10. Price comparison by body style
11. Correlation heatmap
12. Price correlation analysis
13. Summary of important EDA findings
14. Final dataset validation

## Key Findings

- Toyota was the most common automobile make in the dataset.
- Sedan was the most common body style.
- Gasoline vehicles were more common than diesel vehicles.
- The average horsepower was approximately 102.89.
- The average city fuel efficiency was approximately 25.2 MPG.
- The average highway fuel efficiency was approximately 30.68 MPG.
- Automobile price showed strong positive relationships with curb weight, engine size, horsepower, width, and length.
- City MPG and highway MPG showed a very strong positive relationship.

## Project Structure

```text
├── data
│   └── cleaned_automobile.csv
├── screenshots
│   ├── 01_statistical_summary.png
│   ├── ...
│   └── 14_final_validation.png
├── output
│   └── eda_summary.csv
├── Task_2_EDA.ipynb
└── README.md
