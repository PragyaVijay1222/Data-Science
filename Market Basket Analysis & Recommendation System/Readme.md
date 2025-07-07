# 🛒 Market Basket Analysis & Recommendation System

A Market Basket Analysis and Product Recommendation system using the **Online Retail dataset** (Kaggle) and **FP-Growth algorithm** for efficient association rule mining, paired with insightful visualizations.

---

## 📌 Project Overview

This project performs **Market Basket Analysis** to uncover associations between products purchased together in retail transactions.  
It helps businesses improve cross-selling strategies by identifying frequent item combinations and generating product recommendations.

Key steps:
- Data cleaning and preprocessing
- Dimensionality reduction to focus on Top 30 most sold products
- Frequent itemset mining using **FP-Growth**
- Generating association rules based on confidence and lift
- Visualizing frequent itemsets and product associations using bar plots and network graphs

---

## 📖 Key Definitions

- **Market Basket Analysis (MBA):**  
  A data mining technique used by retailers to identify relationships between items purchased together in transactions.

- **Frequent Itemset:**  
  A group of products that appear together in a set of transactions with a frequency above a user-specified threshold (support).

- **Association Rule:**  
  An implication of the form *A → B*, meaning if a customer buys product A, they’re likely to buy product B.

- **Support:**  
  The proportion of transactions that contain a specific itemset.  
  *Example:* Support of 0.05 means the itemset appears in 5% of all transactions.

- **Confidence:**  
  The likelihood of occurrence of consequent items given the antecedent.  
  *Example:* If Confidence of *A → B* is 0.7, then 70% of customers who buy A also buy B.

- **Lift:**  
  A measure of how much more often A and B occur together than expected if they were independent.  
  Lift > 1 suggests a positive association between products.

- **FP-Growth Algorithm:**  
  A fast, memory-efficient algorithm for frequent itemset mining that uses a compact tree structure (FP-tree) instead of candidate generation like Apriori.

---

## 📊 Dataset

- **Name:** Online Retail Dataset  
- **Source:** [Kaggle — E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
- **Transactions:** UK-based online retailer’s transactional data  

---

## 📦 Tech Stack

- **Python 3.x**
- **Pandas**
- **mlxtend (FP-Growth & Association Rules)**
- **Seaborn & Matplotlib (Visualization)**
- **NetworkX (Network Graphs)**

---

## 📈 Features & Visualizations

✅ Market Basket Matrix  
✅ Frequent Itemsets via FP-Growth  
✅ Association Rules with Confidence and Lift  
✅ Top 10 Frequent Itemsets Barplot  
✅ Product Recommendation Network Graph  

---

## 📊 Visual Previews

### 📊 Frequent Itemsets Barplot

Displays top 10 product combinations with highest support values.

### 🌐 Association Rules Network Graph

A directed graph where:
- **Nodes:** Products  
- **Edges:** Strong association rules (thickness ∝ lift)  

---

## 📚 How to Run

1. 📥 Clone this repository:
   ```bash
   git clone https://github.com/PragyaVijay1222/Data-Science/new/main/Market%20Basket%20Analysis%20%26%20Recommendation%20System.git
   cd Market-Basket-Analysis
   
2. 📦 Install required libraries:
   ```bash
   pip install pandas mlxtend seaborn matplotlib networkx
   
3.📂 Place OnlineRetail.csv in the project directory.

4. ▶️ Run the notebook or script


---

## 📌 Results

Identified frequent product combinations in transactional data.

Generated association rules with actionable confidence and lift scores.

Created intuitive visualizations for business insights and product recommendation strategies.

---

##📑 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

Kaggle for providing the Online Retail dataset.

mlxtend library authors for FP-Growth and association rules implementation.

