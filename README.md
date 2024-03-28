# Urban Insights Explorer 🌆

Urban Insights Explorer is a data exploration and analysis tool developed during the hackathon. It leverages data from the U.S. Census Bureau to provide insights into demographics at the city and zip code levels, focusing on California and Washington states. The project includes data collection, preprocessing, modeling, and visualization components.

## Problem Statement 🎯

The goal of this project is to create a visual dashboard that allows users to explore and compare demographic attributes across different cities and zip codes. The dashboard provides insights into population characteristics, occupations, median income, and more, using data from the '2017-2021 ACS 5-year Estimates' dataset.

## Technologies Used 🛠️

- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
- ![Streamlit](https://img.shields.io/static/v1?style=for-the-badge&message=Streamlit&color=FF4B4B&logo=Streamlit&logoColor=FFFFFF&label=)
- ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
- ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
- ![Requests](https://img.shields.io/badge/Requests-2CA5E0?style=for-the-badge&logo=python&logoColor=white)
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![Scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
- ![Statsmodels](https://img.shields.io/badge/Statsmodels-3766AB?style=for-the-badge&logo=python&logoColor=white)

## Features ⚙️

1. **Data Collection:** 
   - Retrieves data from the U.S. Census Bureau using an API key.
   - Focuses on demographic attributes such as population size, age distribution, racial composition, educational attainment, and more.

2. **Data Preprocessing:**
   - Handles missing values, outliers, and duplicates.
   - Performs aggregation and data cleaning to ensure accuracy and consistency.
   - Utilizes statistical methods and visualizations for outlier detection and handling.

3. **Model Building:**
   - Implements logistic regression and ridge regression models to predict and analyze demographic trends.
   - Evaluates model performance using classification metrics and accuracy scores.
   - Detects multicollinearity and applies appropriate techniques for model refinement.

4. **Visualization and Insights:**
   - Generates interactive charts, graphs, and tables using Matplotlib, Seaborn, and Streamlit.
   - Displays trend analysis, seasonal decomposition, histograms, box plots, heatmaps, and correlation plots.
   - Provides actionable insights and statistical summaries to aid decision-making.

5. **Dashboard Interface:**
   - Built with Streamlit for an intuitive and user-friendly experience.
   - Allows users to select cities/zip codes, compare demographic attributes, and customize visualization settings.
   - Enables interactive data exploration and drill-down capabilities for detailed analysis.

## Usage 📝

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/urban-insights-explorer.git
