# CMPE255-Project  

### README for feature-selector:  
Use the below commands to install feature-selector:

git clone https://github.com/WillKoehrsen/feature-selector.git  
cd feature-selector  
pip install -e .  

Requirements:  
python==3.6+  
lightgbm==2.1.1  
matplotlib==2.1.2  
seaborn==0.8.1  
numpy==1.14.5  
pandas==0.23.1  
scikit-learn==0.19.1  

Reference : https://github.com/WillKoehrsen/feature-selector  
### Work Flow
####
This project implements 6 types of multiclassification models trained with 3 different feature selection methods on pre-processed dataset, evaluated and anlayzed the models results and visualized the same with various metric plots.

### Master Branch: Initial Committs
File Network Anomaly Detection.ipynb	has initial committ of parsing data, structuring and pre-processing . Not a main source code.

### feature_importance
1. FeatureSelection_ExtraTreeClassifier.ipynb : This file contains implementation of feature selection using ExtraTreeClassifier model, Undersampling using Randomsampler and oversampling using SMOTE, including all prior data preprocessing.
2. Feature_Selection_RandomForests.ipynb : This file contains implementation of feature selection using RadomTreeClassifier model, Undersampling using Randomsampler and oversampling using SMOTE, including all prior data preprocessing.
3. Feature_Selector_NCR_SM_Sampler.ipynb :  This file contains implementation of feature selection using Feature Selector model, Undersampling using Neighbourhood Cleaning Rule and oversampling using SMOTE, including all prior data preprocessing.

### Models 
1. CNN_ExtratreeClassifier_dataset.ipynb 
2. CNN_on_ncr_sm.ipynb
3. ExtraTreeClassifier_KNN_NB_AdaB_XgB_Logistic_ROC _Plots.ipynb
4. RandomForest_models.ipynb


