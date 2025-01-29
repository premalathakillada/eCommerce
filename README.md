# eCommerce Transactions dataset
An eCommerce Transactions dataset consisting of three files: Customers.csv, Products.csv, and Transactions.csv. Performed exploratory data analysis (EDA), built predictive models, and derived actionable insights. This assignment tested data analysis, machine learning, and business insight generation skills.

Customers.csv:
https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing

Products.csv :
https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing

Transactions.csv :
https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing

Files Description:
1. Customers.csv
○ CustomerID: Unique identifier for each customer.
○ CustomerName: Name of the customer.
○ Region: Continent where the customer resides.
○ SignupDate: Date when the customer signed up.
2. Products.csv
○ ProductID: Unique identifier for each product.
○ ProductName: Name of the product.
○ Category: Product category.
○ Price: Product price in USD.
3. Transactions.csv
○ TransactionID: Unique identifier for each transaction.
○ CustomerID: ID of the customer who made the transaction.
○ ProductID: ID of the product sold.
○ TransactionDate: Date of the transaction.
○ Quantity: Quantity of the product purchased.
○ TotalValue: Total value of the transaction.
○ Price: Price of the product sold.

Task 1: Exploratory Data Analysis (EDA) and Business Insights1. Performed EDA on the provided dataset.
2. Derived at least 5 business insights from the EDA.
○ Written these insights in short point-wise sentences (maximum 100 words per
insight).
Deliverables:
● A Jupyter Notebook/Python script containing EDA code.
● A PDF report with business insights (maximum 500 words).

Task 2: Lookalike Model
Built a Lookalike Model that takes a user's information as input and recommends 3 similar
customers based on their profile and transaction history. The model should:
● Used both customer and product information.
● Assigned a similarity score to each recommended customer.
Deliverables:
● Given the top 3 lookalikes with there similarity scores for the first 20 customers
(CustomerID: C0001 - C0020) in Customers.csv. Form an “Lookalike.csv” which has
just one map: Map<cust_id, List<cust_id, score>>
● A Jupyter Notebook/Python script explaining model development.

Task 3: Customer Segmentation / Clustering
Performed customer segmentation using clustering techniques. Used both profile information
(from Customers.csv) and transaction information (from Transactions.csv).
● Have the flexibility to choose any clustering algorithm and any number of clusters in
between(2 and 10)
● Calculated clustering metrics, including the DB Index(Evaluation done on this).
● Visualise clusters using relevant plots.
Deliverables:
● A report on clustering results, including:
○ The number of clusters formed.
○ DB Index value.
○ Other relevant clustering metrics.
● A Jupyter Notebook/Python script containing your clustering code.
