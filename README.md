# PROJECT-TOPIC-Amazon-Product-Review-Analysis
This project work focus on analyzing Amazon product listing using Excel to uncover insights through Excel Dashboard..

**DATA SOURCE**

The dataset used for this analysis contains product level in formation from Amazon including:
 
  Product name and Category
  
  Actual price and discounted price
  
  Ratings and Review Counts
  
  Discount Percentage and Product_id
  
  product links and other metadata.


**TOOLS USED**

  Excel for data cleaning, pivot table analysis and creating of Dashboad for visualization

**DATA CLEANING AND PREPARATION**
  
  1. Removing duplicate from the dataset.
  
  2. Creating the category within the main category with sub category
  
  3. Added caculated field.

     *Total Potential Profit

       Actual Price * Rating Count

     *Price Range Bucket

       =IF(H2<200,"<₹200",IF(OR(H2=200,H2<=500),"₹200-₹500","₹500"))

     *Discount Range Bucket

       =IF(K22>=50%,"50% or more","<50%")

     * Weighted Score

         Rating * Rating Count.

  **ANALYSIS PERFORMED**

  A total of 14 business questions were answered using Pivot tables and Formulas:

  1. Average discount percentage by product category.

  2. Number of products are listed under each category.

  3. Total number of reviews per category.

  4. Products with the highest average ratings.

  5. Average actual price vs the discounted price by category.

  6. Products have the highest number of reviews.

  7. Products have a discount of 50% or more.

  8. Distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.).

  9. Total potential revenue (actual_price × rating_count) by category.

  10. Number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500).

  11. Rating relate to the level of discount.

  12. Products with fewer than 1,000 reviews.

  13. Categories that have products with the highest discounts.

  14. Top 5 products in terms of rating and number of reviews combined.

     
