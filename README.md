Final Project By:

Oluwatoyin Ibinayo- 100939472  
Azmi Shavez- 100938606  
Lorenc Beqiri- 100943621  
Adeniyi Abiodun- 100915263

# SMS Spam Detection

Using SMS text data, this research aims to develop a machine-learning model for spam message detection. It classifies SMS communications as spam or non-spam (ham) using natural language processing (NLP) techniques and a supervised learning framework.

## Dataset

The "SMS Spam Collection" dataset from the UCI Machine Learning Repository was used in this investigation. There are 5,574 SMS messages in all that are categorized as spam or ham. [Link to dataset] (https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) is the location from which you may obtain the dataset.

Two columns make up the dataset file ('sms_spam_dataset.csv'):

'label': Indicates if the message is ham (0) or spam (1).
'text' refers to the actual text contained in the SMS message.

```

## Usage

1. You have the option to download the project files or clone the repository.

2. Transfer the file "sms_spam_dataset.csv" to the project directory.

3. Train and test the spam detection model using the "sms_spam_detection.py" script.

4. After loading the dataset and preprocessing the text input, the script will use the TF-IDF (Term Frequency-Inverse Document Frequency) approach to train a machine learning model.

5. The model will be evaluated on a holdout set after training, and performance measures (accuracy, precision, recall, and F1-score) will be given.

6. Lastly, by modifying the script's 'predict' function, you may use the trained model to predict the spam/ham label of fresh SMS messages.

## Findings:

On the test set, the trained model achieved **accuracy of 97.10%** and **precision of 100%**.



| Metric    | Score   |
| --------- | ------- |
| Accuracy  | 97.10 % |
| Precision | 100 %   |
```
