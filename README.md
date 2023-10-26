# Sentiment-Analysis-Amazon-Fine-Food-Reviews

[Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) of 568,454 food reviews Amazon users left up to October 2012.


**Problem Statement:**

Amazon's vast collection of food reviews influences countless purchasing decisions daily. Manually gauging the sentiment of these numerous reviews is infeasible, requiring an automated solution that can understand nuanced sentiments efficiently.


**Goal:**

To develop an accurate sentiment analysis model for Amazon food reviews using VADER, enhanced with Word2Vec embeddings and logistic regression for prediction of future reviews, ensuring balanced representation through oversampling techniques.


**Methods and Models used:**

- **Vader model:** To label the dataset with appropriate sentiments based on the text reviews.
- **Logistic Regression:** To train the model using the labelled data and predict the sentiment of new unseen text review.
- **Random Oversampling:** To handle the class imbalance.
- **Word2Vec:** To convert review text into meaningful vector representations, enabling the model to capture semantic nuances and relationships between words.

