# kinematics-motion-detection
Supervised Machine Learning project to differentiate running and walking to keep track of daily footsteps recorded by the sensors in iPhone Operating System (IOS)

# 1. Introduction
Kinematics is the study of how an entity moves without the influence of outer factors such as forces and
potential fields. Example of kinematics is anything that involves movement from one to point to another
such as running, walking, jogging, falling and many more. In this project, we aim to differentiate running
and walking to keep track of daily footsteps recorded by the sensors in iPhone Operating System (IOS)
devices. Precisely, there are 2 types of sensors, named accelerometer and gyroscope that provide the data
samples in the coordinations of x,y and z.
The proposed solution to differentiate between running and walking is through the application of
supervised machine learning algorithms. The algorithms that will be used in this project are binary
classification algorithms that categorize 2 types of classes, running and walking based on the 6 different
features such as acceleration_x, acceleration_y, acceleration_z, gyro_x, gyro_y, gyro_z. There are a total
of 8 algorithms that will be implemented in this project named K-Nearest Neighbor, Naive Bayes,
Random Forest Classifier, Logistic Regression, Decision Tree Classifier, Extra Tree Classifier, Support
Vector Machine, and Artificial Neural Network.
Additionally, Adaptive Boosting Classifiers and Voting from the family of Ensemble methods will be also
incorporated. The models resulting from the algorithms will be compared and evaluated through several
evaluation metrics like accuracy, precision, recall, specificity, f1 score, average precision score, cross
validation score, receiver operating characteristic curve (ROC), and Area under the ROC Curve (AUC).
Hyperparamater tuning and optimization will be performed for all the models in an automated fashion
through GridSearchCV. The model that provides the highest accuracy shall be chosen as the best model
for respective algorithms and the top 3 best models are combined as an ensemble model.

# 2. Methodology
![image](https://github.com/nheelam/kinematics-motion-detection/assets/64530832/c228d497-dbbd-4db7-a318-c0916c965aed)
