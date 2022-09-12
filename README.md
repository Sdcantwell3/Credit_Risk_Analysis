# Credit_Risk_Analysis
Using Supervised Machine Learning to Determine Credit Risk


## Results
1. Naive Random Oversampling 
  -Precisioin: High Risk = 0.01; Low Risk = 1.00
  -Recall: High Risk = .69; Low Risk = 0.40
  -Balanced Accuracy Score = 0.54
  -Accuracy score is low
![Naive_random_oversampling](https://user-images.githubusercontent.com/104606589/189573040-f32d1155-1ffe-4564-b687-def7bf41f3d2.png)
2. SMOTE Oversampling 
  -Precisioin: High Risk = 0.01; Low Risk = 1.00
  -Recall: High Risk = .62; Low Risk = 0.69
  -Balanced Accuracy Score = 0.65
  -Accuracy score is low
![SMOTE_OS](https://user-images.githubusercontent.com/104606589/189573042-51b53c91-c249-4519-ab11-7ae3128b591b.png)
3. Cluster Centroids Undersampling
  -Precisioin: High Risk = 0.01; Low Risk = 1.00
  -Recall: High Risk = .69; Low Risk = 0.40
  -Balanced Accuracy Score = 0.54
  -Accuracy score is low
![ClusterCentroidUndersampling](https://user-images.githubusercontent.com/104606589/189573044-0e43f575-0033-426a-9072-1eed1c5bcf25.png)
4. SMOTEENN (Combination of Over and Undersampling)
  -Precisioin: High Risk = 0.01; Low Risk = 1.00
  -Recall: High Risk = .73; Low Risk = 0.60
  -Balanced Accuracy Score = 0.66
  -Accuracy score is low
![combinationOUSampling](https://user-images.githubusercontent.com/104606589/189573045-7beb6f07-0383-46b5-80be-a2ba151db1b7.png)
5. Balanced Random Forest Classifier
  -Precisioin: High Risk = 0.03; Low Risk = 1.00
  -Recall: High Risk = .70; Low Risk = 0.87
  -Balanced Accuracy Score = 0.78
  -Accuracy score is low
![Balanced_Random_Forest](https://user-images.githubusercontent.com/104606589/189573035-8211d6e5-7b54-4e23-8537-ea2e4f72269a.png)
6. Easy Ensemble AdaBoost Classifier
  -Precisioin: High Risk = 0.09; Low Risk = 1.00
  -Recall: High Risk = .92; Low Risk = 0.94
  -Balanced Accuracy Score = 0.93
  -Accuracy score is low
![EasyEnsembleClassifier](https://user-images.githubusercontent.com/104606589/189573037-2f467176-c5d4-4802-ac14-6cc479b05606.png)
