# 📊 Innovatech Analytics International  
### Business Analytics Model — Nexford University  

**Author:** Joy Alimigbe  
**Course:** Business Analytics — Module 4  
**Project Title:** Business Analytics Model Development  

---

## 🔹 Overview  
This project demonstrates the full lifecycle of developing a **Business Analytics Model** for customer segmentation using machine learning.  
The model identifies behavioral patterns and revenue groups to support data-driven decision-making, customer retention, and marketing optimization.  

Developed as part of the **Nexford University Business Analytics Module 4 Assignment**, this work uses Python-based tools for data cleaning, feature engineering, clustering, and visualization.

---

## 🔹 Project Workflow  

### **Phase 1: Data Collection**  
- Generated synthetic subsidiary data for three business branches.  
- Stored as `.csv` files and compressed into **`subsidiary_report.zip`**.  

### **Phase 2: Data Cleaning**  
- Combined and cleaned raw subsidiary datasets.  
- Filled missing values and standardized numeric columns.  
- Output file: **`cleaned_dataset.csv`**  

### **Phase 3: Model Development**  
- Built a **K-Means Clustering Model** to segment customers based on key behavioral and financial features:  
  - Revenue  
  - Tenure  
  - Engagement Score  
  - Features Used  
  - Login Activity  
- Model evaluation metrics applied:  
  - **Silhouette Score**  
  - **Calinski-Harabasz Index**  
  - **Davies-Bouldin Score**  
- Output file: **`clustered_customers.csv`**  

### **Phase 4: Insights & Interpretation**  
| Cluster | Customer Type | Description |
|----------|----------------|-------------|
| **0** | Premium Customers | High revenue and engagement. |
| **1** | At-Risk Users | Low engagement and short tenure. |
| **2** | New Customers | Recently joined with minimal activity. |
| **3** | Engaged Regulars | Stable usage and moderate tenure. |

These insights enable **Innovatech Analytics International** to personalize marketing efforts and improve customer retention.

---

## 🔹 Tools Used  
- **Python 3.10+**  
- **Jupyter Notebook**  
- **pandas**, **NumPy** — Data cleaning and transformation  
- **Matplotlib**, **Seaborn** — Visualization  
- **scikit-learn** — Model development (K-Means, PCA, metrics)  


