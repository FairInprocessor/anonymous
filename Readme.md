<h2> This repository contains "FairInprocessor: Addressing Fairness–Performance Trade-off via Situation Testing and Pareto Optimization" replicate package. </h2>  
-----------------------------------------------------


Code - https://drive.google.com/drive/folders/1e9XCKADcPf22KCRspg1xAy7Jjwy_UhCR 


-----------------------------------------------------
<h2> Baselines </h2>


**Fairway: Fairway: A Way to Build Fair ML Software**
Fairway is a hybrid bias mitigation algorithm that integrates both preprocessing and in-processing strategies. First, it investigates how ground-truth bias embedded in training data influences the fairness of machine learning models and provides a mechanism to detect such bias within AI software. Second, it introduces a unified framework that combines data-level preprocessing and model-level in-processing techniques to mitigate ethical bias in both the training data and the resulting predictive model.
We use the code they provided in the code repository: https://github.com/joymallyac/Fairway 

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
MirrorFair is a preprocessing method that employs an ensemble approach to address fairness issues, grounded in the principles of counterfactual inference. It creates a counterfactual dataset from the original dataset and trains two separate models, one on the original dataset and the other on the counterfactual dataset. Finally, it adaptively combines the predictions from both models to produce fairer final decisions. 
We use the code they provided in the code repository: https://github.com/XY-Showing/FSE2024-MirrorFair

 **FairGenerate**
FairGenerate, a pre-processing method that (a) balances the internal distribution of training datasets based on class labels and sensitive attributes by generating synthetic data samples using differential evolution and (b) identifies the biased labels through situation testing and removes them before and after synthetic data generation, hence the development of fair ML software.
We use the code they provided in the code repository:  https://github.com/xyz745/FairGenerate/

-----------------------------------------------------


