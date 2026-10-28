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

<img width="391" height="183" alt="image" src="https://github.com/user-attachments/assets/a044fc21-33d8-424e-9d1d-6318b5ca4d2f" />

****1.  SUM, COUNT, and AVERAGE:-**
Perform basic calculations using Excel functions.
•	Sum – Calculate the total price of the all the Products
•	Count – Calculating the count of products exists in the dataset
•	Average – Calculating average price of the product.

<img width="343" height="105" alt="image" src="https://github.com/user-attachments/assets/b7257bac-5df6-4fd9-94c3-4e94f6e132df" />

Formulas:-
1. =SUM(D2:D35)
2. =COUNTA(D2:D35)
3. =AVERAGE(D2:D35)

**2.	Minimum and Maximum Values:-**

•	Minimum – Finding the minimum price of the product
•	Maximum  - Finding the maximum price of the product

<img width="343" height="79" alt="image" src="https://github.com/user-attachments/assets/b60507ed-345a-4f78-bdf7-85cf17d8579f" />

Formulas:-
4. =MIN(D2:D35)
5. =MAX(D2:D35)

**3.	Logical Function – IF:-**

•	Crating a new column as Price Range and,
•	Using IF function classified Price>=500 as Highprice and Price<500 as Standard Price

<img width="457" height="235" alt="image" src="https://github.com/user-attachments/assets/336adc2d-b804-44a0-b09c-945583ed3781" />

Formulas:-
=IF(D2>=500,"High Price","Standard Price")

**4.	Conditional Functions – SUMIF and COUNTIF**:-

•	SUMIF - calculating the total price of products in the
Electronics category.
•	COUNTIF - determining the number of products with a price
less than $100.

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

<img width="457" height="287" alt="image" src="https://github.com/user-attachments/assets/890c2fc9-b9c4-4299-996e-5e331d292811" />

Formulas:-
 1. =LEFT(A2,2)
 2. =RIGHT(A2,2)
 3. =MID(A2,4,3)

 **6.Final Outputs:-**

<img width="1174" height="365" alt="image" src="https://github.com/user-attachments/assets/6ce35588-2e66-4b5e-9cc7-03d9b03fa367" />

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
