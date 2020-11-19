# Olist e-commerce Data Analysis

**Lars Tinnefeld**, 2020-11-16

![portrait](https://images.unsplash.com/photo-1522204523234-8729aa6e3d5f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80)

## Objectives
The ultimate goal of the work in this notebook is to extract information which can serve as a base for data driven decisions that could lead to improvement of the business. The data stems from Olist, a Brazilian e-commerce department store (SaaS). In detail, the analysis is applying time series, modeling and regression analysis to reveal and validate trends and patterns in the development of the business. This output may allow projections for a future business model. In addition, a hypothetical extension of the business service will be reviewed. This new business model would include warehousing and logistic services for the shopkeepers. The analysis will therefore be focussed on three points of attention:
- Finding trends in the business
- Prognosis where the business is headed and the validation of this prognosis
- An initial analysis of the SKU- and order profile to identify opportunities for the potential business extension

## About Olist
Olist is for everyone "who wants to sell more and better" and "who wants to attract new customers". As an SaaS business in the e-commerce sector, Olist is an online selling platform for small businesses. On Olist's sign-up page a range of shopkeeper profiles is listed which fits the business model. Clearly, a strong focus is on attracting more customers.

## The data
The provided data set consists of historical order data from 2016 to 2018 and contains 100,000 orders. There are 8 files available. The below data model displays high level the references between these data- and lookup tables. For the project not all data tables will be used. The data was generously provided by Olist under the license CC BY-NC-SA 4.0 and can be found *[here](https://www.kaggle.com/olistbr/brazilian-ecommerce)* in Kaggle.

![Data Structure](https://i.imgur.com/HRhd2Y0.png)
*Data model as provided in Kaggle*

