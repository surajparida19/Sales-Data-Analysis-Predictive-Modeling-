# 🛒 Sales Data Analysis & Predictive Modeling

[![Python](https://img.shields.io/badge/Python-3.9-blue)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)](https://pandas.pydata.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 📌 Project Overview

This project demonstrates **Sales Data Analysis and Predictive Modeling** on the **Global Superstore dataset**. It focuses on data cleaning, visualization, and sales forecasting using Python. The goal is to uncover sales trends, understand factors impacting profitability, and build a baseline predictive model.

---

## 🎯 Objectives

* Perform **Exploratory Data Analysis (EDA)** to discover insights and trends
* Clean and preprocess raw sales data for accuracy
* Visualize key metrics influencing sales performance
* Build and evaluate a **Linear Regression** model to forecast sales
* Provide actionable **business recommendations** based on data

---

## 🧩 Features

* **Data Cleaning:** Handled duplicates, converted dates, standardized column names
* **Outlier Detection:** Removed extreme values in `Sales` and `Profit` using the IQR method
* **Visualization:** Heatmaps, boxplots, histograms, and time series charts
* **Predictive Modeling:** Linear Regression using `Profit` and `Discount` as predictors
* **Performance Evaluation:** Metrics include R² and Mean Squared Error (MSE)

---

## 📊 Dataset

The **Global Superstore** dataset contains detailed e-commerce sales records with the following key fields:

* `Order_Date`
* `Sales`
* `Profit`
* `Discount`
* `Quantity`
* `Category`
* `Region`

> Ensure your dataset file (e.g., `Global_Superstore.csv`) is placed in the project folder.

---

## ⚙️ Tools & Technologies

| Category             | Tools & Libraries   |
| -------------------- | ------------------- |
| Programming Language | Python 3            |
| Data Analysis        | Pandas, NumPy       |
| Visualization        | Matplotlib, Seaborn |
| Machine Learning     | Scikit-learn        |
| IDE                  | Jupyter Notebook    |

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Sales-Data-Analysis.git
   cd Sales-Data-Analysis
   ```
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook Sales_Analysis.ipynb
   ```

---

## 📈 Key Insights

* **Seasonal Trend:** Sales peak during Q4 (Nov–Dec)
* **Discount Effect:** Higher discounts (>30%) significantly reduce profit
* **Top Segments:** The *Technology* category and *Central* region drive the most revenue
* **Model Result:** R² score of 0.16 → Profit and Discount alone don’t fully explain sales variations

---

## 💡 Recommendations

* **Optimize Discount Strategy:** Cap discounts around 20–25% for profitability
* **Stock Planning:** Boost inventory before Q4 to meet demand
* **Targeted Marketing:** Focus on high-performing categories and regions
* **Enhance Model:** Include more features like `Quantity`, `Shipping_Cost`, and `Customer_Segment`

---

## 📂 Project Structure

```
├── data/
│   └── Global_Superstore.csv
├── notebooks/
│   └── Sales_Analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork this repository
2. Create a new branch (`feature/your-feature`)
3. Commit and push your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

📧 **Suraj Parida** — [surajparida9191@gmail.com](surajparida9191@gmail.com)
🔗 [LinkedIn]([https://www.linkedin.com/in/surajparida19/]) | [GitHub](https://github.com/surajparida19)

---

> Made with ❤️ using Python, Pandas, and Scikit-learn.
