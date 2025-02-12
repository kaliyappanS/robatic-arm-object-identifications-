# Medical Image Processing for Disease Detection

This project focuses on the detection of diseases, specifically COVID-19, using medical imaging techniques. The goal is to classify CT scan images into two categories: COVID-19 positive and COVID-19 negative. The project leverages deep learning models to achieve this classification.

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The project aims to automate the detection of COVID-19 from CT scan images using convolutional neural networks (CNNs). By training a model on a dataset of labeled CT scans, we can predict whether a new CT scan is positive or negative for COVID-19.

## Technologies Used
- **Python**: The primary programming language used for this project.
- **TensorFlow/Keras**: For building and training the deep learning model.
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Scikit-learn**: For data splitting and evaluation metrics.
- **OpenCV**: For image processing tasks.

## Dataset
The dataset used in this project consists of CT scan images labeled as either COVID-19 positive or negative. The dataset is divided into training and testing sets to evaluate the model's performance.

- **COVID-19 CT Scans**: 1252 images
- **Non-COVID-19 CT Scans**: 1229 images

## Installation
To set up the project on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Medical-Image-Processing-for-Disease-Detection.git
   cd Medical-Image-Processing-for-Disease-Detection
