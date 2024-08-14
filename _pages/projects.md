---
title: "Projects"
layout: splash
permalink: /projects/
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/img/header_2.jpg
  caption: "Photo credit: [Blake Connally on Unsplash](https://unsplash.com/photos/macbook-pro-inside-gray-room-B3l0g6HLxr8)"
intro: 
  - excerpt: "*It takes 10,000 hours of intensive practice to achieve mastery of complex skills and materials, like playing the violin or getting as good as Bill Gates.* — Malcolm Gladwell, Outliers: The Story of Success"

feature_row1:
  - image_path: /assets/img/cnn.jpg
    alt: "Project 1"
    title: "Religious Building Classification with CNN"
    excerpt: "A CNN is built from  scratch to classify various religious buildings, demonstrating how having a good cnn structures can prevent overfitting the data and improving perfomance at the same time."
    url: "https://github.com/edward330176/cnn-religious-building"
    btn_label: "View on Github"
    btn_class: "btn--primary"

feature_row2:
  - image_path: /assets/img/walmart.jpg
    alt: "Project 3"
    title: "Walamrt Sales Forecasting"
    excerpt: "Forceast weekly sales for 45 Walmart stores. Trends and sesaonality are extracted from the time-series data to create meaningful features."
    url: "https://github.com/edward330176/walmart-stores-time-series"
    btn_label: "View on Github"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /assets/img/storeSales.jpg
    alt: "Project 6"
    title: "Store Sales Time Series Forecasting with A Hybrid Model"
    excerpt: "A comprehensive approach to time series forecasting by combining traditional statiscal methods with machine learning techniques."
    url: "https://github.com/edward330176/store-sales-xgboost"
    btn_label: "View on Github"
    btn_class: "btn--primary"

feature_row4:
  - image_path: /assets/img/creditCard.jpg
    alt: "Project 7"
    title: "Predicting Customer Credit Card Churn"
    excerpt: "Customers are at risk of churning from their credit card services. A complete exploratory data analysis and machine learning models are utilized to identify plausible reasons. Two mediums posts are written to complement the github repository."
    url: "https://github.com/edward330176/credit-card-churn"
    btn_label: "View on Github"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}

