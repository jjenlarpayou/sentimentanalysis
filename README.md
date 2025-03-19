# Sentimentanalysis
# Concretecrackdetection
## Overview
<p></p>

## How to Run the Project ##
The project used crack surface from https://www.kaggle.com/code/zeynel7/detection-of-surface-crack-using-cnn. The dataset contains concrete images of not having any cracks and having cracks. Each type of surface consists of 20000 positive and 20000 negative images  with 227 x 227 pixels with RGB channels.

### Prerequisites
#### **1. Required Software**
- **Python 3.x** ([Download Here](https://www.python.org/downloads/))
- **TensorFlow & Keras** (For deep learning)
- **OpenCV** (For image processing)
- **scikit-learn** (For machine learning models)
- **Matplotlib & Seaborn** (For data visualization)
- **NumPy & Pandas** (For numerical and data manipulation)
- **TQDM** (For progress bars)
- **IPython** (For interactive shell)
- **Glob** (For file handling)

## Key Features
### Image Processing
Images were resized and converted into grayscale with (100x100 pixels) to enhance the model performance.
<div align="center"><img width="300" alt="image" src="https://github.com/user-attachments/assets/fdef99a9-9910-48d8-ae71-b46875931be7" />
</div>
<div align="center"><b>Figure 1: </b>Samples of grayscale conversion</div>

### Model Development 
The MLP model was trained with fixed epoch (100) and different configurations like neurons with and without regularization(dropout), learning rate, and batch size to optimize the model.
### Model Evaluation
The project includes multiple metrics like accuracy, precision, recall, f1-score and others(ROC-curve and confusion matrix) to assess the model performance.
#### - Accuracy: 96.38%
#### - Precsion: 97.53
#### - Recall: 95.13
#### - F1-Score: 96.32

## Result
<div align="center"><img width="300" alt="image" src="https://github.com/user-attachments/assets/f1b04e25-e07e-4ce5-81e8-f1941df14f22" />

</div>
<div align="center"><b>Figure 2: </b>ROC-Curve</div>
<div align="center"><img width="400" alt="image" src="https://github.com/user-attachments/assets/161d38b0-e9ad-4491-957a-1c36d29eb5d0" />
</div>
<div align="center"><b>Figure 3: </b>Confusion matrix 
</div>
