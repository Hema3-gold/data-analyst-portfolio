# 📊 Walmart Sales Analysis

This project analyzes Walmart’s historical sales data to uncover sales trends, holiday impact, store performance, and how external factors influence weekly revenue.

---

## 📌 Project Objectives

- Analyze weekly and monthly sales trends
- Identify peak sales months and top-performing stores
- Compare holiday vs non-holiday sales
- Explore correlation between sales and external economic indicators

---

## 📁 Files Included

| File Name                       | Description                                                    |
|--------------------------------|----------------------------------------------------------------|
| `Walmart_Sales_Analysis.ipynb` | Main analysis notebook with code, charts, and insights         |
| `Walmart_Sales.csv`            | Dataset used for the project (uploaded under public license)   |
| `correlation_heatmap.png`      | Heatmap of correlation between sales and external factors      |
| `README.md`                    | Project overview and explanation                              |

---

## 📊 Dataset Description

The dataset used in this project is **Walmart Sales Forecasting**, originally published on Kaggle by [Mikhail Mandrygin](https://www.kaggle.com/mikhailmandrygin), and is licensed under **CC0: Public Domain**.

This dataset includes historical weekly sales data for 45 Walmart stores across the U.S., and contains the following features:

- `Store`: Store ID
- `Date`: Week ending date
- `Weekly_Sales`: Weekly sales amount
- `Holiday_Flag`: 1 = Holiday week, 0 = Non-holiday week
- `Temperature`: Local temperature (in Fahrenheit)
- `Fuel_Price`: Cost of fuel in the area
- `CPI`: Consumer Price Index
- `Unemployment`: Local unemployment rate

📂 [Original Dataset on Kaggle](https://www.kaggle.com/datasets/mikhailmandrygin/walmart-sales)

---

## 🧰 Tools & Technologies

- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 🔍 Key Insights

- **December and November** are peak sales months, aligned with **Christmas** and **Thanksgiving** holidays.
- **Thanksgiving** and **Super Bowl** weeks generate the highest average weekly sales.
- **Store 20** and **Store 4** are consistently top-performing in total sales.
- External factors like **Unemployment** have weak negative correlation with sales, while **Fuel Price, CPI, and Temperature** show almost no impact.
- Sales appear to be driven more by **seasonal events and promotions** than by external economic variables.

---

## 📌 Conclusion

This analysis highlights how holiday seasons significantly boost Walmart’s sales, while economic indicators have minimal influence. It emphasizes the value of seasonal marketing strategies. Future work could involve:
- Forecasting sales using time series models
- Deep-diving into department-wise or region-specific performance
- Creating interactive dashboards

---



## 👩‍💻 Author

**Hemalatha**  
Aspiring Data Analyst | Rebuilding career with passion for data 📈  
Completed IBM Data Analyst Certification | Learning hands-on with real projects


📬 Contact: [hemalatha210693@gmail.com]

## ⭐ If you find this project helpful, consider giving it a star!
