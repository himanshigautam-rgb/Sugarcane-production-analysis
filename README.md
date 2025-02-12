# Sugarcane Production Analysis
This repository contains a Jupyter Notebook that performs an analysis of sugarcane production data using Python and popular data analysis libraries such as Pandas, Seaborn, and Matplotlib. The dataset used in this analysis is named "List of Countries by Sugarcane Production.csv."
## Dataset  

This dataset provides insights into sugarcane production across various countries. It includes the following key columns:  

- Country: Name of the country.  
- Continent: The continent where the country is located.  
- Production (Tons): Total sugarcane production measured in tons.  
- Production per Person (Kg): Sugarcane production per capita in kilograms.  
- Acreage (Hectare): Total land area allocated for sugarcane cultivation in hectares.  
- Yield (Kg/Hectare): The yield of sugarcane per hectare in kilograms.  

## Data Cleaning  

The initial data preprocessing involved removing unnecessary characters (such as commas and dots) from numerical columns and dropping any irrelevant fields. While some warnings appeared during the cleaning process, they do not significantly impact the analysis.  

## Univariate Analysis  

Univariate analysis focuses on examining individual columns separately. Various visualizations, including bar charts and distribution plots, are utilized to explore data patterns, detect anomalies, and highlight any extreme values.  

## Bivariate Analysis  

Bivariate analysis investigates the relationships between two different variables. For example, the relationship between land area and total production, as well as yield per hectare and total production, is analyzed using scatterplots and bar charts to reveal meaningful trends.  

## Correlation Analysis  

The correlation analysis evaluates how numerical variables interact with each other. A heatmap is used to display the correlation matrix, helping to identify strong positive or negative correlations between different factors.  

## Analysis by Continent  

This section examines sugarcane production trends at the continental level, offering a broader perspective on how production, yield, and land usage vary across different regions. Visualizations such as bar graphs and line plots help compare these differences effectively.  

## Conclusion  

This study provides valuable insights into global sugarcane production, highlighting key patterns and relationships between production-related metrics. By analyzing both country-level and continent-level trends, it uncovers useful findings that can inform agricultural strategies and decision-making.  

For further details, please refer to the Jupyter Notebook available in this repository.  
