# Task-5_Exploratory_Data_Analysis
cat << 'EOF' > README.md
# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns and key factors that influenced passenger survival.

The analysis includes statistical summaries, data visualization, and correlation analysis using Python.

## Objective

- Understand the dataset structure  
- Perform statistical exploration  
- Visualize trends and relationships  
- Identify important survival factors  
- Summarize key insights  

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab / VS Code  

## Dataset Information

- Total Records: 891  
- Total Features: 12  
- Target Variable: Survived  

### Important Columns

- Survived  
- Pclass  
- Sex  
- Age  
- Fare  
- SibSp  
- Parch  
- Embarked  

## Analysis Performed

### Data Exploration
- .info()  
- .describe()  
- .value_counts()  

### Visualizations
- Count plots  
- Histograms  
- Boxplots  
- Pairplots  
- Correlation heatmap  

### Relationship Analysis
- Survival vs Gender  
- Survival vs Passenger Class  
- Survival vs Age  
- Survival vs Fare  

## Key Insights

- Female passengers had significantly higher survival rates.  
- First-class passengers survived more than second and third class.  
- Higher ticket fare positively correlated with survival.  
- Age had moderate influence on survival probability.  
- Socioeconomic status played an important role in survival outcomes.  

## Project Structure

Titanic-EDA/
│
├── eda.ipynb
├── titanic.csv
└── README.md
