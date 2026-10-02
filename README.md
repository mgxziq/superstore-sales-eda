# 📊 Superstore Sales – Exploratory Data Analysis (EDA)

An end-to-end Exploratory Data Analysis project analyzing retail performance, profitability, customer segments, and shipping efficiency using the classic **Sample Superstore** dataset.

---

## 📌 Project Overview
This project provides data-driven business insights by examining transaction records across multiple dimensions:
* **Product Performance:** Categories and sub-categories driving revenue vs. those incurring losses.
* **Profitability & Margins:** Investigating the hidden trade-offs between aggressive discounting and net profit.
* **Regional & Temporal Trends:** Identifying top-performing geographic markets and annual growth trajectory.
* **Customer Behavior & Logistics:** Evaluating order frequency, top-tier client value, and shipping mode turnaround times.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`
* **Environment:** Jupyter Notebook

---

## 📈 Key Findings & Business Insights

1. **Category Overview:**
   * **Technology** generated the highest sales ($836K+) with a solid profit margin of **~17.4%**.
   * **Furniture** suffered from compressed margins (**2.49%**), weighed down by negative-margin sub-categories.
2. **Loss-Making Products:**
   * Sub-categories running net negative profits: **Tables**, **Bookcases**, and **Supplies**.
3. **Discount Impact:**
   * Orders with discounts **≥ 30%** consistently resulted in net losses, highlighting the need to revise promotional strategies.
4. **Geography & Growth:**
   * The **West** region proved to be the most profitable, whereas the **Central** region lagged in margin efficiency.
   * Total sales peaked in **2017** with steady year-over-year expansion.
5. **Logistics:**
   * **Standard Class** was the dominant shipping channel (averaging ~5 business days), while **Same Day** and **First Class** provided reliable rapid fulfillment.

---

## 📂 Repository Structure

```text
├── Sample - Superstore.csv       # Dataset file
├── superstore_sales_eda.ipynb    # Main Jupyter Notebook analysis
├── fig1_category.png             # Visualizations export
├── fig2_subcategory_profit.png
├── fig3_yearly_trend.png
├── fig4_discount_profit.png
├── fig5_region.png
├── fig6_segment_pie.png
├── requirements.txt              # Required dependencies
└── README.md                     # Project documentation
