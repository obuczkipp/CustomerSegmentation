# Customer Segmentation with R

*Example: K-Means clustering of customers by spending behavior and purchase frequency*

---

## Overview

This project focuses on **customer segmentation** using transactional and behavioral data. The goal is to divide a broad customer base into smaller, meaningful groups that share similar characteristics, enabling:

- Personalized marketing  
- Optimized offers  
- Better business decision-making  

Customer segmentation allows businesses to:

- Understand differences in customer behavior  
- Target marketing campaigns more effectively  
- Improve retention and loyalty  
- Optimize resource allocation and marketing ROI  

By defining **buyer personas** for each cluster, companies can craft tailored strategies for different customer groups.

---

## Methodology

The analysis starts with **exploratory data analysis (EDA):**

- Checking data structure and summary statistics  
- Identifying missing values  
- Visualizing distributions and potential outliers  
- Examining key variables: age, income, spending score, purchase frequency, last purchase amount  

### K-Means Clustering

- Groups customers into clusters based on similarity of features  
- Minimizes the sum of squared Euclidean distances within clusters  
- Efficient for balanced datasets  
- Outputs clusters that are profiled as **buyer personas**  

**Statistical & visualization tools used:**

- Boxplots, histograms, and scatterplots (`ggplot2`, `GGally`)  
- Descriptive statistics (`psych`)  
- Formatted tables (`kableExtra`)  

---

## Results

The segmentation analysis produced **distinct customer clusters**, which can be interpreted as buyer personas, for example:

- **High-value frequent buyers** – loyal customers with high spending scores  
- **Occasional big spenders** – less frequent, but large purchases  
- **Budget-conscious customers** – low spending, price-sensitive  

Profiling clusters enables **tailored marketing strategies**, increasing engagement and conversion.

---

## Tools and Packages

- **R** – statistical computing  
- **dplyr** – data manipulation  
- **ggplot2** – visualization  
- **GGally** – pairwise plots  
- **psych** – descriptive statistics  
- **kableExtra** – table formatting  

---

## Dataset

Publicly available via GitHub:

[Customer Segmentation Data](https://raw.githubusercontent.com/obuczkipp/CustomerSegmentation/main/customer_segmentation_data.csv)

Key features:

- Age, gender, income  
- Spending score and purchase frequency  
- Membership years  
- Preferred product categories  
- Last purchase amount  

---

## Full Report

Complete analysis with code, visualizations, and cluster profiling:

[Customer Segmentation Report on RPubs](https://rpubs.com/peterobuczki/customer_segmentation)
