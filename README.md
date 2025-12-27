# Medical-Imaging
This project focuses on the automated detection of brain tumors using Convolutional Neural Networks (CNN) applied to MRI brain images. Brain tumors are life-threatening conditions where early and accurate diagnosis plays a crucial role in patient treatment and survival. Manual analysis of MRI scans is time-consuming and prone to human error, making AI-based solutions highly valuable in medical imaging.

The model is trained on a publicly available Brain MRI dataset from Kaggle, consisting of tumor and non-tumor images. Extensive data preprocessing techniques such as image resizing, normalization, and data augmentation (rotation, flipping, zooming) are applied to improve model generalization and reduce overfitting. The dataset is split into training and testing sets to evaluate performance effectively.

A CNN architecture is designed using layers such as Conv2D, MaxPooling, Dropout, Flatten, and Dense, with activation functions including ReLU and Sigmoid. The model is implemented using Python with TensorFlow and Keras, and optimized using the Adam optimizer with binary cross-entropy loss. Training is conducted over multiple epochs to achieve high classification accuracy.

Model performance is evaluated using metrics like accuracy, precision, recall, along with confusion matrix and classification reports. The trained network achieves strong results, demonstrating its ability to reliably distinguish between tumor and non-tumor MRI scans. Sample predictions and visualization of results are included for better interpretability.

This project highlights the potential of deep learning in medical diagnosis and serves as an educational resource for students and researchers interested in healthcare AI. Future improvements include using larger datasets, applying transfer learning models such as VGG16 or ResNet50, and deploying the model as a web or mobile application for real-time clinical use.
