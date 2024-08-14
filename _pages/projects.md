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
  - excerpt: > 
      "*It takes 10,000 hours of intensive practice to achieve mastery of complex skills and materials, like playing the violin or getting as good as Bill Gates.* — Malcolm Gladwell, Outliers: The Story of Success"

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
  - image_path: /assets/img/project5.jpg
    alt: "Project 5"
    title: "Project 5"
    excerpt: "A brief description of Project 5."
  - image_path: /assets/img/project6.jpg
    alt: "Project 6"
    title: "Project 6"
    excerpt: "A brief description of Project 6."
    url: "#"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: /assets/img/project7.jpg
    alt: "Project 7"
    title: "Project 7"
    excerpt: "A brief description of Project 7."
    url: "#"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row1", type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="center" %}

