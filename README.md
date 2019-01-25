# Discover Outstanding NBA Players: Comparing Anomaly Detection Techniques

Given key statistics for an NBA player, is he outstanding or not? That is the problem we are tackling. We want to train different anomaly detection machine learning models that identify outstanding NBA players from a group of players. We will then compare the performances of these models to see which techniques were more accurate in finding outliers (or players who were "outstanding"). Constructing the outlier detection models between all techniques follow the same stages of parameterization, training, and testing. Parameterization where you collect the raw data has already been done for us. We will be using NBA statistics data available from kaggle.com (more information in the data section). However, the training and testing stages is what our focus will be on for each technique. We will tune each model depending on each technique’s hyper-parameters.

Our big focus is seeing how supervised anomaly detection compares to unsupervised anomaly detection. The supervised algorithms’ training data will be labeled so the outliers are known. The unsupervised algorithms’ training data will not be labeled but still contains outliers. The two supervised anomaly detection algorithms we will be using are: SVM and Supervised Robust Co- variance Estimator (with Elliptic Envelopes). The two unsupervised anomaly detection algorithms we will be using are: Local Outlier Factor and a Decision Tree technique with Isolation Forests.

To view our results, check out [MachineLearning.PDF](https://github.com/jasonchitla/Machine-Learning-Comparing-Anomaly-Detection-Techniques/blob/master/MachineLearning.pdf)
