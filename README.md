# Customer Segmentation using RFM & K-Means

This project segments customers based on their purchasing behavior using **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering**. 

---

## 📊 Pipeline Workflow

1. **Data Cleaning:** Preprocesses transaction data (`InvoiceNo`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`) and drops invalid records.
2. **RFM Feature Extraction:** 
   * **Recency (R):** Days since the customer's last purchase.
   * **Frequency (F):** Total number of distinct orders placed.
   * **Monetary (M):** Total financial amount spent.
3. **K-Means Clustering:** Groups customers into 3 distinct clusters based on their RFM profiles.
4. **Custom Labeling:** Assigns business-friendly tiers to the resulting clusters:
   * 🥇 **Diamond:** Premium, frequent, and high-spending customers.
   * 🥈 **Gold:** Reliable, steady-spending customers.
   * 🥉 **Silver:** At-risk or newly acquired low-spending customers.

---
## Download this dataset
https://www.kaggle.com/datasets/vijayuv/onlineretail?resource=download
---

## 🛠️ Tech Stack
* **Languages & Environments:** Python, Jupyter Notebook
* **Libraries:** `pandas`, `numpy`, `scikit-learn` (`KMeans`), `matplotlib`, `seaborn`

---
## 🚀 Quick Start

1. Clone the repository and install dependencies:
```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
