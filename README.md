# data-analytics-projects-final


# Analysis of College Teacher Salaries

## Project Overview
This project analyzes how college affiliation influences professor salaries in Connecticut using descriptive statistics and basic data visualization.

## Objective
The goal of this project is to analyze how college title and institution influence professor salaries using descriptive statistics and visualization.

## Dataset
- **File name:** ct-professor-salaries.csv  
- **Description:** Public salary data for college professors in Connecticut.  
- **Key columns:**  
  - College  
  - Average All Pay  
  - Average Professor  
  - Associate Professor  
  - Assistant Professor  
  - Lecturer  
  - City  

The dataset is used locally and stored in the same directory as the notebook.

## Tools & Libraries
- Python  
- pandas  
- matplotlib  

## Methodology
1. Load the dataset locally.
2. Explore available columns and check for missing values.
3. Clean the data by removing rows with missing salary values.
4. Select Central Connecticut State University as the baseline comparison group.
5. Compare it with the University of Connecticut using the *Average All Pay* feature.
6. Use descriptive statistics and a bar chart to compare salary averages.

## Key Analysis Steps
- Data cleaning using `dropna()`
- Descriptive statistics using `.describe()`
- Mean salary comparison
- Visualization with a bar chart

## Visualization
A bar chart comparing average overall pay between:
- Central Connecticut State University (CCSU)
- University of Connecticut (UConn)

## Conclusion
University of Connecticut faculty have a higher average overall pay than those at Central Connecticut State University.  
This suggests that larger or research-focused institutions may offer higher compensation.  
However, the dataset may be biased due to reporting practices or missing forms of compensation.  
Future analysis should include academic rank, discipline, and cost-of-living adjustments.
