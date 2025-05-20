# 🔁 Global Socio-Economic Comparison – Case Study

This repository presents a comprehensive data analysis project focused on analyzing and comparing various countries across regions in terms of their population, development indicators, economic structure, and infrastructure availability.

## 📂 Files in This Repository

* `GDP Case Study.docx`: Detailed case study with project objectives, goals, and analysis questions.
* 'Healthcare Data.csv': The dataset containing details of countries.

## 🎯 Objective

The primary goal is to build a dynamic dashboard that enables users to explore and compare various countries across regions in terms of their population, development indicators, economic structure, and infrastructure availability using a visual, filterable format. 

## 🧰 Tools & Technologies Used

* Microsoft Power BI / Tableau / Google Data Studio for dashboard creation 
* Python for data cleaning and preparation
* Manual rules-based filters and calculated fields for categorization and derived metrics 

## 🔍 Dataset Overview

The dataset contains information on multiple countries and includes the following categories: 

* **Demographics**: Population, Population Density, Birthrate, Deathrate, Net Migration 
* **Economic Indicators**: GDP per Capita, Employment Sectors (Agriculture, Industry, Services)
* **Health and Education**: Infant Mortality, Literacy Rate
* **Infrastructure**: Phones per 1000 people, Arable land, Crop and Other land usage 
* **Geography**: Area, Region, Coastline to area ratio 
* **Climate Category**: Simplified climate type (1–4) 

## 🧪 Key Analysis Performed (based on document questions)

The project involves a thorough analysis across several dimensions to provide comprehensive insights:

1.  **Data Quality and Structure Assessment**: Initial steps involve understanding the dataset's composition by identifying column names, row and column counts, data types, and handling missing values. This also includes distinguishing between numeric and categorical attributes and identifying potential outliers or duplicate entries. 
2.  **Geographic and Demographic Profiling**: This segment focuses on creating regional profiles, including the number of unique regions, countries within each region, and regional aggregates for total population and land area. It also delves into population distribution and density across countries, identifying areas of high population with low density or similar populations with varied densities. 
3.  **Vital Statistics Analysis**: Examination of birth rates, death rates, and net migration rates to highlight countries with the highest/lowest values and identify instances of negative net migration. 
4.  **Economic Structure and Development**: Analysis of GDP per capita ranges, identifying the highest and lowest GDP countries. It includes understanding the predominant employment sectors (agriculture, industry, services) to illustrate development focus and identify countries with high GDP but low infrastructure (e.g., phone density) or high literacy but low GDP. 
5.  **Health and Education Indicators**: Assessment of infant mortality and literacy rates, identifying countries with high infant mortality and low literacy, or those that exhibit high literacy despite low GDP. Regional literacy rates are also examined. 
6.  **Infrastructure and Connectivity**: Evaluation of phone penetration per 1000 people to identify countries with high or very low connectivity, and to explore its relationship with GDP. 
7.  **Land Use and Climate Impact**: Analysis of arable land percentages across countries, including those with zero arable land. This also involves categorizing countries by simplified climate types (1-4) and investigating potential correlations between arable land and birth rates. 

## 📊 Sample Analysis Questions Answered

* What is the overall range of GDP per capita across countries? 
* Which countries primarily rely on agriculture versus service-oriented economies? 
* Are there countries that demonstrate high literacy rates despite having a low GDP?
* Is there a discernible relationship between phone penetration and a country's GDP? 
* Do countries with a higher percentage of arable land tend to exhibit higher birthrates? 

## 🚀 Future Scope

* Add temporal trendlines if time-series data is added.
* Allow scenario analysis (e.g., if GDP increases 10%, how might infrastructure indicators change).
* Incorporate qualitative tags such as "Tourist-heavy", "Oil-based economy", "Post-conflict recovery".

## 🧾 License

This project is for educational and analytical purposes. The dataset is publicly available, and any insights or results are independently derived.
