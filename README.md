### &#x20;        **Handwritten Digit Classification using Deep Learning**

#### 

#### Project Overview



This project implements a Deep Learning model using TensorFlow and Keras to classify handwritten digits (0–9) from the MNIST dataset. The model is trained on grayscale images of handwritten digits and predicts the digit represented in an input image.

#### 

#### Objective



The objective of this project is to build, train, evaluate, and save a deep learning model for image classification using the MNIST dataset.



#### Dataset



MNIST Handwritten Digits Dataset



* Training Images: 60,000
* Testing Images: 10,000
* Image Size: 28 × 28 pixels
* Number of Classes: 10 (Digits 0–9)



#### Technologies Used



* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook



#### Project Workflow



1\. Load the MNIST dataset.

2\. Visualize sample images.

3\. Normalize image pixel values.

4\. Build a Deep Learning model using Keras Sequential API.

5\. Train the model.

6\. Evaluate model performance.

7\. Plot training and validation accuracy curves.

8\. Plot training and validation loss curves.

9\. Save the trained model.

10\. Perform inference on test images.



#### Model Architecture



\* Flatten Layer

\* Dense Layer (128 neurons, ReLU activation)

\* Dense Output Layer (10 neurons, Softmax activation)



Total Parameters: 101,770



#### Evaluation Metric



\* Accuracy



#### Results



The model achieved high classification accuracy on the MNIST test dataset and successfully predicted handwritten digits.



#### How to Run



* Install Required Libraries



pip install tensorflow numpy matplotlib



* Open Jupyter Notebook



* Open Project Notebook



Deep\_Learning\_Digit\_Classification.ipynb



* Run All Cells



Execute all notebook cells from top to bottom.



* Saved Model



The trained model is saved as:



digit\_classifier\_model.h5



#### Project Structure



DeepLearning\_Classification\_Project/



├── Deep\_Learning\_Digit\_Classification.ipynb



├── digit\_classifier\_model.h5



├── README.md



├── Report.pdf



└── screenshots/







