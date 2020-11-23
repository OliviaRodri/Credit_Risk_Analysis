# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to apply machine learning to predict credit risk for a lending services company. The models that were used to run this analysis were undersampling, oversampling, and a combinational model of over and under sampling. 

## Results: 
Image below is the loan status count of 'low risk' and 'high risk' for this analysis.
![credRisk_images](Resources/l_stat_counts.PNG)

Model 1:

![credRisk_images](Resources/N_Over_Samp_title.PNG)
![credRisk_images](Resources/Naive_Balnc_cnfMtrx_rprt.PNG)
Results for the Naive Over Sampling are as follows:
- The balanced accuracy score is 0.63
- The precision score for 
  - high risk is : 0.01
   - low risk is : 1.0
- The recall score for 
  - high risk: .59
  - low risk: .67
- The f1 score for 
  - high risk : 0.02
  - low risk : .80
  
 Model 2:

![credRisk_images](Resources/smote_ovr_samp_title.PNG)
![credRisk_images](Resources/smote_blnc_cnfmtrx_rprt.PNG)
Results for the Smote over sampling are as follows:
- The balanced accuracy score is 0.63
- The precision score for 
  - high risk is : 0.01
   - low risk is : 1.0
- The recall score for 
  - high risk: .62
  - low risk: .64
- The f1 score for 
  - high risk : 0.02
  - low risk : .78
   
Model 3:

![credRisk_images](Resources/undr_samp_title.PNG)
![credRisk_images](Resources/undr_samp_blnc_cnfmtrx_rprt.PNG)

- The balanced accuracy score is 0.63
- The precision score for 
  - high risk is : 0.01
   - low risk is : 1.0
- The recall score for 
  - high risk: .64
  - low risk: .40
- The f1 score for 
  - high risk : 0.01
  - low risk : .57

Model 4:

![credRisk_images](Resources/combo_ovr_undr_samp_title.PNG)
![credRisk_images](Resources/combo_undrOvr_blnc_cnfmtrx_rprt.PNG)

- The balanced accuracy score is 0.52
- The precision score for 
  - high risk is : 0.01
   - low risk is : 1.0
- The recall score for 
  - high risk: .69
  - low risk: .60
- The f1 score for 
  - high risk : 0.02
  - low risk : .75

![credRisk_images](Resources/ensemble_learner_title.PNG)
![credRisk_images](Resources/bal_rnd_forest_title.PNG)
![credRisk_images](Resources/bal_rand_forsest_accur_cnfmtrx_rprt.PNG)

- The balanced accuracy score is 0.79
- The precision score for 
  - high risk is : 0.04
   - low risk is : 1.0
- The recall score for 
  - high risk: .67
  - low risk: .91
- The f1 score for 
  - high risk : 0.07
  - low risk : .95

Model 5:

![credRisk_images](Resources/easy_ensemble_title.PNG)
![credRisk_images](Resources/easy_ensemble_bal_cnfmtrx_rprt.PNG)

- The balanced accuracy score is 0.93
- The precision score for 
  - high risk is : 0.07
   - low risk is : 1.0
- The recall score for 
  - high risk: .91
  - low risk: .94
- The f1 score for 
  - high risk : 0.14
  - low risk : .97


Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)