Objective
The goal of this project is to develop a Convolutional Neural Network (CNN) model capable of classifying chest X-ray images into two categories:
•	Normal 
•	Pneumonia 
The model automatically determines whether a patient is affected by pneumonia based on X-ray images.
Dataset Description
The dataset consists of 5,863 chest X-ray images collected from pediatric patients aged 1 to 5 years.
Dataset Structure
train 
      NORMAL
     PNEUMONIA
value
    NORMAL
    PNEUMONIA
test
    NORMAL
    PNEUMONIA
Key Points
•	All images are in JPEG format 
•	Training dataset: Used to train the model 
•	Validation dataset: Used to monitor performance during training 
•	Test dataset: Used to evaluate final model accuracy


Methodology
    Step 1 – Data Preprocessing
Images are loaded using ImageDataGenerator.
Preprocessing steps:
•	Resize images to 150 × 150 pixels 
•	Normalize pixel values (scale between 0 and 1) 
•	Automatically assign labels from folder names 

   Step 2 – CNN Model Architecture
A Convolutional Neural Network (CNN) is used for classification.
Model Layers:
1.	Convolution Layer – Extracts features from images 
2.	MaxPooling Layer – Reduces spatial dimensions 
3.	Convolution Layer 
4.	MaxPooling Layer 
5.	Convolution Layer 
6.	Flatten Layer – Converts 2D data into 1D 
7.	Dense Layer – Learns complex patterns 
8.	Output Layer – Predicts class (Normal / Pneumonia) 
Activation Functions:
•	ReLU → Used in hidden layers 
•	Sigmoid → Used in output layer 

  
  Step 3 – Model Training
Training Configuration:
•	Optimizer: Adam 
•	Loss Function: Binary Crossentropy 
•	Evaluation Metric: Accuracy 
•	Epochs: 10 
The model learns patterns from the training dataset during this phase.

   Step 4 – Model Evaluation
The trained model is evaluated using the test dataset.
Final Accuracy:
0.7099 (≈ 71%)
This means the model correctly classifies approximately 71 out of 100 images.

Result
The CNN model is able to successfully detect pneumonia from chest X-ray images.
Although the accuracy is moderate, the model demonstrates the effectiveness of deep learning in medical image classification tasks.
  
Conclusion
Convolutional Neural Networks (CNNs) are highly effective for image classification, especially in healthcare applications such as disease detection.

