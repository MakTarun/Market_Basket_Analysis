# 🛒 Market Basket Analysis using Apriori Algorithm

## 📌 Project Overview

Market Basket Analysis is a data mining technique used to identify relationships between products that customers frequently purchase together. This project applies the **Apriori Algorithm** to discover frequent itemsets and generate association rules from a grocery transaction dataset. The insights obtained can help retailers improve product placement, create bundle offers, and increase cross-selling opportunities.

---

## 🎯 Objectives

* Analyze customer purchasing behavior.
* Identify frequently purchased product combinations.
* Generate association rules using the Apriori Algorithm.
* Visualize purchasing patterns and product associations.
* Provide business recommendations based on transaction data.

---

## 📂 Dataset

* **Dataset:** Grocery Transactions Dataset
* **Records:** 38,006 transactions (after data cleaning)
* **Features:**

  * `Member_number`
  * `Date`
  * `itemDescription`

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* mlxtend
* Jupyter Notebook

---

## 📊 Project Workflow

1. Import required libraries.
2. Load the grocery transaction dataset.
3. Perform data cleaning.

   * Check missing values.
   * Remove duplicate records.
4. Perform Exploratory Data Analysis (EDA).
5. Group purchased items into customer transactions.
6. Convert transactions into one-hot encoded format.
7. Apply the Apriori Algorithm.
8. Generate Association Rules.
9. Visualize frequent items and association rules.
10. Generate business insights and recommendations.

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

* Dataset overview
* Dataset shape
* Data types
* Missing value analysis
* Duplicate record removal
* Top 10 most purchased products

---

## 🤖 Machine Learning Technique

### Apriori Algorithm

The Apriori algorithm identifies frequent itemsets using minimum support and generates association rules based on confidence and lift values.

### Evaluation Metrics

* Support
* Confidence
* Lift

---

## 📉 Visualizations

The project includes the following visualizations:

* Top 10 Most Purchased Products
* Top 10 Frequent Itemsets
* Confidence vs Lift Scatter Plot

---

## 💡 Business Insights

* Whole Milk emerged as one of the most frequently purchased products.
* Frequently associated products indicate strong customer purchasing patterns.
* Products with high confidence and lift can be promoted together using combo offers.
* Cross-selling strategies can increase the average basket value.
* Store layout can be optimized by placing associated products closer together.
* Inventory planning can be improved by maintaining sufficient stock for frequently purchased products.

---

## 📋 Business Recommendations

* Introduce bundle offers for frequently purchased product combinations.
* Improve product recommendations using association rules.
* Optimize shelf placement based on customer buying behavior.
* Maintain adequate inventory for high-demand products.
* Use purchasing patterns for targeted marketing campaigns.

---

## 📁 Project Structure

```
Market-Basket-Analysis/
│
├── data/
│   └── Groceries_dataset.csv
│
├── notebook.ipynb
├── frequent_itemsets.csv
├── association_rules.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Future Enhancements

* Build a real-time recommendation system.
* Develop an interactive Streamlit dashboard.
* Apply the FP-Growth algorithm for performance comparison.
* Integrate recommendations into an e-commerce platform.

---

## 🎯 Conclusion

This project successfully applied the Apriori Algorithm to identify frequent itemsets and generate association rules from grocery transaction data. The analysis revealed valuable customer purchasing patterns that can help retailers improve cross-selling, product placement, inventory management, and promotional strategies. Overall, Market Basket Analysis provides a powerful, data-driven approach to understanding customer behavior and supporting business decision-making.

---

## 👨‍💻 Author

**Tarun Singh**


