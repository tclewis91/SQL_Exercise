1. There are 54 users.  .schema
2.60:Ergonomic Steel Car:Books & Outdoors:Enterprise-wide secondary firmware:9341
  40:Sleek Wooden Hat:Music & Baby:Quality-focused heuristic info-mediaries:9390
  100:Awesome Granite Pants:Toys & Books:Upgradable 24/7 access:9790
  83:Small Wooden Computer:Health:Re-engineered fault-tolerant adapter:9859
  25:Small Cotton Gloves:Automotive, Shoes & Beauty:Multi-layered modular service-desk:9984         SELECT * FROM Items ORDER By Price
3.76:Ergonomic Granite Chair:Books:De-engineered bi-directional portal:1496
     it is still the cheapest                                                  sqlite> SELECT * FROM Items WHERE Category LIKE "Book%";
4.Corrine Little
                                                                              SELECT first_name, last_name FROM users JOIN addresses ON users.id = addresses.user_id where addresses.street LIKE '6439 Z%'
5.                             SELECT * FROM users JOIN adddresses ON addresses.user_id= users.id WHERE user.first_name LIKE 'Virginie%';
                              <!-- <!--  --> FOUND USER ID 39 --> UPDATE addresses SET state = "NY" WHERE user_id = 39;
                                                                  UPDATE addresses SET zip = "10108" user_id = 39;
                                                                  UPDATE addresses SET city ="New York " WHERE user_id =39;
6.sqlite> SELECT SUM(price) FROM Items WHERE category LIKE "tools%";
24605
7. SELECT SUM(quantity) FROM orders;
2125
8. SELECT SUM(price * quantity) FROM orders JOIN items ON items.id = orders.item_id WHERE category LIKE "books%";  503761
9.INSERT INTO USERS(id, first_name, last_name, email) SELECT '109', 'Tiffany', 'Lewis', 'hungryhippo@aol.com';
  INSERT INTO ORDERS(id, user_id, item_id, quantity, created_at) SELECT '12415', '109', '53', '3','1991';



