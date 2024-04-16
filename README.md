### Diabetic Retinopathy Diagnosis Using Deep Learning

This repository contains code for deep learning-based binary diagnosis of Diabetic Retinopathy (DR) using the IDRID Disease Grading Dataset. The project focuses on leveraging convolutional neural networks (CNNs) and Inception-inspired architectures for binary classification tasks.

#### Abstract:

This project aims to develop and evaluate deep learning models for binary diagnosis of Diabetic Retinopathy (DR) using the IDRID Disease Grading Dataset. The dataset comprises retinal images annotated with binary labels indicating the presence or absence of DR. Three distinct models are employed: a custom CNN tailored for binary classification, an Inception module-inspired model for enhanced feature extraction, and a pre-trained InceptionV3 model. Among these models, the InceptionV3 model demonstrates superior performance. Training and evaluation are conducted using ImageDataGenerators, with various metrics used to assess model performance, including accuracy.

#### Directory Structure:

- `data/`: Contains the IDRID Disease Grading Dataset.
- `models/`: Includes Python files for the custom CNN, Inception module-inspired model, and InceptionV3 model.
- `notebooks/`: Jupyter notebooks for data preprocessing, model training, and evaluation.
- `README.md`: Markdown file providing an overview of the project.

## Technologies Used 🛠

- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
- ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
- ![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
- ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
- ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=python&logoColor=white)

#### Usage:

1. Clone the repository:

```bash
git clone https://github.com/kanis777/diabetic_retinopathy.git
cd diabetic-retinopathy
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Run the colab notebooks in the notebooks/ directory to preprocess data, train models, and evaluate performance.
Results:
The InceptionV3 model outperforms the custom CNN and Inception module-inspired model, achieving the highest accuracy in binary diagnosis of DR.

References:
## IDRID Disease Grading Dataset 📊

-Dataset:The [Indian Diabetic Retinopathy Image Dataset (IDRID)](https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid)
-TensorFlow: https://www.tensorflow.org/
-Keras: https://keras.io/
-NumPy: https://numpy.org/
-Pandas: https://pandas.pydata.org/
-Matplotlib: https://matplotlib.org/

### Author:
Kanishka K, Nilavini B M,Varsha S

License:
This project is licensed under the MIT License.
