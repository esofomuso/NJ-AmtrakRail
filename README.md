# NJ-AmtrakRail
## 1. Introduction
In the modern landscape of transportation and infrastructure optimization, gaining comprehensive insights into the performance of transit systems is of paramount importance. Rail services, such as those offered by NJ Transit and Amtrak, play a significant role in connecting communities and ensuring efficient mobility. However, challenges such as train delays and operational efficiency remain critical areas to address. Uncovering hidden patterns within rail performance data through advanced data analysis techniques presents a promising avenue for enhancing operational strategies and elevating the overall passenger experience.

In this context, the current research embarks on a journey to explore the application of unsupervised learning techniques in dissecting the complexities of NJ Transit and Amtrak rail performance data. By delving into the intricate web of delays, station-related factors, and temporal patterns, this study aims to offer valuable insights that can influence decision-making, resource allocation, and service improvements. The chosen approach of employing clustering methodologies, namely Principal Component Analysis (PCA) with K-means and t-Distributed Stochastic Neighbor Embedding (t-SNE) with Gaussian Mixture Model (GMM), opens doors to unraveling intricate relationships and clusters within the data.

The subsequent sections of this study will delve into the rationale behind dataset selection, the execution of clustering techniques, meticulous data analysis, and the derived implications for rail operations. Through this exploration, we aim to shed light on the intricate fabric of rail performance, contributing to a comprehensive understanding that transcends the surface-level challenges. Ultimately, the findings of this research endeavor have the potential to reshape the way rail systems are managed, optimized, and enhanced for the benefit of both passengers and operators alike.

### 1.1 Research Question
How can clustering techniques be employed to uncover patterns in NJ Transit and Amtrak rail performance data, shedding light on train delays and station-related factors?

### 1.2 Reason for Choosing the Dataset:
The dataset, "NJ Transit + Amtrak (NEC) Rail Performance," was selected for its relevance to modern transportation challenges. By investigating train delays and station-related variables, we can derive insights that may optimize rail operations and enrich the passenger experience. Utilizing unsupervised clustering methods can unearth hidden structures within the data and facilitate strategic decision-making.

### Sub Questions
  1. Which cluster contains the most train delay on Friday?
  2. Which cluster contains the most train delays for the rush hour in the weekday?


## 2. Data
To ensure a robust analysis, we are leveraging the
Dataset: '''[NJ Transit + Amtrak (NEC) Rail Performance | Kaggle](https://www.kaggle.com/pranavbadami/nj-transit-amtrak-nec-performance)'''
from Kaggle.
There was a total of 5 CSV files to containing NJ Transit & Amtrak Rail data. I collected them and stored in a single CVS and Dataset,
titled **"All_NJ_Transit2020_data.csv,"** then used a subset of the data.

### Dataset Highlights:
* Total Records: 965568
* Variables/Columns: 13
### Subset Dataset
* Total Records: 98698
* Variables/Columns: 13
### Key Attributes:
'delay_minutes', 'hour' and 'day'

This data, subset data represents the most recent data that was collected in 2020 for NJ Transit & Amtrak Rail.


## 3. Methodology
1. Data Collection
2. Data Exploration and Feature Selection
3. Apply Unsupervised Learning Methods
  1. Using PCA and K-means to do the clustering (visualizations and many clusters, justify using silhouette scores)
  2. For PCA/K-means (K>= 4), draw the bar graphs to answer the following sub questions:
      1. Which cluster contains the most train delay on Friday?
      2. Which cluster contains the most train delays for the rush hour in the weekday?
  3. Using T-sne and GMM to do the clustering (visualizations and many clusters, justify using silhouette scores)
  4. For T-sne/GMM (K>= 4), draw the bar graphs to answer the following sub questions:
      1. Which cluster contains the most train delay on Friday?
      2. Which cluster contains the most train delays for the rush hour in the weekday?

## 4. Write up analysis and comparison
## 5. Conclusions
