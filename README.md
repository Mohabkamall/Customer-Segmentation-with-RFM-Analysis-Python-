# Customer-Segmentation-with-RFM-Analysis-Python

## 📝 Task Overview 

This project performs RFM (Recency, Frequency, Monetary) analysis to segment customers based on their purchasing behavior. Using transaction data from a retail store, the goal is to identify customer groups and suggest targeted marketing strategies.

---

## 📁 Dataset

- Source: Online Retail Dataset – UCI Machine Learning Repository.

- Contains ~500,000 transactions from a UK-based online retail store between 2010 and 2011.

---

## 🎯 Objectives

- Clean and preprocess the dataset: remove missing data, filter valid transactions

- Calculate RFM metrics for each customer:

    - Recency: Days since last purchase

    - Frequency: Number of purchases

    - Monetary: Total amount spent

- Score each customer on a scale (e.g. 1–5) for each RFM metric

- Create a composite RFM score for segmentation

- Group customers into meaningful segments (e.g., Champions, Loyal, At-Risk)

---

## 🛠️ Tools & Libraries Used

- Python

- Pandas – for data transformation and RFM calculation

- Seaborn / Matplotlib / Plotly – for visualization

- (Optionally Excel for early data review)

---

## 📊 Key Steps
- Data cleaning: handle null values, remove canceled orders

- Feature engineering:

    - Recency based on reference date.

    - Frequency based on number of invoices.

    - Monetary based on total invoice amount.

- RFM scoring and segmentation logic using custom rules.

- Visualization of segments using:

    - Heatmaps (RFM score matrix)

    - Bar plots (customer count per segment)

    - Pie charts or treemaps (revenue contribution per group)

---

## 💡 Sample Segments & Marketing Ideas

  | Segment           | Description                    | Suggested Action                         |
  | ----------------- | ------------------------------ | ---------------------------------------- |
  | **Champions**     | Recent and frequent buyers     | VIP discounts or loyalty programs        |
  | **Loyal**         | Frequent but not high spenders | Upselling and early access to offers     |
  | **At Risk**       | Inactive for a long time       | Win-back emails and limited-time coupons |
  | **New Customers** | First-time or one-time buyers  | Welcome campaigns and product discovery  |
