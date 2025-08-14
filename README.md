# Customer Segmentation with KMeans, Pipelines, and Elbow Method

This project applies KMeans clustering to segment customers based on their annual income and spending score, using scikit-learn pipelines for preprocessing and clustering. The elbow method is implemented to determine the optimal number of clusters, and Bokeh is used to create interactive visualizations.

---

##  Dataset Overview

- **Source**: [Kaggle - Bike Buyers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?resource=download) 
- The dataset includes the following fields:
  - CustomerID, Gender, Age, Annual Income, Spending Score

---

##  Key Steps

- **Data Selection**
  - Selected relevant numerical features (age, annual_income, spending_score).
  - Data Transformation:
    - Converted `Income` to Number format
    - Created custom columns:
      - **Age Brackets** using nested `IF` statements
      - **Commute Distance Ranges** using logical formulas
  - PivotTables & Slicers for interactive filtering
  - Charts for data visualization

---

##  Business Questions Answered

1. **What is the average income of people who purchased vs. did not purchase a bike?**  
   → Bike buyers had higher average incomes. Among them, **men had an average income of $60,124**.

2. **How many people who purchased a bike commute less than 1 mile to work?**  
   → **20%** of those who purchased a bike had a **0–1 mile** commute to work.

3. **What is the age distribution of bike buyers?**  
   → Around **40%** of bike buyers fall within the **30–54 age range**.

---

##  Dashboard

An interactive Excel dashboard was built using:
- PivotTables
- Slicers to filter data dynamically

![Dashboard Screenshot](Bike_Sales-Dashboard.png)  


---

##  How to View the Project

1. Clone or download this repository
2. Open the `Bike_Sales_Analysis.xlsx` file in Microsoft Excel
3. Explore the "Dashboard" tab to interact with slicers and visualizations

---

##  Key Takeaways

- Gained hands-on experience cleaning and transforming real-world data in Excel
- Strengthened logic-building skills using nested `IF` formulas
- Learned to create dashboards for storytelling and insights
- Answered real business questions with data-backed insights

---

##  Project Status

 Completed  
 Excel file and visuals uploaded  
 Ready for portfolio and sharing

---

##  Let's Connect

If you have feedback or similar projects to share, I’d love to connect!  
📧 LinkedIn: www.linkedin.com/in/yasminabarkouch
