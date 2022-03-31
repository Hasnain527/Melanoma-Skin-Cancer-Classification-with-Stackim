# Melanoma-Skin-Cancer-Classification-with-Stacking

**Introduction:**

Skin diseases are complicated and diagnosing them can be a challenging task. In the case of skin cancer, malignant or cancer cells are found in the outer layer of the human skin. Computerized diagnosis systems are necessary due to increasing rate of skin cancer, time, and cost. Deep learning and machine learning algorithms have made this complex process much easier. We propose a deep ensemble learning base technique that primarily extracts features automatically. The goal is to employ an ensemble of 4 CNN models to improve classification results for skin cancer diagnosis. The suggested model's functionality will be compared against state-of-the-art techniques.
##Methodology: 
•	Ensemble of four CNN architectures (Efficient Net, InceptionV3, ResNet50, Xception) would be utilized for classification, which is followed by fully connected layers, the SoftMax function is used in the end for classification.
•	Melanoma skin cancer images from the dataset are fed into these models as input. Because of the softmax function, the results of each model are presented in a probabilistic manner.
•	Stacking is an ensemble technique to combine base learners. The proposed architecture will utilize the stacking approach to combine the output of above four base learner models. Each individual model would be trained on complete training data. Meta learner is fitted based on the outputs (probabilities) of individual base learners.

**Python Libraries:**

TensorFlow

Keras

SKlearn

OpenCV

PIL

Pandas

Numpy

Matplotlib

****Results:****

The proposed stacking ensemble model of four cnn architectures achieved 93% accuracy.  

