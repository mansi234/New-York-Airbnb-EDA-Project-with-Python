# New-York-Airbnb-EDA-Project-with-Python

Exploratory Data Analysis of NYC Airbnb Listings Using Python.

The dataset contains 22 columns and 20,770 rows, providing detailed information about Airbnb listings in New York.

Columns:

neighbourhood_group: Grouping by boroughs like Manhattan, Brooklyn, etc.
room_type: Types of listings (e.g., Entire home/apt, Private room).
price: Listing prices.
minimum_nights: Minimum stay required.
number_of_reviews: Reviews count per listing.
availability_365: Days available in a World.

Data Characteristics:

The average price is $187.71, with some listings reaching up to $100,000.
Most listings have 1-2 beds, with a maximum of 42 beds in a single listing.
The majority of hosts manage a small number of listings, but some manage over 700 listings.

Steps Taken to perform EDA on the project:

1. Understanding the Dataset
Reviewed the dataset structure (e.g., number of rows, columns, and data types).
Identified key columns such as price, neighbourhood_group, room_type, and availability_365.
Assessed the dataset for its scope and potential insights.
2. Data Cleaning
Handled missing(null) values by:
Dropping irrelevant or incomplete rows/columns.
Removed duplicates to ensure data integrity.
Checked for and resolved data inconsistencies (e.g., unrealistic prices or minimum nights).
3. Exploratory Data Analysis
Univariate Analysis:
Analyzed individual columns, such as price and room_type, to understand their distributions.
Identified outliers in pricing and minimum nights.
Bivariate Analysis:
Explored relationships between variables, such as price vs. room_type or neighbourhood_group vs. availability_365.
Geographic Analysis:
Visualized data geographically to understand trends across neighborhoods and boroughs.
4. Data Visualization
Created plots to uncover trends and patterns:
Histograms and box plots for price distribution.
Bar charts for room_type and neighbourhood_group.
Heatmaps for correlation analysis.
Geographic scatter plots to map listing density and pricing.
5. Insights Generation
Summarized key findings:
Most listings are in Manhattan and Brooklyn.
Entire homes/apartments dominate the market.
Prices vary significantly, with outliers indicating luxury properties.
6. Documentation
Documented the process and findings:
Included a README file for the GitHub repository.
Saved visualizations and key outputs for sharing.
Tools and Libraries Used:
Python: For data manipulation and analysis.
Pandas: Data cleaning and preprocessing.
NumPy: Numerical computations.
Matplotlib & Seaborn: Data visualization.
Jupyter Notebook or Google Collab: For interactive coding and presentation.
