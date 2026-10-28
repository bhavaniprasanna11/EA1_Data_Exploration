# EA1_Data_Exploration

# 📦 Product Sales Dataset

## 📌 Project Overview

This dataset contains sample product information, including product IDs, product names, brand names, prices, quantities, categories, price ranges, and date-related attributes.

It can be used for practicing data analysis, data visualization, Excel, SQL, Python, and Power BI.


## 🎯 Project Objectives

● Calculate the sum, count and average of product prices.
● Find Minimum and Maximum price for the product.
● Using IF function to categorize the product price
● Using SUMIF function to find the total price for the product in particular category
● Using COUNTIF function to find the product count less than price 100
● Using LEFT, RIGHT and MID function to separate a Day, Country code and Month column


## 🛠️ Tools and Technologies

This dataset can be used with:

- Microsoft Excel

  📂 Dataset Description
The dataset contains the following columns:

Column	Description
Product ID	Unique Code
Product Name	Name of the product
Brand Name	Brand
Price ($)	Price of the product in dollars
Quantity	product quantity
Category	Product category
<img width="391" height="183" alt="image" src="https://github.com/user-attachments/assets/a044fc21-33d8-424e-9d1d-6318b5ca4d2f" />

****1.  SUM, COUNT, and AVERAGE:-**
Perform basic calculations using Excel functions.
•	Sum – Calculate the total price of the all the Products
•	Count – Calculating the count of products exists in the dataset
•	Average – Calculating average price of the product.

S.No	Question	Answer
1	Sum	10100
2	Count	34
3	Average	297.0588235
<img width="343" height="105" alt="image" src="https://github.com/user-attachments/assets/b7257bac-5df6-4fd9-94c3-4e94f6e132df" />

Formulas:-
1. =SUM(D2:D35)
2. =COUNTA(D2:D35)
3. =AVERAGE(D2:D35)

**2.	Minimum and Maximum Values:-**

•	Minimum – Finding the minimum price of the product
•	Maximum  - Finding the maximum price of the product

S.No	Question	Answer
4	Minimun	30
5	Maximum	1000
<img width="343" height="79" alt="image" src="https://github.com/user-attachments/assets/b60507ed-345a-4f78-bdf7-85cf17d8579f" />


Formulas:-
4. =MIN(D2:D35)
5. =MAX(D2:D35)

**3.	Logical Function – IF:-**

•	Crating a new column as Price Range and,
•	Using IF function classified Price>=500 as Highprice and Price<500 as Standard Price

Price ($)	Quantity	Category	Price Range
1000	30	Electronics	High Price
80	15	Fashion	Standard Price
130	40	Kitchen	Standard Price
900	25	Electronics	High Price
70	20	Outdoor	Standard Price
200	45	Electronics	Standard Price
30	5	Fashion	Standard Price
90	35	Kitchen	Standard Price
<img width="457" height="235" alt="image" src="https://github.com/user-attachments/assets/336adc2d-b804-44a0-b09c-945583ed3781" />


Formulas:-
=IF(D2>=500,"High Price","Standard Price")

**4.	Conditional Functions – SUMIF and COUNTIF**:-

•	SUMIF - calculating the total price of products in the
Electronics category.
•	COUNTIF - determining the number of products with a price
less than $100.

S.No	Question	Answer
6	SumIF	8050
7	CountIF	11
<img width="343" height="79" alt="image" src="https://github.com/user-attachments/assets/0fae2518-25f7-4dfa-9f2c-556d96992a38" />


Formulas:-
6. =SUMIF(F2:F35,"Electronics",D2:D35)
7. =COUNTIF(D2:D35,"<100")

**5. Text Formatting – LEFT, RIGHT, MID**:-

○ Create a new column named Day with the first 2 characters of each
'Product ID' using the LEFT function.
○ Create a new column named Country Code by extracting the last 2
characters from the 'Product ID' column using the RIGHT function.
○ Create a new column named Month by extracting the 4th to 6th
characters from the 'Product ID' column using the MID function.

Product ID	Day	Country Code	Month
28-JAN-US	28	US	JAN
15-FEB-US	15	US	FEB
03-MAR-US	03	US	MAR
11-APR-US	11	US	APR
22-MAY-US	22	US	MAY
07-JUN-UK	07	UK	JUN
19-JUL-UK	19	UK	JUL
23-AUG-UK	23	UK	AUG
05-SEP-UK	05	UK	SEP
14-OCT-UK	14	UK	OCT
<img width="457" height="287" alt="image" src="https://github.com/user-attachments/assets/890c2fc9-b9c4-4299-996e-5e331d292811" />


Formulas:-
 1. =LEFT(A2,2)
 2. =RIGHT(A2,2)
 3. =MID(A2,4,3)

 **6.Final Outputs:-**

 Product ID	Product Name	Brand Name	Price ($)	Quantity	Category	Price Range	Day	Country Code	Month
28-JAN-US	Laptop	Dell	1000	30	Electronics	High Price	28	US	JAN
15-FEB-US	Sneakers	Nike	80	15	Fashion	Standard Price	15	US	FEB
03-MAR-US	Coffee Maker	Keurig	130	40	Kitchen	Standard Price	03	US	MAR
11-APR-US	Smartphone	Samsung	900	25	Electronics	High Price	11	US	APR
22-MAY-US	Backpack	North Face	70	20	Outdoor	Standard Price	22	US	MAY
07-JUN-UK	Headphones	Sony	200	45	Electronics	Standard Price	07	UK	JUN
19-JUL-UK	T-shirt	Adidas	30	5	Fashion	Standard Price	19	UK	JUL
23-AUG-UK	Blender	Ninja	90	35	Kitchen	Standard Price	23	UK	AUG
05-SEP-UK	Tablet	Apple	500	50	Electronics	High Price	05	UK	SEP
14-OCT-UK	Hiking Boots	Timberland	130	10	Outdoor	Standard Price	14	UK	OCT
17-JUN-IN	Laptop	HP	950	25	Electronics	High Price	17	IN	JUN
25-NOV-AU	Sneakers	Adidas	90	40	Fashion	Standard Price	25	AU	NOV
08-DEC-DE	Coffee Maker	Nespresso	120	35	Kitchen	Standard Price	08	DE	DEC
<img width="1174" height="365" alt="image" src="https://github.com/user-attachments/assets/6ce35588-2e66-4b5e-9cc7-03d9b03fa367" />

S.No	Question	Answer
1	Sum	10100
2	Count	34
3	Average	297.0588235
4	Minimun	30
5	Maximum	1000
6	SumIF	8050
7	CountIF	11
<img width="343" height="209" alt="image" src="https://github.com/user-attachments/assets/36b15fb2-be89-4f5f-b646-67b509cdf4af" />



**Key Learnings**
Through this project, I practiced:

Basic statistical analysis using SUM, COUNT, AVERAGE, MIN, and MAX.
Logical decision-making using IF.
Conditional calculations using SUMIF and COUNTIF.
Text extraction using LEFT, RIGHT, and MID.
Adding calculated columns to an existing dataset.
Applying Excel formulas to a practical product dataset.
Summarizing data to identify useful insights.


## 👤 Author

**Bhavani**

Aspiring Data Analyst | Excel | SQL | Python | Power BI

---
