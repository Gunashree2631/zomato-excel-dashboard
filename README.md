# 🍽️ Zomato Restaurants Analysis – Excel Dashboard

## 📊 Project Overview

The **Zomato Restaurants Analysis Dashboard** is an interactive Excel-based data analytics project designed to analyze restaurant information, customer ratings, pricing, cuisines, restaurant openings, and online services.

The project uses **Microsoft Excel** to perform data cleaning, transformation, analysis, visualization, and dashboard development.

The dashboard provides an easy-to-understand view of restaurant trends and helps identify patterns across **cities, cuisines, ratings, pricing categories, and restaurant services**.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze restaurant distribution across different cities and countries.
- Identify the most popular cuisines.
- Analyze restaurant ratings and customer voting patterns.
- Understand different restaurant pricing categories.
- Analyze restaurant openings over time.
- Compare restaurants offering online delivery and table booking.
- Build an interactive Excel dashboard for business insights.
- Present complex restaurant data using easy-to-understand visualizations.

---

## 📁 Dataset

The dataset contains information about restaurants listed on Zomato.

### Dataset Statistics

| Metric | Value |
|---|---:|
| Total Restaurants | **9,551** |
| Unique Restaurant Names | **7,433** |
| Countries | **15** |
| Cities | **141** |
| Unique Cuisine Categories | **1,826** |
| Price Categories | **4** |
| Restaurants with Online Delivery | **2,451** |
| Restaurants with Table Booking | **1,158** |
| Average Restaurant Rating | **2.89** |

---

## 🗂️ Dataset Features

The main dataset contains the following fields:

- `RestaurantID`
- `RestaurantName`
- `CountryCode`
- `City`
- `Address`
- `Locality`
- `LocalityVerbose`
- `Longitude`
- `Latitude`
- `Cuisines`
- `Currency`
- `Has_Table_booking`
- `Has_Online_delivery`
- `Is_delivering_now`
- `Switch_to_order_menu`
- `Price_range`
- `Votes`
- `Average_Cost_for_two`
- `Rating`
- `Datekey_Opening`

---

## 📑 Excel Workbook Structure

The Excel workbook contains multiple sheets used for data preparation and analysis:

### 1. Source Data
Contains the original restaurant dataset used for the analysis.

### 2. Raw Data
Contains transformed and prepared data used for calculations and dashboard analysis.

### 3. Country Codes
Maps country codes to country names.

### 4. Opening Date Key
Contains date-related information such as:

- Year
- Month
- Quarter
- Year-Month
- Weekday
- Financial Month
- Financial Quarter

### 5. Restaurant Count
Used to calculate restaurant-level metrics and support dashboard analysis.

### 6. Restaurant Openings by Date
Analyzes the number of restaurants opened over different time periods.

### 7. Restaurant Count by Rating
Analyzes restaurant distribution according to customer ratings.

### 8. Pricing Category
Categorizes restaurants based on their price range.

### 9. Yes or No
Provides supporting categories for service-related analysis.

### 10. Cuisines
Used for cuisine-level analysis and identifying popular cuisines.

### 11. Main Dashboard
The final interactive dashboard containing charts, KPIs, filters, and visual insights.

---

## 📊 Dashboard Analysis

The dashboard focuses on several important business dimensions.

### 🏙️ Restaurant Distribution

The analysis shows that restaurants are heavily concentrated in major cities.

The top cities include:

- **New Delhi**
- **Gurgaon**
- **Noida**
- Faridabad
- Ghaziabad

New Delhi has the highest number of restaurants in the dataset.

---

### 🍛 Cuisine Analysis

The project analyzes more than **1,800 unique cuisine combinations**.

The most frequently represented cuisines include:

1. **North Indian**
2. **North Indian, Chinese**
3. **Fast Food**
4. **Chinese**
5. **North Indian, Mughlai**
6. **Cafe**
7. **Bakery**
8. **North Indian, Mughlai, Chinese**
9. **Bakery, Desserts**
10. **Street Food**

This analysis helps identify consumer food preferences and cuisine popularity.

---

### ⭐ Restaurant Rating Analysis

Restaurant ratings are analyzed to understand customer satisfaction and restaurant performance.

The dashboard can be used to compare:

- Number of restaurants by rating
- Rating distribution
- Highly rated restaurants
- Lower-rated restaurants
- Relationship between ratings and restaurant characteristics

The overall average rating in the dataset is approximately **2.89**.

---

### 💰 Price Range Analysis

Restaurants are divided into **four price categories**.

The dashboard analyzes restaurant distribution across different price ranges to understand the relationship between:

- Restaurant pricing
- Customer ratings
- Cuisine
- Location
- Restaurant popularity

---

### 🚚 Online Delivery Analysis

The project analyzes restaurants based on online delivery availability.

Out of 9,551 restaurants:

- **2,451 restaurants** offer online delivery.
- The remaining restaurants do not offer online delivery.

This analysis helps understand the adoption of online food delivery services.

---

### 🪑 Table Booking Analysis

The dashboard also evaluates table-booking availability.

- **1,158 restaurants** provide table booking.

This allows comparison between restaurants that provide reservation facilities and those that do not.

---

### 📅 Restaurant Opening Trends

Restaurant opening dates are analyzed using:

- Year
- Month
- Quarter
- Year-Month
- Weekday
- Financial period

This helps identify restaurant growth trends and periods with higher restaurant openings.

---

## 🛠️ Tools & Technologies

### Microsoft Excel

The project primarily uses:

- Excel Tables
- Pivot Tables
- Pivot Charts
- Slicers
- Filters
- Conditional Formatting
- Excel Formulas
- Data Cleaning
- Data Transformation
- Date Analysis
- Dashboard Design

### Data Analysis Techniques

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Aggregation
- Categorization
- Trend Analysis
- Comparative Analysis
- KPI Analysis
- Data Visualization

---

## 📈 Dashboard Features

The interactive dashboard allows users to analyze restaurant data using different dimensions.

### Key Features

- 📌 Restaurant count analysis
- ⭐ Rating analysis
- 🍛 Cuisine analysis
- 💰 Price-range analysis
- 🚚 Online-delivery analysis
- 🪑 Table-booking analysis
- 🏙️ City-wise restaurant analysis
- 📅 Restaurant opening trends
- 🔎 Interactive filtering
- 📊 Pivot-based visualizations

---

## 🔍 Key Insights

Some important findings from the analysis include:

- **New Delhi** has the largest concentration of restaurants in the dataset.
- **North Indian** cuisine is the most frequently represented cuisine.
- North Indian cuisine is often combined with other popular cuisines such as Chinese and Mughlai.
- The dataset contains **9,551 restaurants** across **141 cities**.
- Only a portion of restaurants provide online delivery, with **2,451 restaurants** offering the service.
- **1,158 restaurants** provide table-booking facilities.
- Restaurant pricing is divided into four categories, enabling comparison of affordable and premium restaurants.
- Restaurant ratings provide useful insight into customer satisfaction and restaurant performance.
- Opening-date analysis can be used to identify restaurant growth patterns over time.

---

## 📷 Dashboard Preview

### Main Dashboard

Add your dashboard screenshot here:

```markdown
![Zomato Restaurant Dashboard](images/zomato-dashboard.png)
```

### Cuisine Analysis

```markdown
![Cuisine Analysis](images/cuisine-analysis.png)
```

### Restaurant Rating Analysis

```markdown
![Rating Analysis](images/rating-analysis.png)
```

### Pricing Analysis

```markdown
![Pricing Analysis](images/pricing-analysis.png)
```

---

## 📂 Project Structure

```text
Zomato-Restaurants-Analysis/
│
├── 📊 Zomato Restaurants Analysis.xlsx
│
├── 🖼️ images/
│   ├── zomato-dashboard.png
│   ├── cuisine-analysis.png
│   ├── rating-analysis.png
│   └── pricing-analysis.png
│
└── 📄 README.md
```

---

## 🚀 How to Use

1. Download the Excel workbook.
2. Open the file using **Microsoft Excel**.
3. Navigate to the **Main Dashboard** sheet.
4. Use the available slicers and filters.
5. Select different cities, cuisines, ratings, pricing categories, or services.
6. Explore the charts and KPIs to identify restaurant trends and insights.

---

## 💡 Business Value

This dashboard demonstrates how restaurant data can be transformed into actionable business insights.

It can help restaurant businesses and food-delivery platforms understand:

- Customer preferences
- Cuisine demand
- Pricing patterns
- Restaurant distribution
- Delivery-service adoption
- Customer satisfaction
- Restaurant growth trends

---

## 👨‍💻 Skills Demonstrated

This project demonstrates practical skills in:

**Excel | Data Cleaning | Data Analysis | Pivot Tables | Pivot Charts | Slicers | Dashboard Development | Data Visualization | KPI Analysis | Business Intelligence | Exploratory Data Analysis**

---

## 📌 Conclusion

The **Zomato Restaurants Analysis Dashboard** demonstrates the complete workflow of transforming raw restaurant data into an interactive business intelligence dashboard using Microsoft Excel.

The project provides insights into **restaurant locations, cuisines, ratings, pricing, online delivery, table booking, and restaurant opening trends**, making it a useful portfolio project for **Data Analyst and Business Intelligence roles**.

---

