# Spam-Mail
An ML model to classify the mail as spam or not

# Description #

 * Given the spam mails dataset. The objective is to determine whether the given mail is spam or not.
 * The Dataset contains spam and ham mails, which can be used to train the ML model.

# My Procedure #

## Cleaning
The dataset didn't have any inconsistent values, hence there was no need for cleaning
  
## Data Preprocessing
Implemented the BOW Model, to tokenize and clean every sentence, with the help of PorterStemmer from ntlk module. This helps to extract features from text to use in modelling.

## Model Training
* Used the Random Forest Classifer for the ML Model.
* The model was implemented and compared different estimators to choose the best accuracy possible for the prediction.
* In general, it can be seen that the model achieved an accuracy of 97%.
