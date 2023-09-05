
# Capstone Project
## Customer Segmentation for Arvato Financial Services

## Project overview
Improving the efficiency to target the group of potential customers and concentrating valuable resources on the right individuals is the challenge for business and all industries. In this article, unsupervised and supervised machine learning algorithms are described to analyze  demographics data for customers of a mail-order sales company. The are two main tasks in the project:

1. Segment the datasets into groups to realize features of existing customers and differences to general population.

2. Build a forecasting model to estimate and recognize promising customer response for a marketing campaign

## Introduction
In the Jupyternote book, the procedure is basically spereated into five parts listed below:

* Know the data: get to understand the dataset and explore which sections of the datasets need to be wrangled.

* Data Wrangling: Based on the findings above, apply functions to clean the data, and explain reasons to cope with the features that are uncenessary.

* Customer Segmentation Report: the method of K-modes is used as an unsupervised learning technnique in the project, and the reason of using this techique is also mentioned. According to the result of clustering, 5 clusters could be formed, and the critical features of the interested cluster are presented.

* Supervised Learning Model: The true meaning behind the quantitavie values of numerous features is actually representation of each categories. In other words, the major task of this project is to cope with complex features of classification. As a result, sevearl classification algorithms are utilized, and metrics of evaluation is also introduced. Finally, the result of prediction is conveyed.

* Conclusion: summarize the findings, challenge, and the limitation of my work.

The complete report can be found in this <a href=https://medium.com/@johnma19821105/save-your-resource-and-effectively-target-your-client-eba0096c24c1>blogpost</a>.

## Data

1. **"Udacity_AZDIAS_052018.csv"** - Demographics data of the general population inGermany: 891221 rows x 366 columns.
2. **"Udacity_CUSTOMERS_052018.csv"** - Demographics data for customers of a mail-order company: 191652 rows x 369 columns.
3. **"Udacity_MAILOUT_052018_train.csv"** - Demographics data of individuals who were targets of a marketing campaign; 42962 rows x 367 columns.
4. **"Udacity_MAILOUT_052018_test.csv"** - Demographics data of individuals who were targets of a marketing campaign; 42833 rows x 366 columns

Furthermore, there are 2 more excel sheets to describe features:
1. **"DIAS Attributes - Values 2017"**- Explanations of encoding values
2. **"DIAS Information Levels - Attributes 2017"** - Disclose the meaning of the attributes


## Libraries

1. Python3
2. Machine Learning Libraries: NumPy, Pandas, Scikit-Learn
3. Visualization: Matplotlib,Seaborn
4. K-Modes

Please refer to 'requirement.txt' for details

## License
**Due to the privacy agreement with Arvato Financial Services, the datasets and supplementary documents listed above are not publicly shared.**

## Acknowledgements
* <a href=https://www.analyticsvidhya.com/blog/2021/06/kmodes-clustering-algorithm-for-categorical-data/>KModes Clustering Algorithm for Categorical data</a>
* <a href=https://www.geeksforgeeks.org/k-mode-clustering-in-python/> K-Modes Clustering in Python</a>
* <a href=https://amva4newphysics.wordpress.com/2016/10/26/into-the-world-of-clustering-algorithms-k-means-k-modes-and-k-prototypes/>Into the world of clustering algorithms: k-means, k-modes and k-prototypes</a>
* <a href=https://www.analyticsvidhya.com/blog/2016/02/complete-guide-parameter-tuning-gradient-boosting-gbm-python/>Complete Machine Learning Guide to Parameter Tuning in Gradient Boosting (GBM) in Python</a>
* <a href=https://www.kaggle.com/code/juanmah/tactic-03-hyperparameter-optimization-adaboost>Tactic 03. Hyperparameter optimization. Adaboost</a>
