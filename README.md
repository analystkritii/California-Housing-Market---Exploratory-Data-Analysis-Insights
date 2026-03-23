*****Project Overview******
->This project performs an in-depth Exploratory Data Analysis (EDA) on the California Housing dataset. The primary goal is to identify the key factors that influence housing prices across various districts in California. By leveraging Python's data science ecosystem, I have cleaned, transformed, and visualized the data to uncover hidden patterns and correlations.

*****Key Features******
1->Data Preprocessing: Handled missing values in the total_bedrooms column using median imputation and ensured data types were optimized for analysis.

2->Statistical Analysis: Conducted descriptive statistics to understand the distribution of variables like median_income, housing_median_age, and population.

3->Geospatial Visualization: Created scatter plots using Latitude and Longitude to visualize the geographic distribution of house prices across California.

4->Correlation Mapping: Utilized Seaborn Heatmaps to determine the relationship between features, identifying median_income as the strongest predictor of house value.

5->Feature Engineering: Engineered new metrics such as rooms_per_household and population_per_household to gain deeper insights into neighborhood density and its impact on pricing.

6->Outlier Detection: Used Boxplots to identify and analyze outliers in the dataset.

*****Tech Stack*****
1->Language: Python

2->Libraries: * Pandas: For data manipulation and cleaning.

3->NumPy: For numerical computations.

4->Matplotlib & Seaborn: For static and interactive data visualizations.

5->Environment: Google Colab / Jupyter Notebook

****Dataset Description******
The dataset contains information from the 1990 California census. It includes 10 attributes:

*longitude / latitude

*housing_median_age

*total_rooms / total_bedrooms

*population

*households

*median_income

*median_house_value

*ocean_proximity

*Insights Derived

*Income Impact: There is a strong positive correlation between median income and house values.

**Location Factor: Houses located "Near Ocean" or "Inland" show significant price variance, with coastal properties generally commanding higher prices.

**Density: Areas with higher rooms_per_household tend to have higher median values.
