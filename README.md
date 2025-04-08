# 📊 RFM Customer Segmentation Project

This project performs customer segmentation using the **RFM model** (Recency, Frequency, Monetary) and unsupervised learning techniques like **KMeans clustering**. The goal is to help businesses identify different types of customers (e.g., loyal customers, big spenders, or those at risk of churn) for personalized marketing strategies and data-driven decision-making.

---

## 🔧 Technologies Used

- 🐍 Python (Pandas, NumPy, Matplotlib, Seaborn)
- 📈 Scikit-learn (for KMeans clustering)
- 📓 Jupyter Notebook / Google Colab
- 📊 Data visualization (boxplots, bar charts, multi-axis line charts)

---

## 📊 Example Segments

| Segment Name           | Description                                   |
|------------------------|-----------------------------------------------|
| Best Customers         | Recent, frequent, and high-spending           |
| Loyal Customers        | Frequent buyers                               |
| Big Spenders           | High total spending                           |
| Almost Lost            | Previously valuable, now inactive             |
| Lost Customers         | Low value and inactive                        |
| Lost Cheap Customers   | Inactive and rarely spent much                |

---

## 🛠️ How It Works

1. **Data Preprocessing**
   - Parse dates, clean missing data
   - Calculate total purchase value

2. **RFM Calculation**
   - Recency = Days since last purchase
   - Frequency = Unique purchases
   - Monetary = Total spend

3. **RFM Scoring**
   - Use quartiles to score each R/F/M value (1–4)
   - Lower R = better; Higher F/M = better

4. **Customer Segmentation**
   - Assign predefined labels based on RFM scores
   - Create `RFM_Score` and `Total_score` for analysis

5. **Clustering**
   - Normalize RFM features
   - Use KMeans for unsupervised customer grouping
   - Visualize clusters

6. **Visualization**
   - Bar plots for average R/F/M by total score
   - Multi-axis line chart combining RFM metrics
   - Scatter plot by cluster

---

## 📊 Example Visualizations

- 📌 Average Recency, Frequency, and Monetary by Total Score  
- 📌 Scatter plots to view customer clusters  
- 📌 Boxplots to compare RFM distribution across clusters  
- 📌 Multi-line chart showing trends of R/F/M by score

---

For questions, improvements, or suggestions — feel free to open an issue or submit a pull request.

