# FLO Client Segmentation via Unsupervised Learning

## Business Problem

FLO wants to segment its customers and develop marketing strategies based on these segments. For this purpose, customer behaviours will be identified, and groups will be created based on the clustering of these behaviours.


<img width="850" alt="Screenshot 2023-07-11 at 12 01 48 AM" src="https://github.com/sametaydn/FLO_Unsupervised_Learning/assets/53154449/99aeb77d-8f89-4b85-a6aa-c2ddb2087d33">


## Dataset Story

The dataset consists of information derived from the past shopping behaviours of customers who made OmniChannel purchases (both online and offline) from FLO between the years 2020 and 2021.

| Column                             | Description                                                                       |
|------------------------------------|-----------------------------------------------------------------------------------|
| master_id                          | Unique customer number                                                            |
| order_channel                      | Channel used for the purchase on the platform (Android, iOS, Desktop, Mobile)     |
| last_order_channel                 | Channel used for the most recent purchase                                         |
| first_order_date                   | Date of the customer's first purchase                                             |
| last_order_date                    | Date of the customer's most recent purchase                                       |
| last_order_date_online             | Date of the customer's most recent online platform purchase                       |
| last_order_date_offline            | Date of the customer's most recent offline platform purchase                      |
| order_num_total_ever_online        | Total number of purchases made by the customer on the online platform             |
| order_num_total_ever_offline       | Total number of purchases made by the customer offline                             |
| customer_value_total_ever_offline  | Total amount spent by the customer on offline purchases                           |
| customer_value_total_ever_online   | Total amount spent by the customer on online purchases                            |
| interested_in_categories_12        | List of categories the customer has made purchases from in the last 12 months     |
