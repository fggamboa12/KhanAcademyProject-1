# KhanAcademyProject-1
CREATE Table Bike_List(id Integer Primary key, bike_name Text, price numeric, year integer, rating integer);
INSERT INTO Bike_List values (1, "Specialized Allez", 119, 2018, 5);
INSERT INTO Bike_List VALUES (2, "Cannondale CAAD13 Disc", 399, 2023, 3);
INSERT INTO Bike_List VALUES (3, "Giant Contend SL1", 239, 2024, 3);
INSERT INTO Bike_List VALUES (4, "Cervelo S5", 199, 2019, 5);
INSERT INTO Bike_List VALUES (5, "Giant Propel Adance SL", 350, 2020, 4);
INSERT INTO Bike_List VALUES (6, "Trek Madone", 899, 2024, 5);
INSERT INTO Bike_List VALUES (7, "Vitus Venon EVO-RS", 989, 2024, 5);
INSERT INTO Bike_List VALUES (8, "RibasuBB", 150, 2023, 5);
INSERT INTO Bike_List VALUES (9, "Schwinn Ranger Mountain Bike", 300, 2021, 4);
INSERT INTO Bike_List VALUES (10, "Retrospec Chatham", 249, 2023, 4);
INSERT INTO Bike_List VALUES (11, "Priority Classic Plus", 599, 2021, 3);
INSERT INTO Bike_List VALUES (12, "Electra Townie 7D", 630, 2022, 4);
INSERT INTO Bike_List VALUES (13, "Polygon Path 2", 599, 2023, 5);
INSERT INTO Bike_List VALUES (14, "Cannondale Quick 4", 499, 2022, 4);
INSERT INTO Bike_List VALUES (15, "Aventon Pace 500.3", 1599, 2024, 4);
Select * from Bike_List order by price;
Select Avg(price)from Bike_List;
