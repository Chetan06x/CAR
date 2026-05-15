# CAR# Used Car Analytics Dashboard – README

## Project Overview

The **Used Car Analytics Dashboard** is an interactive Power BI dashboard designed to analyze used car market data. It provides insights into pricing, mileage, fuel type, transmission, ownership, and location-based trends to help users understand vehicle performance and market behavior. 

---

# Dashboard Objectives

The dashboard helps users:

* Analyze used car pricing trends
* Compare fuel type performance
* Understand mileage and KM driven impact
* Evaluate transmission influence on pricing
* Explore city-wise car distribution
* Filter and drill down into car details dynamically

---

# Key Performance Indicators (KPIs)

The dashboard contains the following major KPIs:

| KPI               | Value  |
| ----------------- | ------ |
| Average Price     | 5.33   |
| Total Cars        | 5204   |
| Average KM Driven | 60.35K |
| Average Mileage   | 19.08  |

These KPIs provide a quick overview of the used car dataset. 

---

# Dashboard Visualizations

## 1. Price Distribution

Bar chart displaying the distribution of car prices by car brands/models.

### Purpose

* Identify high-value car brands
* Compare pricing across manufacturers
* Analyze market demand

---

## 2. KM Driven VS Price

Bubble/Scatter chart analyzing the relationship between:

* KM Driven
* Car Price
* Fuel Type

Fuel types included:

* Petrol
* Diesel
* CNG
* LPG

### Purpose

* Understand depreciation trends
* Compare fuel efficiency impact on resale value

---

## 3. Price VS Year

Line chart showing average price trends across manufacturing years.

### Purpose

* Analyze car depreciation over time
* Compare old vs new vehicle pricing

### Key Insight

Newer cars generally maintain higher resale value.

---

## 4. City-Wise Analysis

Horizontal bar chart representing the count of cars by location/city.

### Purpose

* Identify cities with high used car sales
* Compare regional market activity

---

## 5. Transmission Impact

Donut chart visualizing transmission distribution.

Transmission types:

* Manual
* Automatic

### Purpose

* Analyze customer transmission preferences
* Compare market share

---

## 6. Price by Fuel Type

Bar chart showing vehicle count/pricing based on fuel type.

Fuel categories:

* Petrol
* Diesel
* CNG
* LPG

### Purpose

* Understand fuel-based pricing behavior
* Identify popular fuel types

---

# Filters & Slicers

The dashboard includes dynamic slicers for:

* Fuel Type
* Transmission
* Owner Type
* Location
* Year Range

These filters allow users to interactively explore the dataset.

---

# Dashboard Design

## Theme

The dashboard uses a modern automotive-inspired theme with:

* Dark navy background
* Orange highlight colors
* Car images and automotive visuals
* Rounded KPI cards

## UI Features

* Interactive visuals
* Responsive layout
* Professional automotive design
* User-friendly filtering system

---

# Tools & Technologies Used

* Power BI Desktop
* DAX Measures
* Power Query
* Data Modeling
* Interactive Charts & Slicers

---

# Suggested DAX Measures

## Total Cars

```DAX
Total Cars = COUNT(Car[Car_ID])
```

## Average Price

```DAX
Avg Price = AVERAGE(Car[Price])
```

## Average KM Driven

```DAX
Avg KM Driven = AVERAGE(Car[KM_Driven])
```

## Average Mileage

```DAX
Avg Mileage = AVERAGE(Car[Mileage])
```

---

# Business Insights

* Petrol and Diesel vehicles dominate the used car market.
* Vehicle prices decrease as manufacturing year becomes older.
* Cars with lower KM driven generally have higher resale value.
* Certain cities contribute significantly to used car sales.
* Manual transmission vehicles appear more common in the dataset.

---

# Future Improvements

Possible dashboard enhancements:

* Add profit/loss analysis
* Include car brand segmentation
* Add predictive resale price forecasting
* Create drill-through detail pages
* Add map visualizations for city analysis
* Implement mobile-friendly layout

---

# Dataset Fields Used

The dashboard analyzes fields such as:

* Car Name
* Price
* Fuel Type
* Transmission
* Owner Type
* Location
* KM Driven
* Mileage
* Manufacturing Year

---

# Conclusion

The **Used Car Analytics Dashboard** is a powerful Power BI project that demonstrates interactive data visualization, KPI monitoring, filtering, and automotive market analysis. It provides meaningful insights into used car trends while maintaining a clean and engaging dashboard design. 
