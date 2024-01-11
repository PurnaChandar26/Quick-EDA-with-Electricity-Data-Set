Quick EDA with Electricity Data Set
===================================

Overview
--------

This repository contains a quick exploratory data analysis (EDA) of an electricity dataset. The dataset, named "Electrecity_data.csv," provides information about electricity-related features across different countries and regions. The analysis is performed using Python, and the key packages utilized include:

### Packages

-   Data Processing

    -   `numpy` for numerical operations
    -   `pandas` for data manipulation and analysis
-   Visualization

    -   `matplotlib` for creating visualizations
    -   `seaborn` for enhancing the visual appeal of plots
-   Statistics

    -   `scipy.stats` for statistical operations
-   File Path

    -   `os` for managing file paths

Dataset Information
-------------------

The dataset includes information about electricity-related features for various countries, such as net generation, distribution losses, exports, imports, installed capacity, net consumption, and net imports. The dataset spans from the year 1980 to 2021.

### Data Cleaning

-   Handling Missing Values: Initial inspection revealed missing values represented by '--.' Rows with missing values in the 'Country' column were removed.

-   Data Transformation: The data was transformed by melting and pivoting to enhance its usability.

Exploratory Data Analysis (EDA)
-------------------------------

### 1\. Overview of the Dataset

-   Information about the dataset, including data types and memory usage.
-   Identification and removal of missing values.
-   Conversion of data types for 'Year' and 'Value' columns.

### 2\. Data Transformation

-   Melting the dataset to a more usable format.
-   Setting appropriate data types for columns.

### 3\. EDA

#### 3.1. Correlation

-   Visualizing the correlation matrix of numerical features.

#### 3.2. Distribution (Numerical)

-   Summary plots for numerical features, including histograms, QQ plots, boxplots, and line plots to detect outliers.

#### 3.3. Frequency (Categorical)

-   Distribution of categorical features, including count plots and pie charts.

#### 3.4. Relationship

-   Introduction of a derived variable, 'losses per consumption,' and its analysis.
-   Correlation matrix and line plots depicting the relationship between 'losses per consumption' and other variables.

The analysis provides insights into the distribution, relationships, and potential outliers within the electricity dataset. The code and visualizations are organized to facilitate understanding and further exploration of the dataset.
