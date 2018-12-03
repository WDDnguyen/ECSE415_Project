CLASSIFICATION : 

To run classification for SVM and KNN : 
	- Add the  MIO-TCD-Classification dataset into the main directory
	- run classificationKnn jupyter notebook
		- This will generate the filename1.pk1 to load for localization
	- run classificationSVM jupyter notebook
		- This will generate finalized_model_updated.pk1 to load for localization 

LOCALIZATION :

To run localization :
	- Add the MIO-TCD_Localization
		- run localization_KNN jupyter notebook (need to run classification since model was too large to submit with it)
			- results from localization produced in knn_localization
			
		- run localization_SVM jupyter notebook
			- results from localization produced in svm_localization 
			
	
	