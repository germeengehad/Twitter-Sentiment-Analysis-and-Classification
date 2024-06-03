# Twitter Sentiment Analysis And Classification : Project Overview
 ![Image](https://github.com/germeengehad/Twitter-Sentiment-Analysis-and-Classification/blob/main/image.jpg)

 - This project aims to analyze and classify a dataset of tweets into Positive, Negative, and Neutral classes using various models, including RNN, LSTM, SVM, and Naive Bayes.

- In this project, I decided to upload the dataset from Kaggle. After that, I applied Exploratory Data Analysis (EDA) and data preprocessing. I used text embedding for the RNN and LSTM models, and TF-IDF vectorization for the SVM and Naive Bayes models. Finally, I built and trained the models. 

# The Data Set
- There are three classes in this dataset: Positive, Negative and Neutral. We regard messages that are not relevant to the entity (i.e. Irrelevant) as Neutral , there where 74996 row in the csv file of the dataset it include four coulmns unnamed but i renamed them to  id information labels text and i concatenate data of train and validation files togther 

# EDA And Data Preprossing 
 ![Image](https://github.com/germeengehad/Twitter-Sentiment-Analysis-and-Classification/blob/main/download%20(5).png)

- Data Preprossing:
  - I removed unnecessary columns (id, information) to focus solely on the tweet text.
  - I creat a  function to :
     - Remove Extra Whitespace
     - Remove Special Characters
     - Remove Single Characters
     - Remove Non-Alphabetical Characters
     - Convert to Lowercase
     - Tokenize Text
     - Lemmatize Words
     - Remove Stop Words
     - Remove Short Words
     - Remove Duplicates and Maintain Order
   - I split the data into X and Y (labels)
   - I applied oversampling to handle the unbalanced data.
   - I split the data into train and test sets, with 1% of the dataset used for testing
     
  # Model Performance
   ## RNN Model
  ![Image](https://github.com/germeengehad/Twitter-Sentiment-Analysis-and-Classification/blob/main/download%20(lstm%20acc).png)
  ![Image](https://github.com/germeengehad/Twitter-Sentiment-Analysis-and-Classification/blob/main/download%20(rnn%20loss).png)
  
  ## LSTM Model
  ![Image]()
  ![Image]()

  ## SVM Model
  - Test Accuracy: 92.65%
  - Train Accuracy: 95.83%

  ## Naive Model
  - Test Accuracy: 77.62%
  - Train Accuracy: 80.67%
  
  
  
     
