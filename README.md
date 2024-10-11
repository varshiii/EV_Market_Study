# AtliQ Motors - Electric Vehicle Market Study in India

## Overview
AtliQ Motors, a leading automotive manufacturer from the USA, specializing in electric vehicles (EVs), is exploring the Indian market as part of its global expansion strategy. Over the past five years, the company has secured a 25% market share in the North American EV and hybrid vehicle segment. However, in India, their market share remains below 2%. To boost their presence, Bruce Haryali, the Chief of AtliQ Motors India, has tasked the data analytics team with conducting a comprehensive study of the EV and hybrid market in India. This project entails a detailed analysis of electric vehicle sales trends across various states in India, along with insights into major manufacturers' contributions and the overall state of the market.

## Project Features

### 1. Data Import and Exploration
- Loaded multiple datasets to understand the EV market in India.
- Performed an initial data exploration to examine the structure of the datasets, including the columns, data types, and ranges of key metrics.

### 2. Data Cleaning
- Filtered out irrelevant or duplicated data to focus on useful information for analysis.

### 3. Data Transformation
- Merged and transformed datasets to facilitate deeper analysis.
- Created new features like calculating the EV penetration rates for each maker.

### 4. Insights Generation
- Analyzed key metrics such as EV booking trends, revenue growth for 2-wheelers and 4-wheelers, and penetration rates across states.
- Identified key states with high EV adoption and major manufacturers contributing to the growth of electric vehicle sales.

## Tools and Libraries
- **Pandas**: For efficient data manipulation and transformation.
- **Matplotlib**: To create visualizations that help better understand sales trends.
- **Seaborn**: For enhanced visualizations with statistical plots.
- **GeoPandas**: For analyzing geographical data and visualizing state-wise sales patterns.
- **Jupyter Notebook**: Used for interactive exploration, visualization, and analysis.

## Datasets Used

### 1. `electric_vehicle_sales_by_state.csv`
| Column Name            | Description                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------|
| `date`                 | The date on which the data was recorded (Format: DD-MMM-YY).                                      |
| `state`                | The name of the state where the sales data is recorded.                                           |
| `vehicle_category`      | Specifies whether it is a 2-Wheeler or a 4-Wheeler.                                              |
| `electric_vehicles_sold`| The number of electric vehicles sold in the specified state and category on the given date.       |
| `total_vehicles_sold`   | The total number of vehicles (including both electric and non-electric) sold on the given date.   |

### 2. `electric_vehicle_sales_by_makers.csv`
| Column Name              | Description                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------------|
| `date`                   | The date on which the sales data was recorded (Format: DD-MMM-YY).                                |
| `vehicle_category`        | Specifies whether it is a 2-Wheeler or a 4-Wheeler.                                              |
| `maker`                  | The name of the electric vehicle manufacturer.                                                   |
| `electric_vehicles_sold`  | The number of electric vehicles sold by the specified maker in the given category on the given date.|

### 3. `dim_date.csv`
| Column Name  | Description                                                                                   |
|--------------|-------------------------------------------------------------------------------------------------|
| `date`       | The specific date for which the data is relevant (Format: DD-MMM-YY).                           |
| `fiscal_year`| The fiscal year to which the date belongs (for financial and business analysis).                |
| `quarter`    | The fiscal quarter (Q1, Q2, Q3, or Q4) corresponding to the date.                               |

## Analysis Overview

### 1. **Market Trends Analysis**
   - Explored EV sales by state from 2022 to 2024.
   - Identified peak and low seasons for EV sales in India.
   - Conducted a comparative analysis of 2-Wheelers vs. 4-Wheelers.

### 2. **Revenue Growth Estimation**
   - Estimated revenue growth rate for 2-wheelers and 4-wheelers using average prices and sales data.

### 3. **CAGR (Compound Annual Growth Rate) Calculation**
   - Calculated CAGR for electric vehicles sold in various states.
   
### 4. **State-Wise EV Sales Penetration**
   - Visualized EV sales penetration across different states using GeoPandas.
   - Examined the market share of electric vehicles in relation to total vehicles sold.

### 5. **Manufacturer Analysis**
   - Identified top EV manufacturers in India and their contribution to overall sales.
   - Examined manufacturer trends in both 2-Wheeler and 4-Wheeler categories.

## Visualizations
- **State-wise EV Sales**: Displaying EV sales distribution across Indian states using a geographical map (GeoPandas).
- **Monthly Sales Trend**: A time series visualization to showcase sales trends over time.
- **2-Wheeler vs. 4-Wheeler Sales**: Comparative analysis of sales growth between 2-wheelers and 4-wheelers.

## Key Insights
- **Peak and Low Season**: Identified peak and low sales months based on EV sales data from 2022 to 2024.
- **Revenue Growth**: 2-Wheelers had a higher revenue growth rate compared to 4-Wheelers in 2022-2024.
- **State-Wise Adoption**: States like Karnataka and Delhi showed higher EV penetration rates compared to others.
- **Manufacturer Dominance**: A few manufacturers such as OLA Electric have dominated the 2-Wheeler segment, while other players like Tata Motors lead in 4-Wheeler EVs.

## Conclusion
This project provides a comprehensive analysis of the electric vehicle market in India, offering insights into sales trends, revenue growth, and market penetration. AtliQ Motors can use these insights to make informed decisions about their market expansion in India.
