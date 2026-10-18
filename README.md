# 📊 Superstore Executive Intelligence Hub

An executive-level interactive Power BI dashboard designed to provide end-to-end business insights—covering financial performance, product profitability, customer value segmentation, and operational return risk.

---

## 📸 Dashboard Overview

### Page 1: Executive Overview
![Overview](images/Superstore_Executive_Intelligence_Hub-1.png)

### Page 2: Product & Discount Analysis
![Product Analysis](images/Superstore_Executive_Intelligence_Hub-2.png)

### Page 3: Customer & Return Risk Deep-Dive
![Customer & Returns](images/Superstore_Executive_Intelligence_Hub-3.png)

---

## 🔑 Key Features & Insights

* **Financial Tracking:** Dynamic monitoring of Sales, Profit Margin %, and Order Volumes across multi-year trends.
* **Product Efficiency:** Scatter plot analysis evaluating Discount vs. Profit Margin to identify value-destroying discount strategies.
* **Customer Value:** High-value customer identification with conditional formatting for risk and profitability.
* **Return Risk Analysis:** Tree map visualization using custom 3-tier gradient formatting (Teal / Amber / Coral) to pinpoint high-return regions and sub-categories.

---

## 🛠️ Technical Specifications

* **Data Modeling:** Star Schema architecture with bidirectional filtering between `Orders` and `Returns`.
* **DAX Measures:** Calculated custom measures for `Profit Margin %`, `Return Rate %`, and `Total Returned`.
* **Design Standards:** Muted color palette (`#2A9D8F`, `#E9C46A`, `#E76F51`), locked layout grid, and seamless page navigation.

---

## 📂 Project Structure

```text
├── dataset/                    # Sample Superstore dataset
├── images/                     # Dashboard screenshots for preview
├── Superstore_Executive.pbix  # Main Power BI Desktop file
└── README.md                   # Project documentation
