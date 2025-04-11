# Mall Customer Segmentation Analysis

## Project Overview
This data science project focuses on customer segmentation for a mall using machine learning techniques. The analysis helps businesses understand their customer base by grouping them based on their spending patterns, annual income, and other behavioral characteristics.

## Dataset Description
The dataset (`Mall_Customers.csv`) contains the following features:
- CustomerID: Unique identifier for each customer
- Gender: Customer's gender (Male/Female)
- Age: Customer's age
- Annual Income (k$): Customer's annual income in thousands of dollars
- Spending Score (1-100): Score assigned based on customer's spending behavior and purchasing power

## Technical Stack
- Python 3.x
- Key Libraries:
  - pandas: Data manipulation and analysis
  - numpy: Numerical computations
  - scikit-learn: Machine learning algorithms
  - matplotlib & seaborn: Data visualization
  - scipy: Scientific computations

## Methodology
1. **Data Preprocessing**
   - Data cleaning and validation
   - Feature scaling using StandardScaler
   - Exploratory Data Analysis (EDA)

2. **Customer Segmentation**
   - K-means clustering algorithm
   - Optimal cluster selection using:
     - Elbow Method
     - Silhouette Analysis
   - Final model with 5 distinct customer segments

3. **Analysis Results**
The analysis revealed 5 distinct customer segments:
   - Average income and spending (middle cluster)
   - High income, high spenders (upper right)
   - Low income, high spenders (upper left)
   - High income, low spenders (lower right)
   - Low income, low spenders (lower left)

## Key Findings
- Optimal number of clusters (k=5) determined through both Elbow Method and Silhouette Analysis
- Highest silhouette score of 0.555 achieved with 5 clusters
- Clear separation between customer segments based on income and spending patterns

## Business Applications
This segmentation can be used for:
- Targeted marketing strategies
- Personalized customer service
- Inventory management
- Store layout optimization
- Promotional campaign planning

## Future Improvements
- Include more customer attributes for segmentation
- Implement other clustering algorithms (DBSCAN, Hierarchical Clustering)
- Add time-series analysis for customer behavior changes
- Develop a web interface for interactive visualization

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
