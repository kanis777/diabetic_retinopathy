### Diabetic Retinopathy Diagnosis Using Deep Learning

This repository contains code for deep learning-based binary diagnosis of Diabetic Retinopathy (DR) using the IDRID Disease Grading Dataset. The project focuses on leveraging convolutional neural networks (CNNs) and Inception-inspired architectures for binary classification tasks.

#### Abstract:

This project aims to develop and evaluate deep learning models for binary diagnosis of Diabetic Retinopathy (DR) using the IDRID Disease Grading Dataset. The dataset comprises retinal images annotated with binary labels indicating the presence or absence of DR. Three distinct models are employed: a custom CNN tailored for binary classification, an Inception module-inspired model for enhanced feature extraction, and a pre-trained InceptionV3 model. Among these models, the InceptionV3 model demonstrates superior performance. Training and evaluation are conducted using ImageDataGenerators, with various metrics used to assess model performance, including accuracy.

#### Directory Structure:

- `data/`: Contains the IDRID Disease Grading Dataset.
- `models/`: Includes Python files for the custom CNN, Inception module-inspired model, and InceptionV3 model.
- `notebooks/`: Jupyter notebooks for data preprocessing, model training, and evaluation.
- `README.md`: Markdown file providing an overview of the project.

#### Requirements:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib

#### Usage:

1. Clone the repository:

```bash
git clone https://github.com/username/diabetic-retinopathy.git
cd diabetic-retinopathy
