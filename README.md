# Customer Segmentation with KMeans, Pipelines, and Elbow Method

This project applies KMeans clustering to segment customers based on their annual income and spending score, using scikit-learn pipelines for preprocessing and clustering. The elbow method is implemented to determine the optimal number of clusters, and Bokeh is used to create interactive visualizations.

---

##  Dataset Source

- **Source**: [Kaggle - Bike Buyers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?resource=download) 
- The dataset includes the following fields:
  - CustomerID, Gender, Age, Annual Income, Spending Score

---

##  Key Steps

- **Data Selection**
  - Selected relevant numerical features (age, annual_income, spending_score).
- **Preprocessing**
  - Applied StandardScaler via a ColumnTransformer to standardize numerical data.
- **Pipeline Construction**
  - Combined preprocessing and KMeans clustering into a single scikit-learn Pipeline.
- **Optimal Cluster Search**
  - Used the elbow method to determine the best number of clusters based on inertia values.
 - **Model Fitting & Prediction**
  - Assigned customers to clusters and stored results in the original dataset.
- **Visualization**
  - Elbow curve showing inertia vs. k
 
  ![Elbow Screenshot](/image/Elbow.png)
  
  - Customer segments scatter plot (Annual Income vs Spending Score) using Bokeh for interactivity.
 
  ![Segment Screenshot](/image/Customer_Segment.png)  

## Tools & Libraries:

- Python (pandas, numpy)

- scikit-learn (Pipeline, ColumnTransformer, KMeans, StandardScaler)

- Bokeh (interactive plots)

- Matplotlib & Seaborn (static visualizations)

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
