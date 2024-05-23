# Arrhythmia Detection using XGBoost

### Introduction
This project aims to differentiate various types of arrhythmias from normal heart rhythms using machine learning techniques, particularly **XGBoost**. The dataset used for training the model is `MIT-BIH Arrhythmia Database.csv`, which contains a collection of electrocardiogram (ECG) signals labeled with different arrhythmia types.
### Dataset Structure
The dataset consists of ECG signals with corresponding labels indicating the presence of arrhythmia or normal heart rhythm. The following arrhythmia types are considered as anomalies:
-	VEB
-	SVEB
-	F
-	Q

These anomalies are labeled as 'arrhythmia', while normal heart rhythms (N) are labeled as 'normal'.
### Data Access
The data is accessible and downloadable from [here](https://www.kaggle.com/datasets/sadmansakib7/ecg-arrhythmia-classification-dataset/data).

- [Original paper](http://ecg.mit.edu/george/publications/mitdb-embs-2001.pdf)
- [Paper](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003028635-11/harnessing-artificial-intelligence-secure-ecg-analytics-edge-cardiac-arrhythmia-classification-sadman-sakib-mostafa-fouda-zubair-md-fadlullah) about the feature extraction phase from the original dataset

### Tools and Libraries Used
- Jupyter
- numpy 1.24.3
- pandas 2.1.4
- scikit-learn 1.3.0
- xgboost 2.0.3
- matplotlib 3.8.4

### Correlation Heatmap of All Features
<img src="https://github.com/mohammadhosseinparsaei/ECG-Arrhythmia-Classification/blob/main/correlation_heatmap.png" alt="Heatmap" width="500"/>

### Model Performance

#### Confusion Matrix
<img src="https://github.com/mohammadhosseinparsaei/ECG-Arrhythmia-Classification/blob/main/confusion%20matrix.png" alt="Confusion Matrix" width="500"/>

#### ROC Curve
<img src="https://github.com/mohammadhosseinparsaei/ECG-Arrhythmia-Classification/blob/main/ROC_curve.png" alt="ROC Curve" width="500"/>
