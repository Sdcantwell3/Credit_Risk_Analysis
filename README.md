# Credit_Risk_Analysis
Using Supervised Machine Learning to Determine Credit Risk


## Results
1. Naive Random Oversampling  
    - Precisioin: High Risk = 0.01; Low Risk = 1.00
    - Recall: High Risk = .69; Low Risk = 0.40
    - Balanced Accuracy Score = 0.54
    - Accuracy score is low
   
  ![Naive_random_oversampling](https://user-images.githubusercontent.com/104606589/190297367-a45f5e66-6449-4db1-be94-6c5974900581.png)


2. SMOTE Oversampling 
    - Precisioin: High Risk = 0.01; Low Risk = 1.00
    - Recall: High Risk = .69; Low Risk = 0.40
    - Balanced Accuracy Score = 0.54
    - Accuracy score is low
    
![SMOTE_OS](https://user-images.githubusercontent.com/104606589/190297385-94e2cb07-b145-49e8-9ad3-3ef884e90c98.png)


3. Cluster Centroids Undersampling
   - Precisioin: High Risk = 0.01; Low Risk = 1.00
   - Recall: High Risk = .69; Low Risk = 0.40
   - Balanced Accuracy Score = 0.54
   - Accuracy score is low
   
![ClusterCentroidUndersampling](https://user-images.githubusercontent.com/104606589/190297415-498a9cf3-c182-4790-a5d8-230fb0c7746c.png)


4. SMOTEENN (Combination of Over and Undersampling)
    - Precisioin: High Risk = 0.01; Low Risk = 1.00
    - Recall: High Risk = .73; Low Risk = 0.60
    - Balanced Accuracy Score = 0.66
    - Accuracy score is low
    
![combinationOUSampling](https://user-images.githubusercontent.com/104606589/190297469-d9008c73-acb0-4ee8-a5c4-53592330b3ce.png)


5. Balanced Random Forest Classifier
    - Precisioin: High Risk = 0.03; Low Risk = 1.00
    - Recall: High Risk = .70; Low Risk = 0.87
    - Balanced Accuracy Score = 0.78
    - Accuracy score is low
    
![Balanced_Random_Forest](https://user-images.githubusercontent.com/104606589/189573035-8211d6e5-7b54-4e23-8537-ea2e4f72269a.png)

6. Easy Ensemble AdaBoost Classifier
    - Precisioin: High Risk = 0.09; Low Risk = 1.00
    - Recall: High Risk = .92; Low Risk = 0.94
    - Balanced Accuracy Score = 0.93
    - Accuracy score is low
    
![EasyEnsembleClassifier](https://user-images.githubusercontent.com/104606589/189573037-2f467176-c5d4-4802-ac14-6cc479b05606.png)

## Summary

- The 2 ensemble methods performed better than all three of the Oversampling/Undersampling/Combination algorithms.
- The Cluster Centroids and the Naive Random Oversampling performed the worst with accuracies of .54.
