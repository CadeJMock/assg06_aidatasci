# Mall Customer Segmentation Analysis

## Project Overview
This project analyzes a mall customer dataset to identify distinct customer segments using K-means clustering. By examining customers' annual income and spending patterns, we segment customers into meaningful groups that can be targeted with specific marketing strategies.

## Dataset
The analysis uses the "Customers.csv" dataset, which contains:
- CustomerID: Unique identifier for each customer
- Genre: Gender (Male/Female)
- Age: Age of the customer
- Annual Income (k$): Annual income in thousands of dollars
- Spending Score (1-100): Score assigned by the mall based on customer spending behavior

## Methodology
The project follows these key steps:
1. **Exploratory Data Analysis (EDA)** - Examined the dataset's structure and visualized feature distributions
2. **Feature Selection** - Focused on Annual Income and Spending Score as key clustering variables
3. **Optimal Cluster Determination** - Used the Elbow Method to identify the optimal number of clusters (K=5)
4. **K-means Clustering** - Applied the algorithm and visualized the resulting customer segments

## Results
The analysis identified 5 distinct customer segments:

1. **Middle-Income, Average Spenders (40.5%)** - The largest segment with moderate income ($55.3k) and spending score (49.5)
2. **High-Income, High Spenders (19.5%)** - Premium customers with high income ($86.5k) and high spending score (82.1)
3. **Low-Income, High Spenders (11%)** - Aspirational shoppers with low income ($25.7k) but high spending score (79.4)
4. **High-Income, Low Spenders (17.5%)** - Potential customers with high income ($88.2k) but low spending score (17.1)
5. **Low-Income, Low Spenders (11.5%)** - Budget-conscious customers with low income ($26.3k) and low spending score (20.9)

## Key Insights
- The largest customer segment consists of middle-income, average spenders
- There's a significant group of high-income customers who spend very little (untapped potential)
- A smaller but notable segment of customers spend heavily despite having lower incomes

## Technologies Used
- Python 3
- pandas - Data manipulation
- numpy - Numerical operations
- matplotlib & seaborn - Data visualization
- scikit-learn - Machine learning implementation (K-means clustering)

## Files
- `mall_customer_segmentation.ipynb` - Jupyter notebook containing all analysis code and visualizations
- `Customers.csv` - Dataset used for analysis

## Future Work
Potential extensions of this analysis could include:
- Incorporating additional features like age and gender for more nuanced segmentation
- Implementing other clustering algorithms (DBSCAN, Hierarchical Clustering) for comparison
- Developing targeted marketing strategies for each customer segment
- Time series analysis to track how customer segments evolve over time

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## License
This project is licensed under the MIT License - see the LICENSE file for details.
