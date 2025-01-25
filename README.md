

# **Zeotap Data Science Assignment**

## **Overview**
This repository contains my solution for the **Zeotap Data Science Internship Assignment**. The assignment is based on analyzing an eCommerce Transactions dataset consisting of three files: `Customers.csv`, `Products.csv`, and `Transactions.csv`. The tasks involve:
1. Exploratory Data Analysis (EDA) and deriving business insights.
2. Building a Lookalike Model for customer recommendations.
3. Performing customer segmentation using clustering techniques.

---

## **File Structure**

```
├── data             # Dataset containing all records
├── Rahul_Chauhan_EDA.ipynb      # Jupyter Notebook for Task 1 (EDA)
├── Rahul_Chauhan_EDA.pdf        # PDF report containing EDA insights
├── Rahul_Chauhan_Lookalike.ipynb # Jupyter Notebook for Task 2 (Lookalike Model)
├── Rahul_Chauhan_Lookalike.csv  # CSV containing Lookalike Model results
├── Rahul_Chauhan_Clustering.ipynb # Jupyter Notebook for Task 3 (Customer Segmentation)
├── Rahul_Chauhan_Clustering.pdf # PDF report on clustering results
└── README.md                    # Project documentation
```

---

## **Tasks and Deliverables**

### **Task 1: Exploratory Data Analysis (EDA)**
- **Objective**: Perform EDA on the provided dataset and derive at least 5 business insights.
- **Deliverables**:
  - `Rahul_Chauhan_EDA.ipynb`: Contains the Python code for EDA.
  - `Rahul_Chauhan_EDA.pdf`: Provides business insights derived from EDA.
- **Key Insights**:
  - Distribution of customers by region.
  - Signup trends over time.
  - Top-performing product categories.
  - Transaction value trends.

---

### **Task 2: Lookalike Model**
- **Objective**: Build a Lookalike Model to recommend 3 similar customers based on profile and transaction history.
- **Deliverables**:
  - `Rahul_Chauhan_Lookalike.ipynb`: Jupyter Notebook explaining the model development.
  - `Rahul_Chauhan_Lookalike.csv`: Results with top 3 recommendations for customers (C0001–C0020).
- **Key Features**:
  - Utilized both customer and product information.
  - Cosine similarity was used to compute customer similarities.

---

### **Task 3: Customer Segmentation**
- **Objective**: Perform customer segmentation using clustering techniques and evaluate using clustering metrics.
- **Deliverables**:
  - `Rahul_Chauhan_Clustering.ipynb`: Code for clustering and visualization.
  - `Rahul_Chauhan_Clustering.pdf`: Report with results, DB Index, and insights.
- **Key Highlights**:
  - K-Means clustering was used with the optimal number of clusters determined by the Davies-Bouldin Index.
  - Clusters visualized using scatter plots for better interpretability.

---

## **How to Run the Code**
1. Clone the repository:
   ```bash
   git clone (https://github.com/Rahul4112002/Zeotap-Data-Science-Internship)
   ```
2. Install the required Python libraries:
   *(Include  if libraries are extensive; otherwise, list major ones like Pandas, Scikit-learn, Matplotlib, Seaborn, etc.)*
3. Open the Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```
   - Run `Rahul_Chauhan_EDA.ipynb` for EDA insights.
   - Run `Rahul_Chauhan_Lookalike.ipynb` for Lookalike Model.
   - Run `Rahul_Chauhan_Clustering.ipynb` for customer segmentation.

---

## **Evaluation Metrics**
1. **Task 1**:
   - Quality of business insights.
   - Clarity of EDA visualizations.
2. **Task 2**:
   - Accuracy and logic of Lookalike Model.
   - Quality of recommendations and similarity scores.
3. **Task 3**:
   - Optimal cluster evaluation using the Davies-Bouldin Index.
   - Visual representation of customer clusters.

---

## **Contact**
If you have any questions or feedback, feel free to reach out:
- **Name**: Rahul Chauhan
- **Email**: rahulchauhan4708@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/rahul-chauhan-932522230/
- **Portfolio**: https://rahul4112002.github.io/myportfolio/
---
