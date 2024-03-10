QNo.1 Ans:The “Product” and “Product_Category” entities are related through a foreign key relationship. The “Product” entity has an attribute “category_id” which references the “id” of the “Product_Category” entity, linking each product to its respective category.

QNo.2 Ans:To ensure each product has a valid category:
Enforce a foreign key constraint on “category_id” in the “Product” table.
Make “category_id” a mandatory field