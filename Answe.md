1) Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
Ans:- In above diagram, The Product and Product_category entities have relationship between  them using a category_id as a foreign key which 
      serve as a reference to Product_category table.
      It show the each product in product table is associated with a specific category defined in the Product_Category.
2) How Colud you ensure that each product in the product table has a valid category assigned to it.
Ans:- You can ensure that by making category_id Column in Product a foreign key which is referencing a id column of product_table and that id is
     primary key constraints that ensure that each product in product table is associated with a specific category in the Product_table 
