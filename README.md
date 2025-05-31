# 🛍️ Shopping Mall Customer Segmentation Analysis

A comprehensive customer segmentation project using K-Means clustering to analyze shopping patterns and customer behavior in a mall dataset. This project demonstrates the application of unsupervised machine learning techniques to identify distinct customer groups for targeted marketing strategies.

## 📊 Project Overview

This project performs customer segmentation analysis on mall customer data to help businesses understand their customer base better and develop targeted marketing strategies. By analyzing customer demographics and spending patterns, we identify distinct customer segments using K-Means clustering algorithm.

## 🎯 Objectives

- **Analyze customer demographics** and spending patterns
- **Identify distinct customer segments** using clustering techniques
- **Provide actionable insights** for marketing strategies
- **Visualize customer behavior** through comprehensive data analysis

## 📁 Dataset

The project uses the **Mall Customers Dataset** containing 200 customer records with the following features:

| Feature | Description |
|---------|-------------|
| CustomerID | Unique identifier for each customer |
| Gender | Customer gender (Male/Female) |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousands of dollars |
| Spending Score (1-100) | Score assigned based on customer behavior and spending patterns |

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning algorithms
- **Jupyter Notebook** - Interactive development environment

## 📈 Analysis Workflow

### 1. **Exploratory Data Analysis (EDA)**
- Data loading and initial exploration
- Statistical summary and data distribution analysis
- Gender-based demographic analysis
- Correlation analysis between features

### 2. **Data Visualization**
- Distribution plots for age, income, and spending scores
- Gender-based spending pattern analysis
- Correlation heatmaps
- Comprehensive statistical visualizations

### 3. **Customer Segmentation**

#### **Income-Based Clustering**
- Applied K-Means clustering on Annual Income
- Identified 3 distinct income groups:
  - **Low Income Group** (Cluster 1)
  - **Medium Income Group** (Cluster 0) 
  - **High Income Group** (Cluster 2)

#### **Comprehensive Segmentation**
- Applied K-Means clustering on both Annual Income and Spending Score
- Identified 5 distinct customer segments:
  - **Cluster 0**: Middle-aged, moderate income, average spending
  - **Cluster 1**: Young, low income, high spending (Potential targets)
  - **Cluster 2**: Young, high income, high spending (Premium customers)
  - **Cluster 3**: Middle-aged, low income, low spending (Price-sensitive)
  - **Cluster 4**: Middle-aged, high income, low spending (Conservative spenders)

### 4. **Advanced Analysis**
- Feature standardization and scaling
- Gender encoding for comprehensive analysis
- Multi-dimensional clustering analysis

## 🎯 Key Insights

### **Customer Segments Identified:**

1. **Premium Customers (Cluster 2)**
   - High income, high spending
   - Target for luxury products and premium services

2. **Potential Targets (Cluster 1)**
   - Low income but high spending
   - Focus on value-for-money products

3. **Conservative Spenders (Cluster 4)**
   - High income but low spending
   - Require engagement strategies to increase spending

4. **Price-Sensitive Customers (Cluster 3)**
   - Low income, low spending
   - Target with discounts and budget-friendly options

5. **Average Customers (Cluster 0)**
   - Moderate income and spending
   - Standard marketing approaches

### **Business Recommendations:**

- **Premium Services** for high-income, high-spending customers
- **Value Propositions** for low-income, high-spending segments
- **Engagement Campaigns** for conservative spenders
- **Discount Strategies** for price-sensitive customers
- **Loyalty Programs** across all segments

## 📊 Visualizations

The project includes comprehensive visualizations:
- Customer distribution by gender and age groups
- Income vs. spending score scatter plots
- Cluster visualization with different colors
- Statistical distribution plots
- Correlation heatmaps

## 🔍 Future Enhancements

- **Advanced Clustering Algorithms**: Implement DBSCAN, Hierarchical clustering
- **Feature Engineering**: Create new features like customer lifetime value
- **Predictive Modeling**: Develop models to predict customer behavior
- **Real-time Segmentation**: Implement dynamic customer segmentation
- **A/B Testing Framework**: Test marketing strategies on different segments

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
