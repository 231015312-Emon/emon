Approach-
The objective of this project is to develop a CNN model capable of automatically classifying chest X-ray into two categories:
Pneumonia 
Normal
This is a supervised learning problem,
where the model is trained on labeled medical images and learns to recognize patterns associated with each class.
CNNs are particularly effective for
image classification tasks because they can automatically extract important spatial features such as edges, textures, and shapes from images.
Methodology-
The dataset consists of 5,863 chest X-ray images (JPEG format) categorized into two classes:
Pneumonia
Normal
The dataset is organized into three subsets:
Training set – used to train the model
Validation set – used to tune and validate performance
Test set – used for final evaluation
These images are anterior-posterior chest X-rays collected from pediatric patients aged 1–5 years as part of routine clinical care.
Findings-
The CNN model successfully learns to differentiate between Pneumonia and Normal chest X-rays
The model achieves good accuracy on both training and validation datasets
Some degree of overfitting may be observed due to the limited size and imbalance of medical data
Model performance can be further improved by:
Using Transfer Learning (e.g., MobileNet, ResNet)
Applying class balancing techniques
Increasing dataset size
