# Credit_Risk_Analysis
Module 17 Challenge Assignment

## Overview:
This challenge requested that we use “Supervised Machine Learning” techniques to determine the best model to evaluate “Credit Risk” on new loans.  Using a credit card credit dataset from LendingClub, a peer-to-peer lending services company we created several models using both Over & Under sampling algorithms as well as a combined Over/Under algorithm. After training the models we tested the models and measured them for accuracy, created “confusion matrix and imbalanced classification reports to evaluate each model and finalize our conclusion.

We decided on the following popular Machine Learning methods to create our models:
	(Random_Over_Sampler
	SMOTE
	Cluster_Centroids
	SMOTEEN
	Blanced_Random_Forest_Classifier
	Easy_Ensemble_AdaBoost_Classifier)
	
## Analysis Results:
Deliverable 1
### Random Over Sampling - Naive RandomOverSampler
![image](https://user-images.githubusercontent.com/95320265/165585672-6cea53a7-6a2c-4501-8e30-9aef03767592.png)

•	An accuracy score of the RandomOversampler model is 0.6438627638
•	The Confusion Matrix generated from this model
![image](https://user-images.githubusercontent.com/95320265/165585735-1adc5aa2-29fb-463b-b1d2-17c04041abd7.png)

•	The Imbalanced Classification Report from this model:
![image](https://user-images.githubusercontent.com/95320265/165586207-49ad603d-4c8b-4ff8-911c-25ebb29cc36d.png)



### Over sampling – SMOTE
![image](https://user-images.githubusercontent.com/95320265/165585896-fe56c814-dbfb-4914-8ef9-34f45772ce25.png)

•	An accuracy score of the SMOT model is 0.6438327638
•	The Confusion Matrix generated from this model:
![image](https://user-images.githubusercontent.com/95320265/165586398-c4c6fadc-df75-4b16-a26b-6d3eb2fbf59b.png)

•	The Imbalanced Classification Report from this model:
![image](https://user-images.githubusercontent.com/95320265/165586495-d337b722-eb12-454f-9680-165b6a2e22a3.png)


### Under Sampling - ClusterCentroids
![image](https://user-images.githubusercontent.com/95320265/165586637-b94e0dd6-1e81-48da-9c7a-47bad661bad6.png)

•	An accuracy score of the ClusterCentroids model is 0.6438627638
•	The Confusion Matrix generated from this model
![image](https://user-images.githubusercontent.com/95320265/165586992-1580620c-8e4d-4593-b8ad-27bab9683502.png)

•	The Imbalanced Classification Report from this model:
![image](https://user-images.githubusercontent.com/95320265/165587066-2adb29cf-ad05-44b9-b42e-675d0fcadb15.png)


Deliverable 2
### Combination of (Over and Under) Sampling – SMOTEEN
![image](https://user-images.githubusercontent.com/95320265/165587219-243faf24-775e-4f57-ae41-52fee4beb7b3.png)

•	  An accuracy score of the SMOTEEN model is 0.5441781794
•	The Confusion Matrix generated from this model:
![image](https://user-images.githubusercontent.com/95320265/165587335-400dda27-9499-4581-b81a-ab5506559f83.png)














