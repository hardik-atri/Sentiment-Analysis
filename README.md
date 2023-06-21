# Business Problem
This project is about predicting the emotions in a sentence. This project is inspired from a use-case where a company wants to know how people respond to their advertisements or to their products. This will help the companies to analyse their product and can do the necessary changes.
So for this project, I have used the Emotions dataset from Kaggle. 
* I started by exploring the dataset. There are 18000 sentences and their corresponding emotions. Dataset has 5 emotions ( anger, fear, joy, love, surprise.) So its basically a multi-class problem.
* Now I looked for imbalance in the dataset and found out there is imbalance in the dataset. Sentences having emotion joy have the highest percentage and sentences having emotion surprise have the least percentage.
* Performance metric for this problem is ROC-AUC score. The AUC-ROC metric  tells us about the capability of a model in distinguishing the classes.
* Now I did some transformations on the dataset.
    * Removing special characters from the sentence.
    * Converting every character into small case
    * Stopword removal and lemmatization
    * Also used stemming.
* After doing the transformation, I encoded the text into vectors by 3 different techniques.
    * Bag of Words
    * Tf-idf
    * Tf-idf W2V ( using glove vector)
Applied different ML algo. To predict the sentiment.
