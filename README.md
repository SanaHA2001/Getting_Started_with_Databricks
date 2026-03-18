# Getting_Started_with_Databricks

Project Use Case:
The PROJECT: Retail Sales Analysis for Optimizing Store Performance ==> Analyse des ventes au détail pour optimiser les performances des magasins

Objective:
1_ Clean and prepare sales and store data
2_ Add derived columns for Advanced insights 
3_ Analyse store performance and product trends

Datasets:
1_ Sales data (CSV file):
      sale_id == unique ID for each sale
      store_id == store where the sale occured
      product_id  == product sold
      sale_date == date of the sale
      quantity == number of items sold
      total_amount == total amount of the sale (USD)

2_ Store date (CSV file)
      store_id == unique id for the store 
      store_region == region where the store is located 
      store_size == size of the store in square feet
      open_date == date when the store was opened 

Project Requirements:
1_ Data transformation
      Join the sales and store datasets
      Create new columns
      Sales per square foot: calculate total sales divided by store size 
      sale year: extract the year from the sale date 
      Aggregate sales and quantity by store and region 

2_ Analysis
      Identify the top five stores based on total sales 
      Find the top five products by total quantity sold 

3_ Save results
      Save the transformed and aggregated results as Parquet files 

