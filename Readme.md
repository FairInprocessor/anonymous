<h2> This repository contains "FairInprocessor: Addressing Fairness–Performance Trade-off via Situation Testing and Pareto Optimization" replicate package. </h2>  
-----------------------------------------------------


Code - https://drive.google.com/drive/folders/1e9XCKADcPf22KCRspg1xAy7Jjwy_UhCR 


-----------------------------------------------------
<h2> Baselines </h2>

**Fair-Smote: Proposed in the paper: Bias in Machine Learning Software: Why? How? What to Do?**
Fair-SMOTE is a pre-processing method that uses the modified SMOTE method to balance the distribution of sensitive features and class labels in the dataset consistently. Then, biased data labels are removed through situation testing tactics.
We use the code they provided in the code repository: https://github.com/joymallyac/Fair-SMOTE

**FairMask: Proposed in the paper: FairMask: Better Fairness via Model-Based Rebalancing of Protected Attributes**
Fairway is a hybrid algorithm that combines pre-processing and post-processing methods. 
We use the code they provided in the code repository: https://github.com/anonymous12138/biasmitigation 

**LTDD: Linear Regression Based Training Data Debugging**
LTDD is a preprocessing algorithm that finds and removes the biased portion present in the features of the training data.
We use the code they provided in the code repository: https://github.com/fairnesstest/LTDD

**MirrorFair**
MirrorFair is a preprocessing method that employs an ensemble approach to address fairness issues, grounded in the principles of counterfactual inference. It creates a counterfactual dataset from the original dataset and trains two separate models, one on the original dataset and the other on the counterfactual dataset. Finally, it adaptively combines the predictions from both models to produce fairer final decisions. We use the code they provided in the code repository: https://github.com/XY-Showing/FSE2024-MirrorFair
 

-----------------------------------------------------


