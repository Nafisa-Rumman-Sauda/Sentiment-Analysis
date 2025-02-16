# Sentiment Analysis Using Machine Learning

## Overview

This project performs sentiment analysis on Twitter data using machine learning techniques. Specifically, it focuses on classifying tweets into positive, negative, or neutral sentiments based on the text of customer reviews for six U.S. airlines. The primary goal is to predict and categorize sentiment polarity using various machine learning algorithms including Random Forest (RF), K-Nearest Neighbors (KNN), Logistic Regression (LR), Decision Tree (DT), and Support Vector Classifier (SVC).

## Keywords

Sentiment Analysis, Machine Learning, Tokenization, TensorFlow, Tweet, NLP (Natural Language Processing), Random Forest (RF), K-Nearest Neighbors (KNN), Logistic Regression (LR), Decision Tree (DT), Support Vector Classifier (SVC).

## Project Objective

- Analyze Twitter data from February 2015 for six U.S.-based airlines.
- Categorize tweets into positive, negative, or neutral sentiments.
- Perform sentiment analysis on reviews at the document level (i.e., tweet level).

## Dataset

The dataset used is "twitter-airline-sentiment," containing a total of 14,640 records with labeled sentiments (positive, negative, or neutral). The data includes tweets from six U.S.-based airlines from February 2015.

### Data Collection
- Twitter data related to customer feedback on six U.S. airline carriers was collected for analysis.

### Data Preprocessing
- The text data undergoes tokenization, cleaning, and conversion to numeric form for machine learning processing.
- Word embeddings are used for preprocessing, converting text data into vectors that can be understood by machine learning models.
- 
![Image](https://github.com/user-attachments/assets/7c29e8bd-9716-4da3-82ac-ab0118350633)


![Image](https://github.com/user-attachments/assets/447d5e97-77d8-4ead-b7fb-fe79dec60405)

  

## Methodology

### Classification Techniques
1. **Random Forest (RF)**: An ensemble method based on decision trees, suitable for handling large datasets and performing feature importance evaluation.
2. **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm that classifies based on the majority vote of neighbors.
3. **Logistic Regression (LR)**: A probabilistic model that predicts sentiment based on the logistic function.
4. **Decision Tree (DT)**: A tree-like structure used for classification by making decisions based on attribute tests.
5. **Support Vector Classifier (SVC)**: A linear classifier that divides data points into different categories by finding a hyperplane that maximizes margin between the classes.

### Data Preprocessing Steps:
1. Tokenization: Breaking text into individual words/tokens.
2. Removal of stop words and special characters.
3. Conversion of categorical sentiment labels into numeric form.
4. Padding to ensure equal-length sequences for all data points.

## Results

### Performance Metrics
- **Random Forest** achieved the highest accuracy (81%).
- **Decision Tree** and **Support Vector Classifier** performed well with accuracies of 76% and 74%, respectively.
- **Logistic Regression** and **K-Nearest Neighbors** had the lowest accuracy among the classifiers used.

### Graphs & Visualizations:
- Accuracy vs. Classifier
- Training and Test Loss/Accuracy Graphs

  
![Image](https://github.com/user-attachments/assets/b4959dd1-ae73-4546-bb85-5b4408858388)

![Image](https://github.com/user-attachments/assets/c4e7cca5-149f-4f39-87aa-e95c23f2cef0)


### Experiment Outcomes:
- Random Forest proved to be the most reliable classifier with the highest accuracy and robustness.
- The system effectively classified customer sentiment, providing valuable insights into customer feedback for business decision-making.


![Image](https://github.com/user-attachments/assets/732551a8-f864-45c5-bf58-a856458a1277)


## Future Work

- **Enhance model performance** by addressing class imbalance in the dataset.
- **Develop a web-based application** to allow real-time sentiment analysis of customer reviews.
- **Support multiple languages** by adapting the model for multilingual sentiment analysis.
- **Explore deeper neural network models** (e.g., deep learning) to improve accuracy further.

## Conclusion

This project successfully applies machine learning techniques to perform sentiment analysis on Twitter data, offering insights into customer opinions on airline services. The Random Forest model demonstrated the best performance among the algorithms tested.

## References

- [1] Vishal A. Kharde, S.S. Sonawane, "Sentiment Analysis of Twitter Data," International Journal of Computer Applications, 2016.
- [2] Neha Upadhyay et al., "Sentiment Analysis on Twitter by using Machine Learning Technique," IJRASET, 2016.
- [3] Arockia Xavier Annie et al., "Sentiment Analysis Applied to Airline Feedback to Boost Customer's Endearment," MSIG, 2015.
- [4] Yun Wan, Dr. Qigang Gao, "An Ensemble Sentiment Classification System of Twitter Data for Airline Services Analysis," IEEE, 2015.

---
