# Chicago Socioeconomic Data Analysis (SQL & Python)

This project is a comprehensive analysis of real-world socioeconomic data from the City of Chicago. It demonstrates how to build a data pipeline starting from a live CSV source, storing it in an SQLite database, and performing exploratory data analysis (EDA) using SQL and Python.

## 🎯 Objectives
* **Data Engineering**: Fetching data from the Chicago Data Portal and migrating it to a local SQLite database.
* **SQL Querying**: Using SQL magic commands in Jupyter to perform complex queries and aggregate data.
* **Data Visualization**: Analyzing the relationship between economic hardship and income using statistical plots.

## 📊 Dataset Overview
The dataset contains six socioeconomic indicators and a "Hardship Index" for each Chicago community area (2008–2012). Key variables include:
* **Community Area Name**: Neighborhood identifier.
* **Per Capita Income**: Average income per person.
* **Hardship Index**: A score from 1 to 100 representing economic difficulty.
* **Unemployment & Poverty Rates**: Percentage of residents aged 16+ unemployed or living below the poverty line.

## 🛠️ Tech Stack
* **Language**: Python 3
* **Database**: SQLite
* **Libraries**: `pandas`, `sqlite3`, `seaborn`, `matplotlib`
* **SQL Extension**: `ipython-sql`

## 🚀 Key Insights from Analysis
* **Data Scale**: The dataset contains records for 78 community areas in Chicago.
* **Hardship**: Riverdale was identified as the community area with the highest hardship index (98.0).
* **Correlation**: A clear negative correlation exists between Per Capita Income and the Hardship Index—as income rises, hardship significantly decreases.



## 📝 How to Use
1. Clone this repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install ipython-sql pandas seaborn matplotlib
