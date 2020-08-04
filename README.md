# human-activity-recog
The task was to classify human activity like walking, standing, walking, walking down, walking up, laying. using signals generated from sensors like accelerometer and gyroscope.
We made both traditional ML models and Deep learning models ,then analyzed them on basis of accuracy and other parameters.

<h2>Machine Learning Models</h2>
For these models, we used hand made features engineering by domain experts.<br><br>

<h3>Logistic Regression</h3>
Accuracy:96.19952494061758
<br><br>
<h3>KNN</h3>
Accuracy:90.53274516457415
<br><br>
<h3>Gaussian NB</h3>
Accuracy:80.04750593824228
<br><br>
<h3>Linear SVM</h3>
Accuracy:96.84424838819137
<br><br>
<h3>Kernel SVM</h3>
Accuracy:96.47098744485918
<br><br>
<h3>Decision Tree</h3>
Accuracy:81.6762809636919
<br><br>
<h3>Random Forest</h3>
Accuracy:92.43298269426535
<br><br>
<h3>Gradient Boosting</h3>
Accuracy:93.92602646759416
<br><br>
<h2>Deep Learning Models</h2>
Here we used original signals by transforming them using sliding window technique with window size of 2.56sec and 50% overlap.
<br><br>
<h3>Model Architecture:</h3>
2 LSTM layers------------>Dropout layer--------->Softmax layer for classification
<br><br>
Accuracy:91.45%


<h2>Conclusion</h2>
We can see that, DL model managed to achieve a decent accuracy without any feature engineering.This tells us the power of Deep Learning.
