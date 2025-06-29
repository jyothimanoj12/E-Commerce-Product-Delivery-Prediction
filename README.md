# E-Commerce-Product-Delivery-Prediction
# 📦 E-Commerce Product Delivery Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

This project uses machine learning techniques to predict whether a product from an e-commerce company will be delivered on time. It explores how various factors like shipment method, warehouse location, product importance, and discounts impact delivery performance.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [EDA & Preprocessing](#eda--preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [How to Run](#how-to-run)
- [Conclusion](#conclusion)
- [License](#license)

---

## 📊 Project Overview

An international electronics e-commerce company seeks to reduce late deliveries by analyzing customer and shipping data using advanced machine learning. The goal is to build a model that accurately predicts whether a product will be delivered on time.

---

## 📁 Dataset Description

The dataset contains **10,999 records** and **12 features** including the target variable. Below is a summary of key columns:

| Feature                 | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `ID`                   | Unique customer ID                                                          |
| `Warehouse_block`      | Warehouse block (A–E)                                                       |
| `Mode_of_Shipment`     | Shipment mode (Ship, Flight, Road)                                          |
| `Customer_care_calls`  | Number of enquiry calls made by the customer                                |
| `Customer_rating`      | Customer service rating (1 = worst, 5 = best)                               |
| `Cost_of_the_Product`  | Cost of the product (in USD)                                                |
| `Prior_purchases`      | Number of previous purchases by the customer                               |
| `Product_importance`   | Importance level of the product (low, medium, high)                         |
| `Gender`               | Customer gender                                                             |
| `Discount_offered`     | Discount given on the product                                               |
| `Weight_in_gms`        | Product weight in grams
