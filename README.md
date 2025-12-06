## Mini-Project

# Pneumonia Detection Using FastAI & MATLAB :

A Hybrid Deep Learning and Medical Imaging Analysis System

# Overview :

1.Pneumonia is a serious lung infection that requires fast and accurate diagnosis.
2.This project implements a hybrid AI-based system combining:
3.FastAI (Deep Learning) for classifying chest X-ray images
4.MATLAB (Medical Image Processing) for enhancing images and visualizing infected lung regions
5.This approach improves diagnostic accuracy and interpretability, making it useful for medical research and educational purposes.

# Key Features :

1.Classification of Normal vs Pneumonia X-ray images
2.FastAI convolutional neural network for high accuracy
3.MATLAB-based preprocessing and enhancement
4.Visualization of suspected infected regions
5.End-to-end pipeline from input to final prediction
6.Clean and well-organized project structure

# Technologies Used

* Deep Learning
* FastAI
* PyTorch
* Google Colab
* Image Processing
* MATLAB
* Image Processing Toolbox
* Additional Tools
* NumPy
* Pillow
* Matplotlib
* Scikit-Learn

# Project Structure :

Mini-Project/
│
├── notebooks/
│   └── Pneumonia_Detection_FastAI.ipynb
│
├── matlab/
│   ├── preprocessing.m
│   ├── segmentation.m
│   └── visualize.m
│
├── results/
│   ├── confusion_matrix.png
│   ├── accuracy_plot.png
│   └── sample_predictions/
│
├── models/
│   └── pneumonia_model.pkl
│
├── requirements.txt
└── README.md

# Dataset :

This project uses the Chest X-Ray Pneumonia Dataset, which contains two classes:
1.NORMAL
2.PNEUMONIA
Due to size limitations, the dataset is not included in this repository.
It can be downloaded from Kaggle or other medical imaging sources.

# How to Run the Project :

Step 1: Clone the Repository
```
git clone https://github.com/hemreddy2005/Mini-Project.git
```
```
cd Mini-Project
```

Step 2: Install Dependencies
```
pip install -r requirements.txt
```

Step 3: Run the Training Notebook
Open the notebook:
```
notebooks/Pneumonia_Detection_FastAI.ipynb
```
Run all cells to train the model and export the .pkl file.

Step 4: MATLAB Processing

Run the MATLAB scripts inside the matlab/ folder:

* preprocessing.m
* segmentation.m
* visualize.m

These scripts enhance the X-ray image and highlight the infected lung areas.

# Outputs :

<img width="853" height="447" alt="image" src="https://github.com/user-attachments/assets/7bbef27d-0ace-4414-9e45-8df231c6c3bc" />

# Why FastAI + MATLAB ?

FastAI provides a simple and powerful interface for training deep learning models.
MATLAB provides reliable tools for medical-grade preprocessing and visualization.

Using both results in:
* High accuracy
* Better interpretability
* Cleaner visualization of pneumonia-affected lung areas

# License :

This project is licensed under the MIT License.

# Contributions and Feedback :

Contributions are welcome.
You may submit issues, feature requests, or pull requests through the GitHub repository.
