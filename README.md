# 📊 RFM Customer Segmentation Project

This project performs customer segmentation using the **RFM model** (Recency, Frequency, Monetary) and unsupervised learning techniques like **KMeans clustering**. The goal is to help businesses identify different types of customers (e.g., loyal customers, big spenders, or those at risk of churn) for personalized marketing strategies and data-driven decision-making.

---

## 🔧 Technologies Used

- 🐍 Python (Pandas, NumPy, Matplotlib, Seaborn)
- 📈 Scikit-learn (for KMeans clustering)
- 📓 Jupyter Notebook / Google Colab
- 📊 Data visualization (boxplots, bar charts, multi-axis line charts)

---

## 📂 About the Data

The dataset used in this project, `rfm_stock_data.csv`, contains transaction-level data capturing customer purchase behavior in a stock-based product environment. Each row represents a single transaction and includes critical attributes that allow for the application of RFM (Recency, Frequency, Monetary) analysis for customer segmentation.

### 📌 Key Fields in the Dataset:

- **CustomerID**: A unique identifier for each customer.
- **InvoiceDate**: The date and time when the transaction occurred.
- **Quantity**: The number of units purchased in the transaction.
- **UnitPrice**: The price per unit of the purchased product.
- *(Optional fields may include InvoiceNo, StockCode, etc.)*

### 📈 Purpose of the Dataset:

This dataset is ideal for performing customer segmentation through **RFM analysis**, a proven framework in marketing analytics. It allows us to evaluate:

- **Recency**: How recently a customer has made a purchase.
- **Frequency**: How frequently the customer has made purchases.
- **Monetary Value**: How much the customer has spent in total.

Using these dimensions, we can score and segment customers into categories such as:
- High-value loyal customers
- Big spenders
- At-risk or lost customers
- New and potential customers

### 🧠 Why This Data Is Useful:

This type of transaction data is commonly used in retail, e-commerce, and financial platforms to:
- Improve personalized marketing campaigns
- Boost customer retention strategies
- Increase customer lifetime value (CLV)
- Perform churn analysis and loyalty prediction

The dataset reflects realistic purchasing behavior and provides a foundation for applying **data-driven decision making** in business analytics.

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

