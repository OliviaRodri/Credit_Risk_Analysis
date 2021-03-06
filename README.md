# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to apply machine learning to predict credit risk for a lending services company. 
The models/algorithms that were used to run this analysis are as follows:
- Random Over Sampler (oversampling) 
- Smote (oversampling) 
- Cluster Centroids (under sampling) 
- Smoteen (combinational model of over and under sampling)
- Balanced Random Forest Classifier
- Easy Ensemble Classifier   

## Results: 
Image below is the loan status count of 'low risk' and 'high risk' for this analysis.
![credRisk_images](Resources/l_stat_counts.PNG)

Model 1: NAIVE RANDOM OVER SAMPLING


![credRisk_images](Resources/Naive_Balnc_cnfMtrx_rprt.PNG)
Results for the Naive Over Sampling are as follows:
- The balanced accuracy score is 0.63
- The precision score for 
  - high risk is : 0.01
   - low risk is : 1.0
- The recall score for 
  - high risk: .59
  - low risk: .67
     
 Model 2: SMOTE OVER SAMPLING


![credRisk_images](Resources/smote_blnc_cnfmtrx_rprt.PNG)
Results for the Smote over sampling are as follows:
- The balanced accuracy score is 0.63
- The precision score for 
  - high risk is : 0.01
   - low risk is : 1.0
- The recall score for 
  - high risk: .62
  - low risk: .64
   
Model 3: CLUSTER CENTROIDS

![credRisk_images](Resources/undr_samp_blnc_cnfmtrx_rprt.PNG)

Results for the Cluster centroid under sampling are as follows:

- The balanced accuracy score is 0.63
- The precision score for 
  - high risk is : 0.01
   - low risk is : 1.0
- The recall score for 
  - high risk: .64
  - low risk: .40

Model 4: SMOTEEN

![credRisk_images](Resources/combo_undrOvr_blnc_cnfmtrx_rprt.PNG)

Results for the Smoteen over and under sampling, are as follows:

- The balanced accuracy score is 0.52
- The precision score for 
  - high risk is : 0.01
   - low risk is : 1.0
- The recall score for 
  - high risk: .69
  - low risk: .60


Model 5: BALANCED RANDOM FOREST CLASSIFIER

![credRisk_images](Resources/bal_rand_forsest_accur_cnfmtrx_rprt.PNG)

- The balanced accuracy score is 0.79
- The precision score for 
  - high risk is : 0.04
   - low risk is : 1.0
- The recall score for 
  - high risk: .67
  - low risk: .91

Model 6: EASY ENSEMBLE CLASSIFIER


![credRisk_images](Resources/easy_ensemble_bal_cnfmtrx_rprt.PNG)

- The balanced accuracy score is 0.93
- The precision score for 
  - high risk is : 0.07
   - low risk is : 1.0
- The recall score for 
  - high risk: .91
  - low risk: .94


## Summary
![credRisk_images](Resources/chart.PNG)


The model with the highest accuracy score was the Easy Ensemble Classifier. The high risk recall was at 91%, having the best result in comparison to the other models.  All the models had very low precision, identifying high risk applicants. However, this drawback to all models would result in labeling a low risk candidate as high risk. The main purpose of this model was to identify high risk in which it does, (recall 91%). Therefore, I would recommend  model 6 'Easy Ensemble Classifier' for an analysis to be performed. 