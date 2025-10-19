The amount and extent of calcium deposits visible in Cone Beam CT (CBCT) scans of the head and neck region is one of the strongest indicators of myocardial infarction (heart attack), stroke, cardiac surgery, and other adverse outcomes. This project uses existing methodology to detect and segment the calcification regions from CT scans and investigates the creation of a novel machine learning based pipeline to predict specific outcomes from radiomic features extracted from the calcification regions. Specifically, this study focuses on early prediction of stroke, myocardial infarction (heart attack), low levels of anticoagulants, hypertension (high blood pressure), and future need for cardiac surgery. Data from the study comes from the medical history and paired CBCT scans of 237 patients at Stony Brook University Hospital. Radiomic features from the scans were extracted and unsupervised clustering was performed to identify relevant features that are correlated to particular medical outcomes. Other feature selection methods such as recursive feature elimination (RFE) and information gain (IG) were also used. A variety of different models (SVM’s, RandomForests, Neural Nets) and combinations composing ensemble models were trained and tuned to optimize performance for prediction of each medical outcome. Overall, the final tuned binary classification models’ trained on features selected by RFE (which proved to be the best feature selection method) reported accuracies are 88.23% for stroke prediction, 82.35% for myocardial infarction, 89.36% for low levels of anticoagulants, 91.31% for hypertension, and 86.54% for cardiac surgery. The tuned multiclass classification model for all outcomes gave a final accuracy of 70.588%. Future work includes incorporation of radiologist-annotated data and transfer learning based on some in-house models in the IMAGINE Lab, Stony Brook University Computer Science Department.

Repo File Contents

Allfeatures_Alloutcomes_Model - Initial Multiclass classification model to predict all selected outcomes trained on all extracted radiomic features.

Allfeatures_Anticoagulants_Model - Optimized binary classification model to predict low levels of anticoagulants trained on all extracted radiomic features

Allfeatures_Best_Model - Optimized multiclass classification model to predict all selected outcomes trained on all extracted radiomic features

Allfeatures_Hypertension_Model - Optimized binary classification model to predict hypertension trained on all extracted radiomic features

Allfeatures_MyocardialInfarction_Model - Optimized binary classification model to predict myocardial infarction trained on all extracted radiomic features

Allfeatures_Partialoutcomes_Model - A set of optimized multiclass classification models to predict subsets (2 or more) of the 5 medical outcomes, trained on all extracted radiomic features

Allfeatures_Stroke_Model - Optimized binary classification model to predict stroke trained on all extracted radiomic features
Allfeatures_Surgery_Model - Optimized binary classification model to predict need for cardiac surgery, trained on all extracted radiomic features

InfoGainFeatures_Alloutcomes_Model - Initial Multiclass classification model to predict all selected outcomes trained on radiomic features selected through mutual information gain.

InfoGainFeatures_Anticoagulants_Model - Optimized binary classification model to predict low levels of anticoagulants trained on radiomic features selected through mutual information gain.

InfoGainFeatures_Best_Model - Optimized multiclass classification model to predict all selected outcomes trained on radiomic features selected through mutual information gain.

InfoGainFeatures_Hypertension_Model - Optimized binary classification model to predict hypertension trained on radiomic features selected through mutual information gain.

InfoGainFeatures_MyocardialInfarction_Model - Optimized binary classification model to predict myocardial infarction trained on radiomic features selected through mutual information gain.

InfoGainFeatures_Partialoutcomes_Model - A set of optimized multiclass classification models to predict subsets (2 or more) of the 5 medical outcomes, trained on radiomic features selected through mutual information gain.

InfoGainFeatures_Stroke_Model - Optimized binary classification model to predict stroke trained on radiomic features selected through mutual information gain.

InfoGainFeatures_Surgery_Model - Optimized binary classification model to predict need for cardiac surgery, trained on radiomic features selected through mutual information gain.

RFE_Alloutcomes_Model - Initial Multiclass classification model to predict all selected outcomes trained on radiomic features selected through recursive feature elimination.

RFE_Anticoagulants_Model - Optimized binary classification model to predict low levels of anticoagulants trained on radiomic features selected through recursive feature elimination.

RFE_Best_Model - Optimized multiclass classification model to predict all selected outcomes trained on radiomic features selected through recursive feature elimination.

RFE_Hypertension_Model - Optimized binary classification model to predict hypertension trained on radiomic features selected through recursive feature elimination.

RFE_MyocardialInfarction_Model - Optimized binary classification model to predict myocardial infarction trained on radiomic features selected through recursive feature elimination.

RFE_Partialoutcomes_Model - A set of optimized multiclass classification models to predict subsets (2 or more) of the 5 medical outcomes, trained on radiomic features selected through recursive feature elimination.

RFE_Stroke_Model - Optimized binary classification model to predict stroke trained on radiomic features selected through recursive feature elimination.

RFE_Surgery_Model - Optimized binary classification model to predict need for cardiac surgery, trained on radiomic features selected through recursive feature elimination.

Recursive_Feature_Elimination_Anticoagulant - Recursive Feature Elimination procedure performed to identify features most useful for prediction of low levels of anticoagulants

Recursive_Feature_Elimination_Myocardial - Recursive Feature Elimination procedure performed to identify features most useful for prediction of myocardial infarction

Recursive_Feature_Elimination_Stroke - Recursive Feature Elimination procedure performed to identify features most useful for prediction of stroke

Recursive_Feature_Elimination_hypertension - Recursive Feature Elimination procedure performed to identify features most useful for prediction of hypertension

Recursive_Feature_Elimination_surgery - Recursive Feature Elimination procedure performed to identify features most useful for prediction of future need for cardiac surgery


