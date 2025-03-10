# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME: JAKKOJU MANO TEJ

INTERN_ID:CT6WUBZ

DOMAIN:PYTHON

DURATION: 6 WEEKS

MENTOR:NEELA SANTHOSH KUMAR

Machine learning model implementation involves several key steps: data collection, preprocessing, feature extraction, model selection, training, evaluation, and deployment. In this project, we implemented a spam detection model using Scikit-Learn.

First, we loaded the SMS Spam Collection dataset, which contains labeled messages as "spam" or "ham" (non-spam). We then preprocessed the data by converting labels into binary values (0 for ham, 1 for spam) and splitting it into training and testing sets. Next, we applied feature extraction using the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer to convert text messages into numerical representations.

For model selection, we chose the Naïve Bayes classifier, which is well-suited for text classification tasks. The model was trained using the processed training data and then tested on unseen messages. To evaluate performance, we calculated accuracy, precision, recall, and F1-score, and visualized the confusion matrix.

The results showed that the model effectively distinguishes spam from non-spam messages. This approach can be extended to other text classification tasks, such as sentiment analysis and fake news detection.

OUTPUT:![Image](https://github.com/user-attachments/assets/ce554aa7-7f75-48ac-a48d-14c4c4cadb07)
