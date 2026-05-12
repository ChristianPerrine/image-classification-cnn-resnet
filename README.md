# image-classification-cnn-resnet
This project uses deep learning to classify recyclable materials (glass, plastic, paper, metal) from images. Two models are trained and compared:
A custom Convolutional Neural Network (CNN) and a  ResNet model.

How to Run the Program

Download Dataset
Download the dataset from:
https://ailab.ccec.unf.edu/recycledata.html

Upload to Google Drive
Upload the dataset zip file to your Google Drive
Place it inside a folder (example: Colab Notebooks/Recycle/)

Open Notebook
Open Recycle.ipynb in Google Colab

Mount Google Drive
Run the first cell in the notebook:
from google.colab import drive
drive.mount('/content/drive')
Allow access when prompted.

Set Dataset Path
Update the file path in the code to match your Google Drive location:
Example:/content/drive/MyDrive/Colab Notebooks/Recycle/recycle.zip

Run the Program
Click:
Runtime -> Run all
The notebook will:Extract the dataset,split it into training, validation, and test sets,train both CNN and ResNet models,evaluate performance on test data and display comparison graphs

Notes
Full training may take several hours (CNN 1 hour, ResNet 2–3 hours)
Ensure the dataset path is correct before running
Do not delete or move files while the program is running

Output
The program prints:
CNN accuracy on test data,ResNet accuracy on test data,Graph comparing model performance over training epochs
