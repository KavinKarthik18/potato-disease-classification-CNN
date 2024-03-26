##Potato Leaf Disease Classification with CNN

##disease classification:
1. Late Blight
2. Early Blight
(OTHERWISE HEALTHY)

##Model Architecture:
Implemented a convolutional neural network (CNN) model using TensorFlow, comprising successive convolutional layers for feature extraction and classification.
Utilized rectified linear unit (ReLU) activation functions within each convolutional layer to introduce non-linearity and enhance model expressiveness.
Employed max-pooling layers to downsample feature maps, reducing spatial dimensions and computational complexity.

##Dataset Splitting:
Partitioned the dataset into training, validation, and testing subsets, with 80% allocated for training, 10% for validation, and 10% for testing.
Ensured balanced representation across subsets to promote model generalization and performance evaluation.

##Data Augmentation and Optimization:
Applied data augmentation techniques using TensorFlow's 'AUTOTUNE' and 'keras.Sequential' rotation+flip functions to increase dataset variability and improve model robustness.
Implemented dataset caching and shuffling with a buffer size of 1000 to optimize training efficiency and prevent overfitting.

##Model Compilation:
Compiled the model using the Adam optimizer to adaptively adjust learning rates and facilitate efficient gradient descent during training.
Utilized SparseCategoricalCrossentropy loss function to compute the categorical cross-entropy loss between predicted and true labels.
Employed accuracy as the evaluation metric to assess the model's performance on both training and validation datasets.

##Performance Evaluation:
Achieved a notable accuracy of 82.3% on the validation dataset, indicative of the model's ability to accurately classify input samples from the dataset.
The model's success underscores its effectiveness in learning and extracting meaningful features from the dataset, leading to improved classification performance.
