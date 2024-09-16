# Case Study - Fufu Republic
This repository contains the data engineering solution developed for **Fufu Republic**; a popular restaurant chain in Nigeria. 

The project addresses the challenges of inventory management, customer experience, and data-driven decision-making through dimensional modeling.

## Project Overview:
Fufu Republic is a popular restaurant chain in Nigeria with multiple outlets nationwide.

While the core menu is standardized, some items vary by location (e.g., the Agege branch may sell Chinese Rice, while the Lekki branch might not). 

### Dinng Options:
Customers can order
- online through the website or 
- visit outlets for dine-in or take-out.

### Payment Methods:

The restaurant accepts:
- Cash
- Debit card payments via Nomba POS terminals at outlets
- Online payments processed through gateways like Nomba Web Checkout, Paystack Interswitch etc.

### Challenges:
1. **Inventory Management:**
Variations in customer demand and menu items across branches make it challenging to
maintain optimal stock levels.

2. **Customer Experience:**
The restaurant aims to improve the customer experience by offering personalized
promotions based on purchasing behavior.

## Objective:
Fufu Republic wants to leverage data to:

● Understand sales trends across locations, payment methods, and dining options
(dine-in, take-out, online).

● Manage stock levels efficiently, reducing waste and ensuring availability.

● Enhance customer experience by analyzing purchasing habits and tailoring promotions
accordingly.

As a recently hired **data engineer** at Fufu Republic, you have been tasked with developing a dimensional model to address the business's needs for data-driven decision-making.

For this project, you should:

1. Map out the necessary entities ,relationships and constraints: This should be a model (Any degree of abstraction is okay)

2. Create a dimensional model:
    - Identify a business process of your choice
    - List the business question under the business process you selected
    - Identify the grain, dimensions and fact


## Solution to the Case Study

### Business Process ERD Diagram
After analyzing Fufu Republic’s business process, I identified the key tables that capture the details of the operations and designed a dimensional model using a star schema to illustrate how these tables are interconnected.

a. Data Modeling - Overview
<p align="center" style="margin-bottom: 0px !important;">
<img src="https://github.com/Chisomnwa/CDE_Data-Modeling-Assignment/blob/master/fufu_repuplic_data_model_overview.png" width="540" height="540">


b. Dimensional Modeling - the big picture
<p align="center" style="margin-bottom: 0px !important;">
<img src="https://github.com/Chisomnwa/CDE_Data-Modeling-Assignment/blob/master/fufu_republic_dimensional_model.png" width="540" height="540">


This solution with the full details captured in this PowerPoint Presentation [here](https://docs.google.com/presentation/d/1eHlx8JQcEIsJ9wte8s5X0SnhZGBDClDm/edit?usp=sharing&ouid=115975829916748489005&rtpof=true&sd=true) provides a **step-by-step** approach to developing a data modeling strategy that addresses Fufu Republic’s need for data-driven decision-making, focusing on optimizing inventory management, enhancing customer experience, and improving operational insights.