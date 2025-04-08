# RFM Analysis Project

![RFM Analysis](https://img.shields.io/badge/Analysis-Customer%20Segmentation-blue)
![Python](https://img.shields.io/badge/Python-3.7%2B-brightgreen)
![Pandas](https://img.shields.io/badge/Pandas-Latest-orange)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Latest-red)

## 📊 Project Overview

This repository contains a comprehensive implementation of RFM (Recency, Frequency, Monetary) analysis for customer segmentation using Python. RFM analysis is a powerful marketing technique used to quantitatively analyze and segment customers based on their purchasing behavior.

### What is RFM Analysis?

RFM stands for the three key dimensions of customer behavior:
- **Recency**: How recently did the customer purchase?
- **Frequency**: How often do they purchase?
- **Monetary Value**: How much do they spend?

By analyzing these three factors, businesses can effectively segment their customer base and develop targeted marketing strategies for each segment.

## 🎯 Project Goals

- Implement RFM analysis on customer transaction data
- Segment customers using advanced clustering techniques
- Visualize customer segments and their characteristics
- Identify high-value customers for targeted marketing campaigns
- Create actionable insights to improve customer retention and increase revenue

## 🚀 Features

- **Data Cleaning & Preprocessing**: Handles missing values, converts data types, and prepares data for analysis
- **RFM Score Calculation**: Computes quartile-based scores for recency, frequency, and monetary value
- **Customer Segmentation**: Implements K-means clustering to identify natural customer segments
- **Visualization**: Creates insightful plots to analyze segment characteristics
- **Customer Classification**: Identifies key customer groups like:
  - Best Customers (111)
  - Loyal Customers
  - Big Spenders
  - At-Risk Customers
  - Lost Customers

## 🛠️ Technologies Used

- **Python**: Programming language used
- **Pandas**: Data manipulation and analysis
- **scikit-learn**: Machine learning for K-means clustering
- **Matplotlib/Seaborn**: Data visualization
- **NumPy**: Numerical computation

## 📋 Prerequisites

- Python 3.7 or higher
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
- Missingno

## 🔧 Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/RFM-Project.git
cd RFM-Project
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:
```bash
jupyter notebook RFM_Project.ipynb
```

## 📊 Example Segments

| Segment Name           | Description                                   |
|------------------------|-----------------------------------------------|
| Best Customers         | Recent, frequent, and high-spending           |
| Loyal Customers        | Frequent buyers                               |
| Big Spenders           | High total spending                           |
| Almost Lost            | Previously valuable, now inactive             |
| Lost Customers         | Low value and inactive                        |
| Lost Cheap Customers   | Inactive and rarely spent much                |

## 📈 Analysis Process

1. **Data Loading & Exploration**: Load the transaction data and perform initial exploratory analysis
2. **Data Preprocessing**: Clean the data by handling missing values, refunds, and data type conversions
3. **RFM Calculation**: Calculate recency, frequency, and monetary values for each customer
4. **K-means Clustering**: Apply K-means clustering to identify natural customer segments
5. **RFM Scoring**: Calculate RFM scores using quartile-based segmentation
6. **Customer Classification**: Classify customers into meaningful business segments
7. **Visualization & Insights**: Create visualizations to understand segment characteristics and derive actionable insights

## 📊 Example Visualizations

- 📌 Average Recency, Frequency, and Monetary by Total Score  
- 📌 Scatter plots to view customer clusters  
- 📌 Boxplots to compare RFM distribution across clusters  
- 📌 Multi-line chart showing trends of R/F/M by score

## 🔍 Results & Insights

The analysis identified three primary customer segments:

- **Platinum Customers (Cluster 1)**: High frequency, very high monetary value, low recency (recent purchasers)
- **Gold Customers (Cluster 2)**: Medium frequency, medium monetary value, low recency
- **Silver Customers (Cluster 0)**: Low frequency, low monetary value, high recency (haven't purchased recently)

These segments can be targeted with different marketing strategies:
- **Platinum**: Loyalty programs, VIP offers, and exclusive products
- **Gold**: Upselling, cross-selling, and incentives to increase purchase frequency
- **Silver**: Re-engagement campaigns, special discounts to reactivate

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👏 Acknowledgments

- Online Retail Dataset used for analysis
- Inspiration from various RFM analysis implementations in the data science community

---

Created with ❤️ by [Hang Wang]
