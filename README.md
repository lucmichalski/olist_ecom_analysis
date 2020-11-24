# Olist e-commerce Data Analysis

**Lars Tinnefeld**, 2020-11-23

![portrait](https://images.unsplash.com/photo-1522204523234-8729aa6e3d5f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80)

## About Olist's Business
Olist is for everyone "who wants to sell more and better" and "who wants to attract new customers". As an business in the e-commerce sector, Olist is an online selling platform for small businesses. On Olist's sign-up page a range of shopkeeper profiles is listed which fits the business model. A strong focus is on attracting more customers through a larger market presence. A user satisfaction report helps to address areas of attention. Olist therefore acts as a service provider which is managing the sales process for the shopkeepers. Olist doen't own any of the offered products and is also not managing shipping or inventory.

## Objectives and Motivation
The goal of the analysis is to extract information that supports Olist's business objectives. These objectives are: Attracting more shopkeepers by enhancing the service and attacting more end-customers through broader product spectrum and higher satisfaction. The analysis is part of a business case that is looking into expanding Olist's service to also include logistics and warehousing, something Olist is not offering at the moment.
In detail, the analysis is first investigating correlations in the order data with the goal to find potentially important inssights that can be integrated into the enhanced service. Secondly, the analysis investigates how the business is developing and how dynamic it changes from day to day. This includes also to find extreme events. Thirdly, a prediction about the size of the business for a future state needs to be modeled. This all is part of a selection- and definition process for the potential logistic concept, and eventually a business case. Questions that will be answered in this analysis are in detail:
- Are there correlations and patterns in the data which are important for the concept?
- What is the general business trend?
- How dynamic is the operation and are there extreme events which impact logistic process?
- What does the prediction say about the business in two years?

## Approach
Success criteria for this analysis stage is to answer the above questions with the available data and information. To archive this the following steps and techniques are applied:
- Data import and wrangling
- Exploratory Data Analysis
- Time Series Visualization
- Logistic Regression

## The data
The provided data set consists of historical order data from 2016 to 2018 and contains 100,000 orders. There are 8 files available. The below data model displays high level the references between these data- and lookup tables. For the project not all data tables will be used. The data was generously provided by Olist under the license CC BY-NC-SA 4.0 and can be found *[here](https://www.kaggle.com/olistbr/brazilian-ecommerce)* in Kaggle.
For the current analysis following data files were used:
- olist_orders_dataset.csv: Contains the orders with order-id, delivery time stamps, the order status and customer-id
- olist_order_items_dataset.csv: Contains the details of the orders with order-id, product-id, seller-id, price, freight cost and shipping limit date
- olist_products_dataset.csv: Contains the details of the products with product-id, category, product name, name length, available photos, dimensions and weight

![Data Structure](https://i.imgur.com/HRhd2Y0.png)
*Data model as provided in Kaggle*

## Approach and used libraries
- Data import and wrangling (Python, Pandas, Numpy)
- Exploratory Data Analysis (Python, Pandas, Seaborn, Matplotlib)
- Time Series visualizations (Python, Pandas, Seaborn, Matplotlib)
- Logistic Regression (Python, Pandas, Seaborn, Matplotlib, Sklearn)

## Brief conclusion
The business is growing and the day-to-day volume is fluctuating very dynamically. Black Friday is a major event for the business. The prognosis is predicting with some error margin that in beginning 2020 in average 500 units per day will be sold. "Health and Beauty" and "Gift Watches" are key categories in the product mix. Delivery times for expensive products seem to be somewhat important for shopkeepers and customers. A final conclusion about the extension of the business model is outstanding due to more required concept selection steps, but initial results already show that a highly automated system would not be a good fit.
