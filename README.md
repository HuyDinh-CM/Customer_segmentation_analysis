# Customer segmentation analysis

<div align="center">
  <img src="https://www.netscribes.com/wp-content/uploads/2022/03/Customer-segmentation-strategy.jpg" alt="Customer segmentation analysis">
</div>

## The goal of the project
The project objective is to analyze and segment the automobile bike company customers in Australia. Using Python for data cleaning and Tableau for visualization, we apply the RFM model to optimize marketing strategy and improve customer experience.
## Dataset
My dataset consists of Excel sheets containing information about a bicycle company operating in the Australian market. Here is the description of the sheets in the dataset:
### Transaction: 
This is a record sheet containing information about customer purchases. Columns can include information about transaction ID, transaction date, customer ID, purchased product/service, quantity, price, and other transaction details.
### New Customer: 
They are used to store information about the company's new customers. It contains the customer ID, name, email address, phone number, and joining date.
### Customer Demographic: 
Contains information about customer characteristics like gender, date of birth, and occupation. This helps to segment customers by groups of similar nature.
### Address: 
Contains information about the customer's address, including street, city, county, zip code, and other address details.
The data in the dataset is fundamental in understanding customer buying behavior and creating customer segments to apply the RFM model. Based on the information in the sheets, you can analyze each customer's shopping pattern, purchase frequency, and monetary value to make appropriate strategies and business development directions.

## Analysis Approach
During the Analysis Approach phase, using Python and Google Colab, I explored and cleaned the data in the dataset. I exported the correct data set by examining and processing missing, null, duplicates, and data inconsistency values. I prepared it for the following Customer Segmentation Analysis project analysis steps.
### customer_demographic:
When the Date of Birth is Null, tenure is also Null. Therefore, null terms are also removed after removing null DOBs from the data frame.
