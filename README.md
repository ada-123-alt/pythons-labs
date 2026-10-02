SCHOOL OF ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING, VEPHLA UNI.

ITEIRE-CHUKWUSA MARY ADA

VEPH/50B/AI062

 

  Task 24

DATE- 24/09/2026

  

## **Description**

This project focuses on Exploratory Data Analysis (EDA) using Python and Pandas. The resource uses a roller coaster dataset to demonstrate how data can be imported, inspected, cleaned, explored, visualized, and analyzed to identify patterns and relationships.

The project begins by importing the dataset into a Python working environment and examining its structure. The data is then prepared by removing unwanted columns, correcting data types, renaming columns, checking for missing values, and identifying and removing duplicate records.

After the cleaning process, different EDA techniques are used to understand the dataset. These include univariate analysis, data visualization, bivariate analysis, correlation analysis, heatmaps, and location-based analysis.

The main goal of the project is to develop practical skills in working with a dataset and using Python to obtain meaningful information from it.

## **Topics and Techniques Explored**

The following topics and techniques were covered in the resource:

### 1\. Python Libraries

The project uses:

* Pandas – for data manipulation and analysis.  
* NumPy – for numerical operations.  
* Matplotlib – for data visualization.  
* Seaborn – for statistical visualization.

### 2\. Dataset Exploration

The dataset was initially explored using commands such as:

* head()  
* shape  
* columns  
* dtypes  
* describe()

These commands helped in understanding the number of rows and columns, column names, data types, and basic statistical information.

### 3\. Data Preparation and Cleaning

The project explored:

* Removing unwanted columns.  
* Changing incorrect data types.  
* Converting date values to datetime.  
* Converting values to numeric data.  
* Renaming columns.  
* Checking for missing/null values.  
* Identifying duplicate records.  
* Removing duplicates.  
* Resetting the dataframe index.

### 4\. Univariate Analysis

Univariate analysis was performed by examining one variable at a time.

For example, the Year\_Introduced column was analyzed using value\_counts() to determine how frequently roller coasters were introduced in different years.

### 5\. Data Visualization

Different visualization techniques were used, including:

* Bar charts  
* Histograms  
* KDE plots  
* Scatter plots  
* Horizontal bar charts  
* Heatmaps

These visualizations made it easier to identify patterns and understand the data.

### 6\. Bivariate Analysis

The project examined relationships between two variables, particularly:

* Speed and height  
* Speed and height based on year introduced  
* Speed and height based on roller coaster type

Seaborn's hue feature was used to add another variable to the scatter plots.

### 7\. Correlation Analysis

Correlation was calculated between selected numerical variables:

* Year\_Introduced  
* speed\_mph  
* height\_ft  
* Inversions  
* G-force

A Seaborn heatmap was then used to display the correlation values visually.

### 8\. Location Analysis

The project also analyzed roller coaster speed by location.

Locations labelled "Other" were excluded, and only locations with at least 10 records were included. The average coaster speed for each location was calculated and displayed using a horizontal bar chart.

## **Repository Structure and Navigation**

The repository contains the Jupyter Notebook used for the analysis.

A simple way to understand the project is to follow the notebook from top to bottom:

TASK 24 LAB/  
│  
├── TASK 24 LAB.ipynb  
└── README.md

### TASK 24 LAB.ipynb

This is the main project file. It contains the Python code, explanations, data preparation steps, analysis, and visualizations.

The notebook can be followed in this order:

1. Import Python libraries.  
2. Load the roller coaster dataset.  
3. Explore the dataset.  
4. Prepare and clean the data.  
5. Check missing values.  
6. Check and remove duplicates.  
7. Perform univariate analysis.  
8. Create visualizations.  
9. Perform bivariate analysis.  
10. Calculate correlations.  
11. Create a correlation heatmap.  
12. Perform location-based analysis.  
13. Draw observations from the data.

### **README.md**

This file provides an overview of the project, explains the techniques used, and helps users understand how to navigate the repository.

## **Key Takeaways**

The major lessons learned from this resource include:

* A dataset should be properly inspected before analysis.  
* Understanding the structure and data types of a dataset is important before cleaning it.  
* Unwanted columns and duplicate records should be identified and handled during data preparation.  
* Missing values can be checked using Pandas functions such as isna() and isna().sum().  
* duplicated() can be used to identify duplicate records.  
* Different visualizations provide different ways of understanding data.  
* Univariate analysis helps examine individual variables.  
* Scatter plots can help examine relationships between variables.  
* Correlation analysis helps examine relationships between numerical variables.  
* A heatmap provides a visual representation of correlation values.  
* Grouping data by location and calculating averages can help answer specific questions about the dataset.  
* EDA is not only about creating graphs; it also involves asking questions and finding patterns in the data.

## 

## **Conclusion**

This resource provided practical experience in performing Exploratory Data Analysis with Python. By working with the roller coaster dataset, the project demonstrated the complete process from importing and cleaning data to analyzing relationships and creating visualizations.

The overall workflow followed in the project can be summarized as:

Load → Inspect → Prepare → Clean → Explore → Visualize → Analyze Relationships → Ask Questions → Draw Insights.

