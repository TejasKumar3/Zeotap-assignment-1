Overview
This repository contains the solution to a data science assignment based on an eCommerce transactions dataset. The tasks include exploratory data analysis (EDA), building a Lookalike Model, and performing customer segmentation using clustering techniques.

Dataset Descriptio
The dataset consists of the following files:
1. Customers.csv:
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. Products.csv:
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. Transactions.csv:
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.

Assignment Tasks
Task 1: Exploratory Data Analysis (EDA)
- Perform EDA on the dataset to uncover patterns and trends.
- Derive 5 actionable business insights.
- Deliverables:
  - Tejas_K_EDA.ipynb: Jupyter Notebook containing the EDA code.
  - Tejas_K_EDA.pdf: PDF report summarizing the insights with visualizations.

Task 2: Lookalike Model
- Build a Lookalike Model to recommend 3 similar customers based on profiles and transaction history.
- Deliverables:
  - Tejas_K_Lookalike.ipynb: Jupyter Notebook explaining the Lookalike Model.
  - Tejas_K_Lookalike.csv: CSV file with recommendations for the first 20 customers.

Task 3: Customer Segmentation (Clustering)
- Perform clustering on customer data to segment them into meaningful groups.
- Deliverables:
  - Tejas_K_Clustering.ipynb: Jupyter Notebook containing clustering code and results.
  - Tejas_K_Clustering.csv: CSV file with cluster assignments for each customer.
  - Tejas_K_Clustering.pdf: PDF report summarizing the clustering analysis.
  - 
How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
3. Open the respective Jupyter Notebook files (`.ipynb`) in Jupyter Notebook, JupyterLab, or VS Code to view or run the code.

---

Folder Structure
```
.
├── Customers.csv
├── Products.csv
├── Transactions.csv
├── Tejas_K_EDA.ipynb
├── Tejas_K_EDA.pdf
├── Tejas_K_Lookalike.ipynb
├── Tejas_K_Lookalike.csv
├── Tejas_K_Clustering.ipynb
├── Tejas_K_Clustering.csv
├── Tejas_K_Clustering.pdf
└── README.md


Insights and Results
Task 1 (EDA):
- 5 actionable business insights with visualizations are provided in `Tejas_K_EDA.pdf`.

Task 2 (Lookalike Model):
- Recommendations for the first 20 customers are provided in `Tejas_K_Lookalike.csv`.

Task 3 (Customer Segmentation):
- Clustering results and analysis are detailed in `Tejas_K_Clustering.pdf`.


Contact
For questions or feedback, please reach out to:
- Name: Tejas K
- Email:tejaskumar037@gmail.com
