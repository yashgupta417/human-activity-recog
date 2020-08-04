# human-activity-recog
The task was to classify human activity like walking, standing, walking, walking down, walking up, laying. using signals generated from sensors like accelerometer and gyroscope.
We made both traditional ML models and Deep learning models ,then analyzed them on basis of accuracy and other parameters.

<h2>Machine Learning Models</h2>
For these models, we used hand made features engineering by domain experts.

Logistic Regression
Training Time:0:02:34.000630	Accuracy:96.19952494061758

KNN
Training Time:0:03:24.616886	Accuracy:90.53274516457415

Gaussian NB
Training Time:0:00:05.724484	Accuracy:80.04750593824228

Linear SVM
Training Time:0:00:39.214242	Accuracy:96.84424838819137

Kernel SVM
Training Time:0:02:49.244386	Accuracy:96.47098744485918

Decision Tree
Training Time:0:00:02.466103	Accuracy:81.6762809636919

Random Forest
Training Time:0:00:46.293426	Accuracy:92.43298269426535

Gradient Boosting
Training Time:0:06:43.979135	Accuracy:93.92602646759416

<h2>Deep Learning Models</h2>
Here we used original signals by transforming them using sliding window technique with window size of 2.56sec and 50% overlap.

Model Architecture:
2 LSTM layers------------>Dropout layer--------->Softmax layer for classification

Accuracy:91.45%


<h2>Conclusion</h2>
We can see that, DL model managed to achieve a decent accuracy without any feature engineering.This tells us the power of Deep Learning.
