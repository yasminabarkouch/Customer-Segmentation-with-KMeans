# Customer Segmentation with KMeans, Pipelines, and Elbow Method

This project applies KMeans clustering to segment customers based on their annual income and spending score, using scikit-learn pipelines for preprocessing and clustering. The elbow method is implemented to determine the optimal number of clusters, and Bokeh is used to create interactive visualizations.

---

##  Dataset Source

- **Source**: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?resource=download) 
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
  - Descriptive Analysis
    - Mean of Age, Annual Income, and Spending Score by Gender.
      
      ![Mean Screenshot](/image/Mean_by_Gender.png)
    - Male and Female Distribution
      
      ![Male Female Screenshot](/image/Male_Female_Distribution.png)
      
    - Age and Annual Income Frequencies
    - 
      ![Age Income Screenshot](/image/Age_Income_Frequencies.png)
      
  - Elbow curve showing inertia vs. k
 
  ![Elbow Screenshot](/image/Elbow.png)
  
  - Customer segments scatter plot (Annual Income vs Spending Score) using Bokeh for interactivity.
 
  ![Segment Screenshot](/image/Customer_Segment.png)
## Tools & Libraries:

- Python (pandas, numpy)

- scikit-learn (Pipeline, ColumnTransformer, KMeans, StandardScaler)

- Matplotlib, Seaborn, and Bokeh (Visualizations)

- (static visualizations)

##  Insights:

- Found 5 customer groups based on income and spending habits.

- Identified a high-income customer group with low spending scores, highlighting a potential for targeted engagement.


