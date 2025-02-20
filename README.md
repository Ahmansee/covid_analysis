# covid_analysis
This project shows higher vaccination rates lower death rates, emphasizing the need for targeted efforts and booster doses for vulnerable groups.

## Purpose of Analysis:
The purpose of your analysis is to explore the relationship between COVID-19 vaccination rates and COVID-19 death rates by examining two datasets. My aim is to assess vaccine effectiveness by determining whether higher vaccination rates correlate with lower death rates, identify trends and patterns over time, and conduct geographical comparisons to understand how different regions are impacted. Additionally, I seek to gain demographic insights to identify vulnerable populations, evaluate the impact of vaccination campaigns and public health policies, and potentially develop predictive models to forecast future death rates based on vaccination trends. Ultimately, my analysis aims to inform public health strategies, enhance communication about the importance of vaccination, and contribute to efforts to reduce COVID-19 mortality and improve pandemic response.

## Data Sources:
Data Source: Kaggle
- <a href="https://github.com/Ahmansee/covid_analysis/blob/main/CovidDeaths%20(1).xlsx">Dataset</a>


## Questions for more insight:
1. Is there a statistically significant correlation between vaccination rates and reduced COVID-19 death rates?  
2. Are there specific regions or countries where vaccination rates have had a more pronounced impact on reducing deaths?   
3. Are certain demographic groups more vulnerable to COVID-19 deaths despite vaccination efforts?  
4. How do death rates change as vaccination rates increase over time?  
5. How do new COVID-19 variants affect the relationship between vaccination and death rates?  
6. Are vaccinated populations still experiencing high death rates due to variants, and if so, why?  
7. What is the long-term impact of vaccination on COVID-19 mortality rates?  
8. How might future vaccination strategies need to adapt to sustain low death rates?

## Analysis Methodology,Data Cleaning & Transformation:
1. Imported datasets on COVID-19 vaccination rates and death rates into Power BI  
2. Included additional data such as demographic information, geographic boundaries, and variant prevalence for a comprehensive analysis.  
3. Used drill-through features to explore detailed insights for specific demographic groups.  
4. Used Power Query to handle missing values (e.g., imputed averages or removed incomplete records).  
5. Removed duplicates and standardized data formats (e.g., consistent date formats, region names).  
6. Merged vaccination and death rate datasets using common keys (e.g., date, region) in Power Query.  
7. Aligned time periods and geographic boundaries across datasets to ensure consistency.  
8. Created interactive visualizations to explore trends and correlations between vaccination rates and death rates.  
9. Used slicers and filters to dynamically analyze data by region, time period, and demographic groups.  
10. Built calculated measures (e.g., correlation coefficients, rolling averages) using DAX (Data Analysis Expressions) to quantify the relationship between vaccination and death rates.    
11. Created segmented visualizations (e.g., stacked bar charts, pie charts) to compare vaccination coverage and death rates across age groups, genders, and socioeconomic statuses.  
  
## Results:
1. Higher vaccination rates were strongly correlated with lower COVID-19 death rates.  
2. Regions with faster and more widespread vaccination campaigns saw significant declines in mortality.  
3. Older adults and individuals with underlying health conditions remained at higher risk of severe outcomes and death, even in highly vaccinated populations.  
4. Vaccinated populations still had significantly lower death rates compared to unvaccinated groups during variant surges.  
5. Death rates decreased steadily as vaccination rates increased, with the most significant declines observed in the months following widespread vaccination efforts.  
 
## Conclusion:
The analysis demonstrated that vaccination is a critical tool in reducing COVID-19 death rates, but its effectiveness depends on factors such as public health policies, and demographic vulnerabilities. The findings underscore the need for targeted vaccination campaigns, booster doses, and integrated public health strategies to sustain low death rates and address emerging challenges like new variants. The use of Power BI enabled clear, interactive, and actionable insights for stakeholders.
