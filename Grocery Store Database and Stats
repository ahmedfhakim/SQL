--Create a grocery store database

CREATE TABLE store (id INTEGER PRIMARY KEY, name TEXT, inventory INTEGER, COG INTEGER, price INTEGER);

INSERT INTO store VALUES(1, "bananas", 10, 0.25, 1);
INSERT INTO store VALUES(2, "apples", 200, 0.5, 2);
INSERT INTO store VALUES(3, "kiwis", 300, 0.15, 0.5);
INSERT INTO store VALUES(4, "blueberries", 75, 0.2, 0.8);
INSERT INTO store VALUES(5, "chips", 100, 0.15, 0.6);
INSERT INTO store VALUES(6, "salsa", 15, 0.35, 1);
INSERT INTO store VALUES(7, "carrots", 10, 0.25, 1);
INSERT INTO store VALUES(8, "broccoli", 80, 0.75, 3);
INSERT INTO store VALUES(9, "garlic", 20, 0.25, 1);
INSERT INTO store VALUES(10, "kale", 65, 0.4, 2);
INSERT INTO store VALUES(11, "pomegranate", 30, 1, 5);
INSERT INTO store VALUES(12, "potatoes", 45, 0.5, 2.5);
INSERT INTO store VALUES(13, "fish", 1000, 4, 10);
INSERT INTO store VALUES(14, "nuts", 250, 1.4, 7);
INSERT INTO store VALUES(15, "rice", 800, 1, 4);

--display the database ordered by price
Select * FROM store 
ORDER BY price;

Select SUM(price) 
FROM store
order by price
limit 5;
