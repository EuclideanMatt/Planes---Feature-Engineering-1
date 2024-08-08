**Planes Feature Engineering #1**

**Overview**

This repository contains a Jupyter Notebook that performs feature engineering on plane data from a SQL Server database. The notebook demonstrates various data manipulation, analysis, and visualization techniques to extract meaningful insights and prepare the data for machine learning models.

**Repository Contents**

Planes - Feature Engineering #1.ipynb: The main Jupyter Notebook file containing the feature engineering process.

**Key Features**

_SQL Integration_: Connects to a SQL Server database and retrieves data from the flights table.

Data Exploration__: Provides an overview of the data, including data types and basic statistics.

_Feature Engineering_: 
Transforms and creates new features from the existing data to enhance the predictive power of machine learning models. 
This includes:

Deconstructing and cleaning date, time, and duration features.

Handling missing values and data type conversions.

Creating new features such as day, month, year, arv_hour, arv_min, dep_hour, dep_min, and total_dur.

_Data Expor_t: Saves the cleaned and engineered dataset back to the SQL Server database.

_Data Visualization_: Utilizes matplotlib and seaborn to visualize data trends and distributions.

**Data Sources**

planes.xlsx: Dataset containing flight information.

ind_loc.csv: Dataset containing latitude and longitude information.

indian_city_names.csv: Dataset containing city names.


**Key Steps in the Notebook**

Libraries and Database Connection:

Imports necessary libraries.
Connects to the SQL Server database and retrieves data from the flights table.
Data Exploration:

Displays basic information about the dataset, including data types and summary statistics.
Feature Engineering:

Creates new features from existing data.
Transforms categorical features into numerical representations.
Data Visualization:

Uses matplotlib and seaborn to visualize the distributions and relationships of features.
Data Export:

Saves the cleaned and engineered dataset back to the SQL Server database.
