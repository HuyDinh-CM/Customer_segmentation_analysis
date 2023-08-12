# Customer segmentation analysis

<div align="center">
  <img src="https://www.netscribes.com/wp-content/uploads/2022/03/Customer-segmentation-strategy.jpg" alt="Customer segmentation analysis">
</div>

## The goal of the project
This project focuses on performing customer segmentation based on a dataset named "Raw_data.xlsx." This data set includes information related to transactions, customer information, customer addresses, and new customer lists.

The project's primary goal is to build RFM (Recency, Frequency, Monetary) model to segment customers based on their shopping behaviour, thereby better understanding how customers interact with the company and creating similar customer groups.

## Dataset
My dataset consists of Excel sheets containing information about an automobile bike company operating in the Australian market. The data in the file "Raw_data.xlsx" is divided into the following sheets:
- *Transactions:* Contains information about purchase transactions.
- *CustomerDemographic:* Contains information about the customer.
- *CustomerAddress:* Contains information about the customer's address.
- *NewCustomerList:* Contains information about the new customer list.

## Tools and Libraries
The project is implemented using Google Colab, a browser-based development environment, and uses Python libraries such as:
- *Pandas:* Processing and analyzing data.
- *Numpy:* Arithmetic and statistical operations.
- *Matplotlib and Seaborn:* Plotting and visualizing data.
- *Math:* Essential math calculations.

## Analysis Approach
- During the Analysis Approach phase, using Python and Google Colab, I explored and cleaned the data in the dataset. I exported the correct data set by examining and processing missing, null, duplicates, and data inconsistency values. I prepared it for the following Customer Segmentation Analysis project analysis steps.
- Check and clean data from Transactions, CustomerDemographic, and CustomerAddress sheets, and then organize relevant information to perform RFM analysis.
- Data processing for the NewCustomerList sheet is similar to the previous steps.
- Create a .ipynb file named "RFM_model_analysis.ipynb" to perform customer segmentation and compare their characteristics with the new list of customers from the NewCustomerList sheet.
- The project has successfully implemented customer segmentation using the RFM model. Customer groups were created based on their shopping behaviour.
- The comparison with the new customer list from the NewCustomerList sheet helps better understand the nature of the customer groups and how they might interact with the company.
