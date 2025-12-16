# 🏍️ Bike Sales Analysis Dashboard

## 📄 Project Description
This project is a comprehensive **Bike Sales Dashboard** designed to analyze the used two-wheeler market in India. The dashboard evaluates 10,000+ data points to understand pricing trends, depreciation (loss in value), and customer preferences across different states and brands.

## ❓ Business Problem
The used bike market is often unorganized, making it difficult for buyers and sellers to estimate the correct price of a vehicle. Stakeholders struggle to understand:
- **Depreciation:** How much value does a bike lose over time (Original Price vs. Resale Price)?
- **Location Impact:** Does a bike sell for a higher price in a Metro city compared to Tier 3 cities?
- **Brand Reliability:** Which brands hold their value the best?
- **Customer Behavior:** Are people buying more from dealers or individuals?

## 🎯 Dashboard Goal
The goal of this dashboard is to bring transparency to the resale market by providing insights on:
1.  **Price Valuation:** Comparing Original Price vs. Resale Price to calculate the "Loss Percentage."
2.  **Regional Trends:** Identifying which states (e.g., Maharashtra) have the highest demand.
3.  **Inventory Health:** Monitoring insurance status (Active vs. Expired) to assess risk.

## ⚙️ Technical Workflow & Features
This dashboard was built using an end-to-end data analysis process in **Microsoft Excel**:

### 1. Data Cleaning & Preparation
- **Calculated Fields:** Created a new metric for **"Loss %"** by calculating the difference between the *Sum of Price* and *Sum of Resale Price*.
- **Data Standardization:** Grouped cities into **City Tiers (Metro, Tier 1, Tier 2, Tier 3)** for better segmentation.
- **Handling Nulls:** Processed missing values in the "Insurance" and "Owner Type" columns to ensure accurate charts.

### 2. Data Analysis (Pivot Tables)
- Used **Pivot Tables** to aggregate sales data by State, Brand, and Year.
- Analyzed the correlation between **Fuel Efficiency** and **Model Popularity**.
- Created summary statistics to track total inventory volume (10,000 brands/units).

### 3. Interactivity (Slicers)
- Added dynamic **Slicers** to allow users to filter the entire dashboard by:
  - **State:** (e.g., Delhi, Gujarat, Maharashtra)
  - **Brand:** (e.g., Bajaj, Hero, Royal Enfield)
  - **City Tier:** To compare urban vs. rural pricing trends.

## 📊 Key Visuals & Insights
The dashboard includes the following key visualizations:

* **KPI Overview:** Shows a total **Loss of 40.34%**, indicating that, on average, used bikes are sold at ~60% of their original value.
* **State-wise Sales (Line Chart):** **Maharashtra** and **Uttar Pradesh** show the highest volume of bike sales.
* **Price Comparison (Bar Chart):** Compares Average Original Price vs. Resale Price. High-end brands like **Royal Enfield** tend to have higher resale values.
* **Owner Type Distribution (Pie Chart):** The majority of bikes listed are from **First Owners**, which generally command a better price.
* **Insurance Status:** A significant portion of the bikes have **"Expired"** insurance, highlighting a potential cost for new buyers.
* **Year-Wise Trend:** There is a consistent upward trend in bike registrations from **2015 to 2024**, showing a growing market.

## 💡 Recommendations
1.  **Focus on Metro Markets:** Since resale prices are stable in Metro and Tier 1 cities, marketing efforts should focus there.
2.  **Insurance Value Add:** Since many bikes have expired insurance, sellers offering "Renewed Insurance" could sell faster.
3.  **Brand Strategy:** Dealers should stock more **Royal Enfield** and **Yamaha** bikes as they retain higher value compared to other brands.

---
*Created by Sonu Kumar | Data Analyst Aspirant*
