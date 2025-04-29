# Urbanization Trends Analysis

## Project Goal
The aim of this project was to evaluate urbanization trends across 12 countries and income groups over the past 63 years. The focus was on identifying areas where urbanization could lead to infrastructure stress or uneven development. Instead of simply visualizing the growth, critical questions were asked regarding the urban patterns and their potential economic implications.

### Business Context
Insights derived from this analysis can help policymakers, urban planners, and business leaders:
- Identify countries or regions that are rapidly urbanizing and may face future infrastructure stress.
- Highlight disparities in urban growth across different income groups and countries.
- Understand areas with potential for sustainable growth, and where urban planning efforts are most needed.

---

## Data Overview

### Data Source & Structure
- The dataset includes information for **12 countries** and spans over **63 years**.
- The key columns in the dataset include:
  - **Country**: The country under study.
  - **Income Group**: Classification of the country's economy (e.g., High, Upper Middle, Lower Middle income).
  - **Indicator Year**: Year for which the data is recorded.
  - **Indicator Name**: Metrics such as "Urban Growth" and "Population Growth".
  - **Indicator Value**: The values corresponding to the indicators.
  
This data enabled detailed analysis of the urbanization and population growth trends for each country across the years.

---

## Structure of the Report

### Page 1 – Global Overview

1. **KPI Cards:**
   - **Urban Population (2023)**: 368 million
   - **Average Urban Growth Rate**: 0.92%
   - **Urban Growth Adjusted by Population**: 2.00%

2. **Line Chart** – **Urban Population Growth (%) vs Total Population Growth (%)**
   - **Insight**: Urban growth has been consistently higher than total population growth but began aligning more closely after 2005. There were minor surges in urban growth between 2016–2018 and a slight increase post-2020.

3. **Scatter Plot** – **Urban Growth Rate vs Urban Share (2023)**
   - **Insight**: Most countries are in a **moderate urbanization stage** (urban share between 65% and 88%). Countries with **high urbanization and low growth** (like Uruguay and Argentina) are stable, while some nations are still in early stages of urbanization, suggesting a need for urgent infrastructure investment.

4. **Map** – **Urban Population by Country (2023)**
   - **Insight**: Brazil has the highest urban population in the region, reflecting its extensive urbanization.

5. **Slicers:**
   - Filters for **Year**, **Country**, and **Income Group** for interactive analysis.

---

### Page 2 – Income Group Analysis

1. **Column Chart** – **Urban Share by Country, Segmented by Income Group**
   - **Insight**: 
     - **High-income countries**, such as **Uruguay**, have the highest urban share (96%).
     - **Lower-middle-income countries** like **Bolivia** show mid-range urban share, indicating differences even within similar economies.
  
2. **Treemap** – **Urban Growth Rate by Income Group (2023)**
   - **Insight**: 
     - **Lower and Upper Middle Income** groups exhibit **higher urban growth** (~2%).
     - **High Income** countries show lower urban growth (~1%), reflecting already established urban centers.

---

## Recommendations

### 1. **Prioritize Infrastructure in Fast-Growing Urban Areas**
   - **Countries**: Peru, Colombia, Venezuela
   - **Reason**: These countries are experiencing rapid urban population growth. Investing in transportation, housing, and public services will be crucial to avoid future stress on infrastructure.

### 2. **Focus on Early-Stage Urbanization**
   - **Countries**: Bolivia, Paraguay, Ecuador
   - **Reason**: These countries have a lower urban share and are in the early stages of urbanization. Investing in basic infrastructure (e.g., roads, water supply) will help them transition smoothly and support long-term growth.

### 3. **Improve Quality of Life in Already Highly Urbanized Countries**
   - **Countries**: Uruguay, Argentina
   - **Reason**: These countries have a high urban share, and the focus should shift toward enhancing public services, healthcare, and sustainability in urban areas to improve quality of life and prevent congestion.

### 4. **Support Urban Growth in Middle-Income Countries**
   - **Countries**: Bolivia, Guyana, Suriname
   - **Reason**: These countries show an urban growth rate of around 2%. Scalable infrastructure and policy support are needed to manage this growth and ensure the cities are equipped to handle the increased population.

### 5. **Monitor Brazil's Urban Growth**
   - **Country**: Brazil
   - **Reason**: Brazil has the highest urban population in the region. Continued tracking and investment in urban infrastructure will be necessary to accommodate its growing cities and ensure sustainable development.

---

## How to Use This Analysis

This analysis can guide **policymakers**, **urban planners**, and **business leaders** in making informed decisions about:
- **Urban growth** trends and how they vary across countries and income groups.
- **Future infrastructure needs** in countries experiencing rapid urbanization.
- **Opportunities for investment** in emerging urban economies.
  
By using the interactive slicers and visuals in the report, users can analyze **specific trends by year**, **country**, and **income group** to drill down into the data and uncover more tailored insights.

---

## Conclusion

This project provides a detailed understanding of **urbanization trends** and offers actionable insights for **future planning**. The interactive visualizations and calculated fields help uncover important patterns about **urban growth**, **population dynamics**, and **income group disparities**, all of which play a crucial role in shaping **sustainable urban development** strategies.

---

## Technologies Used:
- **Power BI** for data visualization and reporting.
- **Power Query** for data preparation and transformation.
- **DAX** for creating calculated fields and metrics.

---

