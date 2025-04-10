# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: VIDITH SOMANNA C

*INTERN ID*: CT04WA143

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

This project implemented a Decision Tree model to classify images from the CIFAR-10 dataset, which consists of 60,000 32x32 color images across 10 classes (airplanes, cars, birds, etc.). Decision Trees are typically used for structured data but here we adapted them for basic image recognition to demonstrate fundamental machine learning concepts. The workflow involved loading and normalizing the image data, then training a Decision Tree classifier using scikit-learn's DecisionTreeClassifier. The model achieved approximately 45-50% accuracy, which is modest compared to neural networks but provides valuable insights into how machine learning models interpret pixel data.

Decision Trees work by recursively splitting the dataset based on feature values (in this case, pixel intensities) to maximize information gain at each node. For images, this means the tree learns thresholds on pixel values that best separate different classes. While not as powerful as CNNs for image tasks, this approach helps beginners understand how classification models make decisions. The project also visualized the tree structure, showing how it partitions the feature space.

Real-world applications include medical imaging (classifying X-rays), agricultural monitoring (crop disease detection), and quality control in manufacturing (identifying defective products). The limitations are clear—Decision Trees struggle with complex spatial hierarchies in images—but the project serves as an excellent introduction to both computer vision and interpretable ML models. The entire implementation was done in Google Colab, leveraging free cloud GPUs for efficient computation.

