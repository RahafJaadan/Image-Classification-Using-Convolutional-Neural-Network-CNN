# Image Classification Project - CIFAR-10 
This project demonstrates image classification using deep learning on the CIFAR-10 dataset. Initially, we implemented a simple Artificial Neural Network (ANN) for classification; however, the accuracy was suboptimal. We then improved the model by using a Convolutional Neural Network (CNN), which achieved better performance.

## Dataset 
* **Source**: CIFAR-10
* **Description**: CIFAR-10 is a widely used dataset that contains 60,000 32x32 color images in 10 different classes.

 ## Models
 1. **ANN** - Initial model; low accuracy due to limitations in capturing spatial features.
 2. **CNN** - Improved model that leverages convolutional layers to better capture image features and enhance classification accuracy.

 ## Libraries 
* **TensorFlow** - Model building and training
* **Keras** - High-level API for deep learning, integrated with TensorFlow
* **NumPy** - Numerical operations and data manipulation
* **Matplotlib** - Visualization of results 
* **scikit-learn.metrics** - Evaluation metrics for model performance

## Results
• The CNN model significantly outperformed the ANN in accuracy, demonstrating the effectiveness of convolutional layers for image data.

 ## Usage 
 1. Clone the repository.
 2. Install the required libraries.
 3. Run the model training script.

## Future Improvements
* Experiment with hyperparameter tuning.
* Implement data augmentation techniques to further improve accuracy.
