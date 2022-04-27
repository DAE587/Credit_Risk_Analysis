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
### Combination of (Over and Under) Sampling – SMOTEENN
![image](https://user-images.githubusercontent.com/95320265/165587219-243faf24-775e-4f57-ae41-52fee4beb7b3.png)

•	  An accuracy score of the SMOTEEN model is 0.5441781794

•	The Confusion Matrix generated from this model:
![image](https://user-images.githubusercontent.com/95320265/165587968-966b8c3e-7d70-4b5d-9dd9-afddc71d315b.png)


Deliverable 3
### Ensemble Learners - Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/95320265/165587849-ca8483ba-eb46-48a4-b406-22001f401724.png)

•	An accuracy score of the Balanced Random Forest Classifier model is 0.7885466545

•	The Confusion Matrix generated from this model:
![image](https://user-images.githubusercontent.com/95320265/165587923-61a0b795-ff77-4fc5-b88e-807cae667161.png)

•	The Imbalanced Classification Report from this model:
![image](https://user-images.githubusercontent.com/95320265/165588349-3fa39f8a-bdef-4b5d-9e68-4ba06f551650.png)


### Ensemble Learners - Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/95320265/165588444-26bc4629-3f9f-4695-b2b5-fedb1bf7d053.png)

•	  An accuracy score of the Easy Ensemble AdaBoost Classifier model is 0.9316600714

•	The Confusion Matrix generated from this model:
![image](https://user-images.githubusercontent.com/95320265/165588518-4bca9917-6027-4c60-b067-5372ff027a9c.png)

•	The Imbalanced Classification Report from this model:
![image](https://user-images.githubusercontent.com/95320265/165588570-5bf60971-7f51-479a-90a3-d0967ca16642.png)


Another request for the challenge was for us to sort the features by importance.  This could allow us to determine if we want to handle features differently based on their importance.  As you can see the “total_rec_prncp” is the most important with an importance score of .078768, which is about 2% points higher than the next most important item. The next few features have minimal differences and several at the bottom have no importance.  We could probably remove this data from our analysis.  Below show the top and bottom five items out of a total of ninety-four features.
![image](https://user-images.githubusercontent.com/95320265/165588659-9e3e1516-1c79-4dd3-865e-e8ce901fcf36.png)



## Summary:

Here is a summary table of our six models with their accuracy scores and the Precision, Recall and F1 results from their imbalanced Classification reports:
![image](https://user-images.githubusercontent.com/95320265/165588794-c60cc361-6f56-4c7f-8b58-a7d87c293f71.png)

Scoring definitions:
	Accuracy: How many of our predicted scores are correct.
	
	Precision: How close our predicted scores are together in a group
	
	Recall: Also known as sensitivity and the closer to one the better the score.
	
	F1: Is a harmonic mean of the precision and recall scores.
	

With these definitions the F1 score is probably the best score to evaluate our models. The better the model is at making correct prediction the closer the F1 score is to 1.0.  Given the results above the “Easy Ensemble AdaBoost Classifier” method is significantly better than all the other in evaluating high-risk loans and on average is very close to the 1.0 score across the board, so that would the model we would recommend.
























