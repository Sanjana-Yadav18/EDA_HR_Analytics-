# EDA_HR_Analytics-

# Project Overview
The EDA_HR_Analytics project focuses on performing exploratory data analysis (EDA) on a dataset related to customer interactions and product pitches. The primary goal is to uncover insights and patterns that can help the business optimize its sales strategies, understand customer behavior, and improve overall marketing efficiency.

The dataset contains various demographic and behavioral attributes of customers, alongside details of the product pitch and their responses to it. This analysis aims to assist in decision-making for product targeting, marketing efforts, and customer segmentation.

# Dataset
The dataset consists of 20 columns that provide details about customer demographics, product preferences, and engagement with the company's sales process:

CustomerID: Unique identifier for each customer.
ProdTaken: Indicator of whether the customer took the product (1 = Yes, 0 = No).
Age: Age of the customer.
TypeofContact: Method of contact (e.g., in-person, phone).
CityTier: Tier of the city in which the customer resides (1 = High, 2 = Medium, 3 = Low).
DurationOfPitch: Time (in minutes) spent on the product pitch.
Occupation: Customer's occupation (e.g., salaried, businessman).
Gender: Customer's gender (Male, Female).
NumberOfPersonVisiting: Number of people accompanying the customer.
NumberOfFollowups: Number of follow-up interactions with the customer.
ProductPitched: The product presented to the customer.
PreferredPropertyStar: Customer's preference for property star rating.
MaritalStatus: Customer's marital status (Married, Single, etc.).
NumberOfTrips: Number of trips the customer has made in the past.
Passport: Whether the customer has a valid passport (1 = Yes, 0 = No).
PitchSatisfactionScore: Customer's satisfaction score with the pitch (on a scale of 1-5).
OwnCar: Whether the customer owns a car (1 = Yes, 0 = No).
NumberOfChildrenVisiting: Number of children accompanying the customer.
Designation: Customer's designation (e.g., Executive, Manager).
MonthlyIncome: Customer's monthly income.


# Project Objectives
The key objectives of the project are as follows:

Customer Segmentation: Segment customers based on various factors such as age, income, occupation, and product interest to understand key customer groups.
Product Pitch Performance: Analyze the relationship between pitch satisfaction score, duration of the pitch, and whether the product was taken.
Contact Method Efficiency: Evaluate the impact of contact methods (TypeofContact) on the likelihood of product uptake (ProdTaken).
City Tier Analysis: Assess how customer behavior varies across different city tiers in terms of product interest, income, and occupation.
Demographic Trends: Identify trends based on customer demographics (age, marital status, gender, etc.) that influence product interest and follow-up success.
Predictive Insights: Use the insights gained to make data-driven recommendations for improving sales efficiency and customer engagement.


# Analysis Summary
Key findings from the exploratory data analysis include:

Customer Segments: Certain age groups and occupations show higher product uptake, indicating potential for targeted marketing.
Pitch Duration: There is a correlation between longer pitch durations and higher satisfaction scores, though this does not always translate into product uptake.
Follow-up Impact: Customers with more follow-ups are more likely to take the product, suggesting that persistence in sales efforts pays off.
Income Influence: Higher-income customers tend to prefer higher-tier properties and have a higher probability of taking the product.


# Tools and Technologies Used
Python: For data manipulation and analysis.
Pandas: For data cleaning and transformation.
Seaborn & Matplotlib: For data visualization.
Jupyter Notebook: For running code and documenting insights.

