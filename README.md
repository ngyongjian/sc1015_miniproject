# Prediction on Severity of Road Accidents

## Repository Description

This repository is submitted to Nanyang Technological University as part of a graded assignment for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on [Severity of Road Accidents in the US](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents). For detailed walkthrough, please view the source code in order from:

1. [Complete Data Cleaning & Visualization - 14042022]()
2. [Data Visualization via Tableau - 07042022]()
3. [Machine Learning 1 - 07042022]()
4. [Machine Learning 2 - 07042022]()
5. [Machine Learning 3 - 15042022]()

## Contributors
Nanyang Technological University School of Computer Science and Engineering
AY2021/22 SC1015 ECAD1 Group 8

- NG YONG JIAN C210057@E.NTU.EDU.SG
- KEVIN YOK KYOK001@E.NTU.EDU.SG
- LIV TAN KER JIN LIVT0001@E.NTU.EDU.SG

## Datasets folder
- us_accident_2016_cleaned: cleaned 2016 dataset with 20 columns, no NULL, removed outliers
- us_16_acd_ohe: us_accident_2016_cleaned with categoriacal variables being one hot encoded  
- us_16_acd_ohe_up: us_16_acd_ohe with severity 3 and 4 upsampled

## Problem Definition
- How do different factors affect severity of road accidents in the US?
- Which model would be the best to predict severity of accidents in the US?

## Models Used
1. Ordinary Least Squares Linear Regression(OLS)
2. OneHotEncoder
3. Grid Search Cross-Validation
4. Decision Tree Classifier
5. Random Forest Classifier
6. Balanced Bagging Classifier
7. Balanced Random Forest Classifier
8. Logistic Regression
9. Eli 5

## Conclusion
- Severity and distance a positive relationship.
- No linear relationship between the numerical variables and distance.
- Best prediction model was built using imblearn.
- Most accidents happen during peak hours on weekdays, especially in California, when the car is on the right side of the street, and when there is no crossing, no junction, and no traffic signals. Perhaps this can be improved by reducing the number of cars allowed on the street and to have more traffic signals.

## What did we learn from this project?
- Scikit-learn:
  - Regression: OLS Regression
  - Classification: Decision Tree Classifier, Random Forest Classifier
- ImbLearn:
  - Classification: Balanced Bagging Classifier, Balanced Random Forest Classifier
- Others:
  - Utility models: Simple Imputer, Standard Scalar, One Hot Encoder, Resample, Grid Search CV, Eli5
- Tableu:
  - Visualization: Tableu desktop, Tableu public

## References
- Moosavi, S., Mohammad, S., Srinivasan, P., & Rajiv, R. (2019). A Countrywide Traffic Accident Dataset. https://www.kaggle.com/sobhanmoosavi/us-accidents ​
- Moosavi, S., Mohammad, S., Srinivasan, P., Radu, T., & Rajiv, R. (2019). Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights. In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019. ​
- Road Safety Facts — Association for Safe International Road Travel. (2022, January 10). Association for Safe International Road Travel. https://www.asirt.org/safe-travel/road-safety-facts/ ​
- Pedregosa et al. (2011). Scikit-learn: Machine Learning in Python. JMLR 12, pp. 2825-2830.‌​
- What is Cross Validation in Machine Learning? Types of Cross Validation. (2020, September 24). GreatLearning Blog: Free Resources What Matters to Shape Your Career! https://www.mygreatlearning.com/blog/cross-validation/ ​
- Imbalanced Data  |  Data Preparation and Feature Engineering for Machine Learning  |  Google Developers. (2021). Google Developers. https://developers.google.com/machine-learning/data-prep/construct/sampling-splitting/imbalanced-data ​
- Bento, C. (2021, June 28). Decision Tree Classifier explained in real-life: picking a vacation destination. Medium; Towards Data Science. https://towardsdatascience.com/decision-tree-classifier-explained-in-real-life-picking-a-vacation-destination-6226b2b60575 ​
- Yadav, D. (2019, December 6). Categorical encoding using Label-Encoding and One-Hot-Encoder. Medium; Towards Data Science. https://towardsdatascience.com/categorical-encoding-using-label-encoding-and-one-hot-encoder-911ef77fb5bd ​
- Lemaître, G., Nogueira, F., & Aridas, C. K. (2017). Imbalanced-learn: A Python Toolbox to Tackle the Curse of Imbalanced Datasets in Machine Learning. Journal of Machine Learning Research, 18(17), 1–5. https://jmlr.org/papers/v18/16-365.html ​
- IBM Cloud Education. (2021, May 11). What is Bagging? Ibm.com. https://www.ibm.com/cloud/learn/bagging#:~:text=Bagging%2C%20also%20known%20as%20bootstrap,be%20chosen%20more%20than%20once ​
- python-visualization. (2020). Folium. https://python-visualization.github.io/folium/. ​
- McKinney, W., & others. (2010). Data structures for statistical computing in python. In Proceedings of the 9th Python in Science Conference (Vol. 445, pp. 51–56).​
