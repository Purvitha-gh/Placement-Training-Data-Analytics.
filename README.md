# Placement-Training-Data-Analytics.
1. Project Overview
This project analyzes book-related data using Python for preprocessing and statistical analysis, Microsoft Excel for raw data storage, and Power BI for interactive visualization.
It aims to provide insights into book ratings, trends, and patterns, helping identify popular books and explore relationships between various features.

2. Files in the Project
a) goodbooks final.ipynb (Python Notebook)
Purpose: Data cleaning, exploration, and initial analysis.

Key Tasks Performed:

Data Import & Inspection:

Loaded raw data from Excel (books.csv.xlsx).

Checked dataset shape, column names, and data types.

Data Cleaning:

Removed/handled missing values.

Renamed columns for clarity.

Converted data types where needed.

Exploratory Data Analysis (EDA):

Descriptive statistics (mean, median, mode, etc.).

Value counts and frequency distribution for categorical features.

Grouped data using groupby() to calculate aggregated metrics (e.g., average ratings per book).

Correlation matrix creation to study relationships.

Visualization:

Histograms, scatter plots, and box plots for rating distribution and outlier detection.

Heatmaps for correlation visualization.

b) books.csv.xlsx (Excel Dataset)
Content: Raw tabular dataset with 14 rows × 2 columns.

Columns:

Unnamed: 0: Appears to represent a label or ID field (may require renaming).

Unnamed: 1: Contains numeric or categorical values related to books (ratings, counts, or categories).

Notes:

Contains "Row Labels" entry, indicating it may have originated from a pivot table export.

Some duplication of values, with counts aggregated for certain categories.

Cleaning steps in Python handled blank or inconsistent fields.

c) goodbooks.pbit (Power BI Template)
Purpose: Interactive dashboard for insights and storytelling.

Features:

Data Connection:

Imports cleaned data from Python processing or directly from Excel.

Key Visuals:

Top-rated books chart.

Distribution of ratings across genres/authors.

Trend lines showing rating changes over time.

Interactivity:

Slicers for filtering by category, rating, or author.

Drill-through capability for detailed book views.

Calculated Measures:

Average rating (DAX measure).

Count of reviews.

Popularity index.

3. Workflow
Data Source: Books dataset (books.csv.xlsx) with raw book information.

Data Cleaning & Analysis (Python):

Imported dataset into goodbooks final.ipynb.

Cleaned and transformed the data.

Conducted initial statistical and visual analysis.

Visualization (Power BI):

Loaded cleaned dataset.

Created interactive dashboards to explore trends and insights.

Output:

Python notebook with code & static plots.

Power BI dashboard for dynamic exploration.

4. Insights Gained
Identification of most popular and highest-rated books.

Detection of outliers in rating distributions.

Correlation patterns between book attributes.

Trends in book ratings over time or by category.
