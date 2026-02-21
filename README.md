# 😊 Happy & Sad Mood Classification using Deep Learning

This project implements a Convolutional Neural Network (CNN) to classify facial expressions into two emotional categories: Happy and Sad.
The model is trained on labeled image data and is capable of predicting the emotional state from new input images.

This project demonstrates practical knowledge of:

-Image preprocessing

-Deep learning model building

-Model evaluation

-Performance visualization

### Objective

To build an image classification model that accurately identifies emotional expressions (Happy or Sad) using Deep Learning techniques.

### Tech Stack

-Programming Language: Python

-Libraries: NumPy, Pandas, Matplotlib

-Deep Learning Framework: TensorFlow / Keras

-Model Type: Convolutional Neural Network (CNN)

-Development Environment: Jupyter Notebook,Google Colab

### Model Architecture

-Input Layer (Resized Image)

-Convolutional Layers

-Max Pooling Layers

-Flatten Layer

-Dense Layers

-Output Layer (Binary Classification – Happy/Sad)

##### Activation Functions Used:

-ReLU

-Sigmoid (Output Layer)

##### Loss Function:

-Binary Crossentropy

##### Optimizer:

-Adam

### Project Structure

Happy-Sad-Mood-Classification/

│

├── training/

│   ├── happy/

│   └── sad/

│

├── validation/

│   ├── happy/ 

│   └── sad/  

│

└── testing/

│

├── Happy&Sad_MoodClassificaton.ipynb

├── README.md


#### How Many Images Should Be in Validation?

##### Common split:

70% → Training

15% → Validation

15% → Testing

Example:
If you have 200 images:

140 → training

30 → validation

30 → testing

#### What Accuracy Means

Training Accuracy → How well model performs on training data

Validation Accuracy → How well model performs on unseen validation data

### Model Performance

Training Accuracy: 0.95

Validation Accuracy: 0.87

### How to Run the Project

##### 1.Clone the repository:

git clone https://github.com/gouthamibogoji-ui/Happy-Sad-Mood-Classification.git

##### 2.Navigate to the project folder.

##### 3.Install required libraries:

pip install -r requirements.txt

##### 4.Open Jupyter Notebook or GoogleColab and run:

Happy&Sad_MoodClassificaton.ipynb


### Author

Gouthami Bogoji

Machine Learning Enthusiast




