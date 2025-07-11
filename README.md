# 📊 eCommerce Tableau Dashboard (50K Records via GCP & Kaggle)

This dashboard visualizes an eCommerce dataset using **Tableau Public**, focusing on sales performance, customer activity, top products, and country-level insights.

The project originally leveraged **Google Cloud Storage** and **BigQuery** for data processing and querying. However, to ensure free and fast public access without incurring query costs, the data was extracted, cleaned, and used in CSV format.

---

## 📍 Live Dashboard  
👉 [View on Tableau Public](https://public.tableau.com/app/profile/essam.afifi/viz/E-CommerceAnalyticsDashboard50K/E-CommerceOverview?publish=yes)

---

## 📷 Dashboard Previews

### 🔹 Performance Overview  
![Performance Overview](images/Performance%20Overview.png)

### 🔹 Interactive Country Map  
![Interactive Country Map](images/InteractiveCountryMap.png)

### 🔹 Top Products  
![Top Products](images/TopProducts.png)

### 🔹 Filters Panel  
![Filters](images/Filters.png)

---

## 📚 Data Source

The original dataset is publicly available on Kaggle:  
[🗂️ eCommerce Data by carrie1](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

### 🔄 Data Pipeline Summary

- ✅ Raw CSV uploaded to **Google Cloud Storage**
- ✅ Queried, cleaned, and summarized using **BigQuery**
- ✅ Final 50K-row sample exported to CSV for use in Tableau  
- ✅ This avoids public users triggering paid BigQuery queries when using the dashboard

---

## 📁 Dataset

- Original: 500K+ raw records
- Processed: 50K cleaned rows with derived time fields (hour, weekday, month) and country mappings
- Covers orders, customers, products, pricing, and locations

---

## 🗂️ Repository Structure

├── Data/
│ ├── Raw/
│ │ ├── ecommerce_data.csv ← Original dataset from Kaggle
│ └── Processed/
│ └── ecommerce_sample50K.csv ← Cleaned dataset used in dashboard
│
├── E-Commerce Analytics Dashboard 50 K.twb ← Tableau Workbook (editable)
├── E-Commerce Analytics Dashboard 50 K.twbx ← Tableau Packaged Workbook (includes data)
├── images/
│ ├── Performance Overview.png
│ ├── InteractiveCountryMap.png
│ ├── TopProducts.png
│ └── Filters.png
└── README.md


---

## 🎥 Video Overview

For a full walkthrough of this and related dashboards:  
[🎬 Watch the Demo](https://github.com/essamun/Ecom-Dashboard-Analytics#video-demo)

---

## 🔄 Other Versions of This Dashboard

| Tool           | Dataset Size | Link |
|----------------|--------------|------|
| 🟢 Streamlit   | 1M+ records  | [GitHub](https://github.com/essamun/Ecom-Dashboard-Analytics) |
| 🟡 Power BI    | 1M+ records  | [GitHub](https://github.com/essamun/eCommerce-PowerBI-Dashboard) |
| 🔴 Looker Studio| 50K records | [Live Link](https://lookerstudio.google.com/reporting/f16be1e0-4668-4a6d-a952-6a0e2f1704da)
