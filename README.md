# Lazada Sentiment Analysis Project

## Project Overview

This project analyzes customer reviews of the Lazada mobile application collected from the Google Play Store. The goal is to understand user opinions and identify common issues mentioned in reviews by applying Natural Language Processing (NLP) and machine learning techniques.

The analysis focuses on classifying review topics and identifying sentiment (positive, neutral, negative) from user feedback. The results are presented through an interactive Power BI dashboard to help visualize customer opinions and highlight important aspects of the application.

---

## Objectives

* Collect customer reviews from the Lazada mobile application on Google Play Store
* Clean and preprocess Thai text review data
* Explore frequently mentioned words in customer feedback
* Classify reviews into different aspects using machine learning models
* Perform sentiment analysis to identify positive, neutral, and negative opinions
* Visualize insights using an interactive Power BI dashboard

---

## Tools & Technologies

* Python
* Pandas
* Scikit-learn
* Natural Language Processing (NLP)
* Naive Bayes
* Random Forest
* Power BI

---

## Project Workflow

### 1. Data Collection

Customer reviews were collected from the Lazada mobile application on the Google Play Store using Python.

### 2. Data Cleaning & Preprocessing

The collected reviews were processed to prepare them for analysis.

Steps include:

* Removing missing values
* Cleaning Thai text
* Tokenizing review sentences
* Preparing text data for machine learning models

### 3. Text Exploration

Exploratory analysis was performed to identify commonly used words in customer reviews and understand general discussion patterns among users.

### 4. Aspect Classification

Machine learning models were used to classify reviews into different aspects related to the Lazada application, including:

* Store
* System
* Company
* Promotion
* Logistics

The models used include:

* Naive Bayes
* Random Forest

### 5. Sentiment Analysis

Customer reviews were classified into three sentiment categories:

* Positive
* Neutral
* Negative

This helps identify overall user satisfaction and highlight areas where users experience problems.

### 6. Data Visualization

The results of the analysis were visualized using Power BI to provide interactive insights into customer feedback.

---

## Dashboard Features

The Power BI dashboard provides the following insights:

* **Overall Sentiment Distribution**

  * Positive: 38.49%
  * Negative: 28.63%
  * Neutral: 32.88%

* **Aspect-Based Sentiment Analysis**

  * Comparison of positive, neutral, and negative reviews across aspects:

    * Store
    * System
    * Company
    * Promotion
    * Logistics

* **Total Reviews by Aspect**

  * Shows the number of reviews associated with each aspect.

* **Negative Reviews by Aspect**

  * Highlights which aspects receive the highest number of negative feedback.

* **Most Frequently Mentioned Topics**

  * Common topics discussed by users include:

    * ส่วนลด (Discounts)
    * สินค้า (Products)
    * ราคา (Price)

* **Example Customer Reviews**

  * Displays real user comments from the dataset.

* **Interactive Aspect Filter**

  * Allows users to filter and explore sentiment results by specific aspects.

---

## Project Files

* `review_scraper_ipynb.ipynb`
  Python notebook used to scrape Lazada app reviews from Google Play Store.

* `sentiment_analysis.ipynb`
  Contains data cleaning, text processing, aspect classification, and sentiment analysis.

* `lazada30.csv`
  Dataset containing Lazada customer reviews used in the analysis.

* `Lazada_Dashboard.pbix`
  Power BI dashboard used to visualize sentiment analysis results.

* `Lazada_Sentiment_Analysis_Presentation.pdf`
  Presentation slides explaining the project methodology and results.

---

## Key Insights

* Customer feedback shows a mix of positive, neutral, and negative opinions about the Lazada mobile application.
* The **Store** and **System** aspects receive the highest number of reviews.
* Some negative feedback is related to promotions, system issues, and logistics experiences.
* Common topics mentioned by users include discounts, products, and pricing.

---

## Author

This project was developed as part of a university final project in the field of Data Analysis / Data Science.
