# Classification-and-Detection-of-Melanoma-Skin-Cancer-Using-Neural-Networks
This repository houses the research and implementation code for a deep learning approach to melanoma detection, an aggressive form of skin cancer. By leveraging Convolutional Neural Networks (CNNs) and dermoscopic images, this project aims to provide a reliable, efficient, and accessible method for early melanoma detection.

Overview
Melanoma is known for its potential to spread rapidly and aggressively if not detected at an early stage. This research focuses on harnessing deep learning to analyze dermoscopic images, aiming to accurately classify skin lesions as malignant or benign. The model, based on CNNs, is specifically designed to capture essential features critical for this classification task.

Repository Contents
Code-EDA.ipynb: This notebook provides an extensive exploratory data analysis of the dermoscopic images used in this study. It includes data visualization, class distribution analysis, and other statistical examinations to understand the dataset better before model implementation.

Code-10 epochs.ipynb: Here, we dive into the model creation, training, and evaluation. The notebook details the process of building a CNN, deciding on the architecture specifics, and training it on the skin lesion images. It also includes a comprehensive evaluation section, where the model's diagnostic capabilities are assessed based on various metrics.

Key Findings
The CNN model showcased impressive diagnostic capabilities, with preliminary results indicating an accuracy rate exceeding 80% on the ISIC 2019 and ISIC 2020 datasets. This performance underscores the potential of deep learning in enhancing early detection and treatment approaches for melanoma.

Datasets
The datasets used for this research were sourced from the ISIC 2019 and ISIC 2020 challenges, known for their diverse and high-quality dermoscopic images. These datasets provide a rigorous testing ground for the model, contributing to its robustness and reliability.

Dataset Link: ISIC 2019 and 2020 Melanoma Dataset - https://www.kaggle.com/datasets/qikangdeng/isic-2019-and-2020-melanoma-dataset

Technologies Used
Python
Pandas
Matplotlib
NumPy
PyTorch
Scikit-learn
Installation
To set up the necessary environment, run the following command in the repository's directory:

Copy code
pip install -r requirements.txt
Usage
Clone the repository to your local machine.
Acquire the datasets from the provided link and place them in the designated directory.
Run the Jupyter notebooks in order to replicate the analysis and model training.
Contribution
Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Ankur Napa - Napaankur@gmail.com - LinkedIn - https://www.linkedin.com/in/ankur-napa/
