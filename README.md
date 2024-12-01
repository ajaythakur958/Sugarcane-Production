# Sugarcane-Production


This repository contains a Jupyter Notebook that performs an analysis of sugarcane production data using python and popular data analysis libraries such as Pandas, Seaborn and Matplotlib. 
The dataset used in this analysis is names as List of Countries by Sugarcane Production.csv


## Dataset

This dataset contains information about Sugarcane Production in various countries.

- `Country`: The name of the country.
- `Continent`: The continent where the country is located.
- `Production(Tons)`: Total sugarcane production in tons.
- `Production_per_person(Kg)`: Sugarcane production per person in kilograms.
- `Acreage(Hectare)`: Total acreage of land used for sugarcane cultivation in hectares.
- `Yield(Kg/Hectare)`: Yield of sugarcane in kilograms per hectare.


## Data Cleaning

The initial data cleaning step includes removing unwanted character like ( eg. commas, dot) from numeric column and also dropping unnecessary columns.


## Univariate analysis

Univariate analysis examines each column individually. It also includes visualizations such as bar plots and distribution plots to understand the data distribution and identify outliers.

![Screenshot 2024-12-01 152400](https://github.com/user-attachments/assets/20fd3945-b129-4af5-96e3-dd20fc853322)

![Screenshot 2024-12-01 152326](https://github.com/user-attachments/assets/d395880f-2513-45ce-b298-7c1a1427c0e6)


## Bivariate Analysis

Bivariate analysis explores the relationship between two variables, such as total sugarcane production vs. acreage per hectare and total sugarcane production vs. yield per hectare. Scatter plots and bar plots are used to visualize these relationships.

![image](https://github.com/user-attachments/assets/f5ab55cb-11ee-4a0b-ab56-d5f5465567fe)


## Correlation Analysis

The Correlation analysis explores the relationship between numerical variables. A heatmap is used to identify the correlation matrix 

![Screenshot 2024-12-01 185239](https://github.com/user-attachments/assets/ed58a1b6-4815-4638-8df9-08b6e3759107)


## Conclusion

This analysis provides insights into sugarcane production across various countries and continents. It highlights the relationships between key factors, such as production by each country, acreage, and yield.



