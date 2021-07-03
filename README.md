# Parkinsons Disease Classification


## Introduction

This dataset is collected from UCI Machine Learning Repository through the following link: https://archive.ics.uci.edu/ml/datasets/Parkinson%27s+Disease+Classification#

### Data Set Information:

The data used in this study were gathered from 188 patients with PD (107 men and 81 women) with ages ranging from 33 to 87 (65.1Â±10.9) at the Department of Neurology in CerrahpaÅŸa Faculty of Medicine, Istanbul University. The control group consists of 64 healthy individuals (23 men and 41 women) with ages varying between 41 and 82 (61.1Â±8.9). During the data collection process, the microphone is set to 44.1 KHz and following the physicianâ€™s examination, the sustained phonation of the vowel /a/ was collected from each subject with three repetitions.

### Attribute Information:

Various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features and TWQT features have been applied to the speech recordings of Parkinson's Disease (PD) patients to extract clinically useful information for PD assessment.

### Citation Request:

If you use this dataset, please cite: Sakar, C.O., Serbes, G., Gunduz, A., Tunc, H.C., Nizam, H., Sakar, B.E., Tutuncu, M., Aydin, T., Isenkul, M.E. and Apaydin, H., 2018. A comparative analysis of speech signal processing algorithms for Parkinsonâ€™s disease classification and the use of the tunable Q-factor wavelet transform. Applied Soft Computing, DOI: [Web Link] https://doi.org/10.1016/j.asoc.2018.10.022


## Models Used

A serie of classical machine learning models were used, such as : 

* Logistic Regression 
* Naive Bayes
* SVM 
* KNN
* Decision tree
* Random Forest
* Bagging Classifier
* ADA/XG-Boost
* LGBM
* Small CNN networks

These models are reused after PCA compression of the data to decrease computation time. The minimal variance explained to reach during the compression is set to 0.8 but can be easily changed. 

## Results
 

<img src="https://github.com/sebgra/Parkinsons_Disease_Classification/blob/main/results/images/Classification_results.png"
     alt="Results graph"
     style="float: left; margin-right: 10px;" />



