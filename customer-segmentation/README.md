# Customer Segmentation

Machine learning project that groups customers into segments based on income and spending behavior using clustering algorithms.

## Project Overview

This project performs customer segmentation using machine learning techniques to group customers based on similar purchasing behavior.

Customer segmentation helps businesses understand different types of customers and design targeted marketing strategies.

The project applies unsupervised learning algorithms to identify patterns in customer data and visualize customer groups.

## Dataset

The dataset contains information about customers such as:

- Customer ID  
- Age  
- Annual Income  
- Spending Score  

These features are used to analyze purchasing behavior and cluster customers into meaningful segments.

## Tools and Libraries

- python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

## Machine Learning Workflow

### Data Exploration
- inspect dataset structure  
- check for missing values  
- understand feature distributions  

### Data Preprocessing
- select relevant features  
- apply feature scaling using StandardScaler  

### Model Training
- k-means clustering  
- DBSCAN clustering  

### Finding Optimal Clusters
- elbow method for k-means  

### Visualization
- scatter plots to visualize customer clusters  

## Results

The model groups customers into distinct clusters based on spending behavior and income levels.

Customer groups identified include:

- high value customers  
- budget customers  
- potential growth customers  

## Key Insights

- customers with high income but low spending can be targeted with marketing campaigns  
- customers with low income but high spending represent loyal buyers  

## Future Improvements

- include more behavioral features  
- build interactive dashboards for business insights
