# Semi-Supervised-Learning-Hands-on

Hi,<br>
This repository is my work on a university course project on __Semi Supervised Learning__.<br>

This project highlighted Semi Supervised Learning algorithms with different percent of unlabelled data. There were three algorithms used in this project for the experimentations –
1. Semi Supervised Self Training
2. Semi Supervised Ensemble
3. Unsupervised Pretraining </br>


For __Semi Supervised Self Training, five base machine learning algorithms were used to perform the experimentation__ and get a bigger sample of the metrics for the comparison. For __Semi Supervised Ensemble, Majority Voting Classifier was used__ with a choice of one of two base learners. And finally, for __Unsupervised Pretraining, an Autoencoder is used.__
There are six different sets of unlabelled data – __0%, 10%, 20%, 50%, 90%, and 95%__.<br>

There were three original datasets, namely, Shoppers Data, Customer Data, and Heart Disease Data, where Shoppers Data was highly imbalanced, and hence two more datasets were created using Under sampling and Oversampling Shoppers Data to balance the classes. Hence, there is a total of five datasets on which the three algorithms have experimented. The naming conventions are –
1. Data1 – Shoppers Data (https://www.kaggle.com/roshansharma/online-shoppers-intention)
2. Data2 – Undersampled Shoppers Data 
3. Data3 – Oversampled Shoppers Data
4. Data4 – Customer Data (https://www.kaggle.com/imakash3011/customer-personality-analysis)
5. Data5 – Heart Disease Data (https://www.kaggle.com/ronitf/heart-disease-uci)
Data4 and Data5 were not resampled because they were quite balanced, and oversampling can lead to overfitting of data sometimes.
Undersampling was performed using RandomUnderSampler, and Oversampling was performed with SMOTE that uses KNN to get synthetic data. <br>

__Please find the .ipynb file for the implementations__

If you are referrering or using this repository, consider citing. Happy coding :)


