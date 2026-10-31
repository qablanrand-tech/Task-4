 We made a file called products.json and put 10 products for our online store (such as mouse, keyboard, T-shirt, coffee... Etc.).

• We chose the partition key  and made it be “category”: because it is the smart idea to distribute products by category (electronics, clothes, home), and this is to make search and access data much faster.

• We wrote how many query or filter sentences (Queries) to know how to search the data aire easily, like this:

• If we want to bring all the products: we write SELECT * FROM c

• If we want to spread electronics products only: we write SELECT * FROM c WHERE c.category = 'Electronics'

• If we want to look for products with a price between 20 and 60: we write SELECT * FROM c WHERE c.price >= 20 AND c.price <= 60