# PDAN8412 Part 3

## Image Classification using CNN

## Overview

SA Book Press a library and print shop wants to improve business and inventory operations through the use of CNN image recognition. Using an annotated object dataset (PASCAL), create a CNN model from scratch to classify images.



## Dataset

The dataset used in this project is the The PASCAL Visual Object Classes

Dataset:
https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/

It contains annotated XML files with paired images.

Using a subset of the full dataset, being just the JPEG Files folder and Annotations folder

## Tools and Libraries

- Python
- PySpark
- pandas
- NumPy
- scikit-learn
- NLTK
- Matplotlib
- Plotly
- XGBoost
- OpenCV

## Environment Setup

This project was run with the following environment and package versions:

- Python: 3.13.5
- Java: 25.0.4
- pandas: 2.3.3
- PySpark: installed through pip to match the local Python and Java setup
- scikit-learn: used for encoding, train/test splitting, and evaluation
- xgboost: alternative model

### Installation steps used for this project

1. Create and activate a virtual environment

```bash
python -m venv PDANp3venv
PDANp1venv\Scripts\activate
```

2. Upgrade pip

```bash
python -m pip install --upgrade pip
```

3. Install the required packages

```bash
pip install pandas==2.3.3
pip install nltk
pip install pyspark
pip install numpy
pip install scikit-learn
pip install tensorflow
pip install nbformat
pip install plotly
pip install PyArrow
pip install wordcloud
pip install seaborn
pip install xgboost
pip install opencv-python
pip install ElementTree
```

4. Install Java 25.0.4 and add it to the system PATH

On Windows, install Java 25.0.4 and set the environment variables:

```powershell
setx JAVA_HOME "C:\Program Files\Java\jdk-25"
setx PATH "%JAVA_HOME%\bin;%PATH%"
```

## Requirements

- Python environment with Jupyter support
- PySpark installed and configured correctly
- TensorFlow and Keras available
- NLTK data files downloaded for tokenization and stopwords
- Java 25.0.4 installed and available on PATH
- Access to the dataset file blogtext.csv


## References

[1] “3.3. Tuning the decision threshold for class prediction,” scikit-learn. Accessed: Oct. 21, 2026. [Online]. Available: https://scikit-learn/stable/modules/classification_threshold.html


[2] “PySpark Tutorial,” GeeksforGeeks. Accessed: Oct. 21, 2026. [Online]. Available: https://www.geeksforgeeks.org/python/pyspark-tutorial/


[3] “Deep Convolutional Neural Networks for Computer-Aided Detection: CNN Architectures, Dataset Characteristics and Transfer Learning,” IEEE Trans Med Imaging, vol. 35, no. 5, pp. 1285–1298, Feb. 2016, doi: 10.1109/TMI.2016.2528162.


[4] M. Krichen, “Convolutional Neural Networks: A Survey,” Computers, vol. 12, no. 8, p. 151, Aug. 2023, doi: 10.3390/computers12080151.


[5] “Convolutional Neural Network (CNN) | TensorFlow Core,” TensorFlow. Accessed: Nov. 19, 2026. [Online]. Available: https://www.tensorflow.org/tutorials/images/cnn


[6] “Introduction to Convolution Neural Network,” GeeksforGeeks. Accessed: Nov. 19, 2026. [Online]. Available: https://www.geeksforgeeks.org/machine-learning/introduction-convolution-neural-network/


[7] “OpenCV: OpenCV-Python Tutorials.” Accessed: Nov. 19, 2026. [Online]. Available: https://docs.opencv.org/4.13.0/d6/d00/tutorial_py_root.html


