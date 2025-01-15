# Mental Health Data Analysis Project

This project performs an analysis on global mental health disorder data, specifically schizophrenia, depressive, anxiety, bipolar, and eating disorders, using data from 1990 to 2019. The analysis includes trends over time, comparisons between countries, and correlations between different mental health disorders.

## Project Overview

The dataset contains the following columns:
- **Entity**: The country or region
- **Code**: Country code
- **Year**: Year of the data point (1990 - 2019)
- **Schizophrenia disorders (share of population)**: Age-standardized share of population affected by schizophrenia
- **Depressive disorders (share of population)**: Age-standardized share of population affected by depression
- **Anxiety disorders (share of population)**: Age-standardized share of population affected by anxiety
- **Bipolar disorders (share of population)**: Age-standardized share of population affected by bipolar disorders
- **Eating disorders (share of population)**: Age-standardized share of population affected by eating disorders

The project includes:
1. **Data loading and cleaning** using Python's Pandas library.
2. **Data visualization** using Matplotlib, Seaborn, and Plotly.
3. **Trend analysis** for specific countries and disorders over time.
4. **Correlation analysis** between different mental health conditions.

## Prerequisites

To run this project on your local machine, you need the following Python libraries:
- Pandas
- Matplotlib
- Seaborn
- Plotly

### Installation
You can install the required libraries using pip:
```bash
pip install pandas matplotlib seaborn plotly


How to Use
Open the Jupyter notebook mental_health_analysis.ipynb.
Make sure the dataset (1- mental-illnesses-prevalence.csv) is in the same folder as the notebook.
Run each cell to perform the following:
Data Loading: Load the CSV dataset into a Pandas DataFrame.
Data Cleaning: Handle missing values and duplicates.
Trend Visualization: Plot trends for mental health disorders across years.
Comparative Analysis: Compare the prevalence of disorders between countries.
Correlation Analysis: Examine the relationships between different disorders.
Key Features
Trend Analysis: Shows how the prevalence of mental health disorders changes over time for different countries.
Comparative Visualization: Compares the prevalence of mental health disorders in different countries for a specific year.
Correlation Matrix: Visualizes the relationships between different disorders using a heatmap.
Interactive Maps: Generates interactive choropleth maps for global comparisons (optional).
Contributing
If you would like to contribute to this project:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a pull request.
License
This project is open source and available under the MIT License.

Acknowledgments
The data used in this project is publicly available and sourced from various health organizations and research institutes.
This project utilizes open-source Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly.
