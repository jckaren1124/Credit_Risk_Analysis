# Credit_Risk_Analysis

## Overview of the analysis
The purpose of this analysis is to generate models to predict credit risk. Different types of algorithms are used (RandomOverSample, SMOTE, ClusterCentroids, RandomForestClassifier, and EasyEnsembleClassifier) from machine learning techniques to assess the differences and determine which model (if any) appears to be the best for predicting credit risk. 

## Results

Random Oversampling   
![image](https://user-images.githubusercontent.com/89353378/149835658-40747557-6669-4592-9251-cd35256d98f3.png)
![image](https://user-images.githubusercontent.com/89353378/149835723-7a01b5ec-f4f7-4706-9c22-a3fc822d3979.png)



SMOTE Oversampling  
![image](https://user-images.githubusercontent.com/89353378/149836116-1b732613-f3ec-4e83-b5a9-c13455112787.png)
![image](https://user-images.githubusercontent.com/89353378/149836162-4c83fd91-36ce-45ff-acf3-df6c1af0f8df.png)



Cluster Centroids Undersampling  
![image](https://user-images.githubusercontent.com/89353378/149865646-2664ce7c-55fd-401f-8a94-78910ed4a4f8.png)
![image](https://user-images.githubusercontent.com/89353378/149865695-f8b43362-5387-4509-a621-96069b6c3d4f.png)



SMOTEENN Combination (Over and Under) Sampling  
![image](https://user-images.githubusercontent.com/89353378/149867166-48995289-dd2a-4ea7-90c8-a4f52eecab91.png)
![image](https://user-images.githubusercontent.com/89353378/149867209-d270e726-15d2-4d1f-b534-d6ace4b8ccac.png)



Balanced Random Forest Classifier  
![image](https://user-images.githubusercontent.com/89353378/149840241-bd1ddf97-9372-41d7-b221-75da661d5743.png)
![image](https://user-images.githubusercontent.com/89353378/149840276-aa165e22-ed79-4bbe-bbc8-f7ab554f84eb.png)
 



## Summary

The low accuracy rate for the cluster centroids undersampling and SMOTEENN combination sampling models might be due to eliminating too much relevant data, resulting in an increased number of inaccurate predictions.  Since recall measures the rate of true predictions, this means that the balanced random forest classifier model correctly predicted the highest number of fraudulent transactions.  All models showed about the same precision score, indicating that they are all fairly reliable on their predictions.  Based on these scores, it appears that the balanced random forest classifier model is the best model for making predictions.
