Project Overview -
Alzheimer's disease is a progressive neurological disorder that affects memory, thinking, and behavior. Early detection and accurate classification of Alzheimer's disease stages can help in better diagnosis and treatment planning.
This project uses a Deep Learning approach with DenseNet (Dense Convolutional Neural Network) to classify Alzheimer's disease stages from brain MRI images. The model uses transfer learning to extract important features from MRI scans and classify them into different dementia stages.

Model Used -
DenseNet (Dense Convolutional Network)
DenseNet is a convolutional neural network architecture where each layer is connected to every other layer in a feed-forward manner. These dense connections improve feature reuse, gradient flow, and model performance.

Dataset -
The project uses an Alzheimer's MRI image dataset containing four classes:
Non Demented
Very Mild Demented
Mild Demented
Moderate Demented
The dataset is not included in this repository because of its large size and licensing restrictions.

Dataset Structure -
dataset/
│
├── NonDemented/
├── VeryMildDemented/
├── MildDemented/
└── ModerateDemented/
Download the dataset from the original source and place it in the required folder structure before training.

Technologies Used - 
Python
TensorFlow
Keras
DenseNet
Google Colab
NumPy
Pandas
OpenCV
Matplotlib
Seaborn
Scikit-learn


