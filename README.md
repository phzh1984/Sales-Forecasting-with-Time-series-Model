# Sales-Forecasting-with-Time-series-Model

Overview

This repository contains code and data for a sales forecasting project aimed at predicting the total number of products sold for shops and products in November 2015, based on historical sales data from January 2013 to October 2015.

File Descriptions

sales_train.csv: The training set containing daily historical data from January 2013 to October 2015.

test.csv: The test set for which predictions need to be made for November 2015.

items.csv: Supplemental information about the items/products.

item_categories.csv: Supplemental information about the item categories.

shops.csv: Supplemental information about the shops.

Data Fields

ID: An ID representing a (Shop, Item) tuple within the test set.

shop_id: Unique identifier of a shop.

item_id: Unique identifier of a product.

item_category_id: Unique identifier of the item category.

item_cnt_day: Number of products sold per day. Prediction involves forecasting a monthly amount of this measure.

item_price: Current price of an item.

date: Date in format dd/mm/yyyy.

date_block_num: Consecutive month number for convenience (e.g., January 2013 is 0, February 2013 is 1,..., October 2015 is 33).

item_name: Name of the item.

shop_name: Name of the shop.

item_category_name: Name of the item category.

Task

The task involves creating a robust model capable of forecasting the total number of products sold for the test set, considering that the list of shops and products may slightly change every month.
