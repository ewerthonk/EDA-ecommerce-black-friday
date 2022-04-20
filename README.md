# 🔬 Exploratory Data Analysis: E-commerce sales during Black Friday

<div align="center"><img src="./images/readme_image.png" width="500"></div>

<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white">    
<img src="https://img.shields.io/badge/seaborn-add8e6?style=for-the-badge&logo=python&logoColor=333333">    
</div>

## 👨🏻‍🏫 Description

Exploratory Data Analysis on a dataset containing Black Friday sales information of an E-Commerce.

This EDA is restricted to **visual analysis tools** only. The challenge was to produce insights only by visualization.

**Questions to be answered by the EDA:**

- Does the marital status influences in the Average Purchase Value?
- Does the marital status influences in the Purchase Category?
- If one wants to sell more products of category 14, should one invest more in publicity for marital status 0 or 1?
- Which variables are correlated to the value of the purchase?

**Dataset:** 

| Column                 | Description                                               |
|:-----------------------|:----------------------------------------------------------|
| User_ID                | User ID (key)                                             |
| Product_ID             | Product ID (key)                                          |
| Gender                 | User gender                                               |
| Age                    | Interval range of user age                                |
| Occupation             | Occupation (masked)                                       |
| City_Category          | City Size Category (A, B, C)                              |
| StayInCurrentCityYears | Number of Years the user is living in the current city    |
| Marital_Status         | Marital status (Single or Married)                        |
| Product_Category_1     | Product category (Masked)                                 |
| Product_Category_2     | A 2nd possible product category (Masked)                  |
| Product_Category_3     | A 3rd possible product category (Masked)                  |
| Purchase               | Purchase value                                            |