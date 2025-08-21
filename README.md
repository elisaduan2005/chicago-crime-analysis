# Chicago Crime Analysis

## Introduction
This project analyzes the evolving landscape of crime in Chicago, focusing on how crime trends have changed over time, which communities are most affected, and how demographics intersect with victimization. Our aim is to provide insights into safety risks across neighborhoods, identify disparities, and better understand social factors driving these patterns.

## Datasets
We used three datasets:
1. **Violence Reduction – Victim Demographics (1991–Present)**  
   - Covers homicide, battery, robbery, with demographics (age, sex, race) and crime context.  
2. **Crimes – One Year Prior to Present**  
   - Recent crime incidents with location and detailed descriptions.  
3. **Boundaries – Neighborhoods**  
   - Geographic shapefiles for Chicago neighborhoods.  

Together, these datasets enable both long-term trend analysis and recent neighborhood-level crime mapping.

## Key Questions & Findings
1. **Which demographic groups are most affected by violent crime?**  
   - Males are consistently more victimized (≈85–95% across homicide, battery, robbery).  
   - Young adults (ages 20–29) face the highest victimization rates.  
   - Black and Hispanic individuals are disproportionately represented as victims.  

2. **How have violent crimes evolved over time?**  
   - Battery is most common, followed by homicide, then robbery.  
   - Peaks observed in 2016–2017 and 2020–2023, linked to changes in policing and COVID-19 effects.  
   - Over time, crime against younger victims has declined, while incidents among older adults have risen.  

3. **Where and when do crimes occur most?**  
   - Violent crime is slightly higher on weekends and evenings.  
   - Seasonal peaks in summer, dips in winter.  
   - Austin and Englewood are the neighborhoods with the highest crime counts.  

## Tools & Methods
- **Google Colab / Python**: pandas, numpy, scipy, shapely, plotly  
- **Data Cleaning & Merging**: standardized column names, filtered demographics, merged datasets on case numbers  
- **Analysis**: grouped by demographics, time, location; used moving averages to smooth trends  
- **Visualization**: stacked bar charts, line plots, and interactive neighborhood maps  

## Contributors
- **Elisa Duan** – Question 1 (demographics & victimization analysis)  
- **Mariana Prado** – Question 2 (crime evolution & demographics over time)  
- **Chelsea Vital** – Question 3 (geographic & temporal crime patterns)  

## Summary
Chicago crime disproportionately affects young men and minority populations, with neighborhood and socioeconomic factors playing major roles. Trends reveal seasonal and demographic shifts, highlighting both systemic disparities and areas for targeted intervention. Future work may include predictive modeling of crime risk by demographic group and neighborhood-level hotspot analysis.

## Full Report
The complete report, including figures and references, is available here:  
📄 [Full Report (Google Docs)](https://docs.google.com/document/d/17khHzWbn67ck2fNcegpjUeJWRZslBca-vqGxprufHlE/edit?usp=sharing)

---

