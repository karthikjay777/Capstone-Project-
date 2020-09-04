# Capstone-Project-
BACK-ORDER PREDICTION

Product Back orders 

What is a backorder? : 
A customer order that has not been fulfilled. 
A backorder generally indicates that customer demand for a product or service exceeds a company’s capacity to supply it. 
Total backorders, also known as backlog, may be expressed in terms of units or dollar amount. 
Product backorder may be the result of strong sales performance (e.g. the product is in such high demand that production cannot keep up with sales). 
However, backorders can upset consumers, lead to canceled orders and decreased customer loyalty. 
Companies want to avoid backorders, but also avoid overstocking every product (leading to higher inventory costs).
Machine learning can identify patterns related to backorders before customers order. 
Production can then adjust to minimize delays while customer service can provide accurate dates to keep customers informed and happy. 
The predictive analytics approach enables the maximum product to get in the hands of customers at the lowest cost to the organization.

DATA : 
The data file contains the historical data for the 8 weeks prior to the week we are trying to predict. 
The data were taken as weekly snapshots at the start of each week. The target (or response) is the went_on_backorder variable.
To model and predict the target, we’ll use the other features, which include:

sku – Random ID for the product national_inv 

Current inventory level for the part lead_time 

Transit time for product (if available) in_transit_qty 

Amount of product in transit from source

forecast_3_month – Forecast sales for the next 3 months 

forecast_6_month – Forecast sales for the next 6 months 

forecast_9_month – Forecast sales for the next 9 months 

sales_1_month – Sales quantity for the prior 1 month time period 

sales_3_month – Sales quantity for the prior 3 month time period 

sales_6_month – Sales quantity for the prior 6 month time period 

sales_9_month – Sales quantity for the prior 9 month time period 

min_bank – Minimum recommend amount to stock 

potential_issue – Source issue for part identified 

pieces_past_due – Parts overdue from source 

perf_6_month_avg – Source performance for prior 6 month period 

perf_12_month_avg – Source performance for prior 12 month period 

local_bo_qty – Amount of stock orders overdue 

deck_risk – Part risk flag 

oe_constraint – Part risk flag 

ppap_risk – Part risk flag 

stop_auto_buy – Part risk flag 

rev_stop – Part risk flag 

went_on_backorder – Product actually went on backorder. This is the target value.
