# Melanoma Assignment Using CNN



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Project Background
Skin cancer is one of the most prevalent forms of cancer worldwide, and early detection plays a crucial role in improving survival rates. However, diagnosing skin cancer requires expertise in dermatology, which is not always accessible in remote areas. The use of deep learning techniques, particularly Convolutional Neural Networks (CNNs), can assist in automating the detection of different types of skin cancer from dermoscopic images, making early diagnosis more efficient and accessible.

### Business Problem
The primary business problem this project addresses is improving the accuracy and accessibility of skin cancer diagnosis using AI. Traditional methods of skin cancer detection rely on dermatologists manually analyzing skin lesion images, which can be time-consuming, costly, and subject to human error. By leveraging AI-powered image classification, this project aims to:

- Assist medical professionals by providing a secondary opinion.
- Enhance early detection to improve patient outcomes.
- Make diagnosis accessible in regions with a shortage of dermatologists.

### Dataset Information
The dataset used in this project is the ISIC (International Skin Imaging Collaboration) Skin Cancer Dataset, a widely used dataset for skin cancer classification. It consists of dermoscopic images of different types of skin lesions, including benign and malignant cases. The dataset is divided into 9 classes, representing different types of skin conditions.

- Dataset Source: ISIC Archive (publicly available medical dataset)
- Number of Classes: 9
- Types of Skin Lesions: Includes categories such as Melanoma, Basal Cell Carcinoma, and Benign Nevi.
- Image Format: JPG images with varying resolutions.
- Dataset Split: Training and Testing folders with images categorized into respective classes.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 1 & 2: 
    Had low accuracy and high validation loss fluctuations, indicating underfitting and poor generalization.
- Model 3: 
    Showed some improvement, but validation accuracy was inconsistent, suggesting overfitting.
- Model 4: 
    Introduced dropout layers, leading to more stable training, but validation accuracy was still volatile.
- Model 5: 
    Implemented batch normalization, significantly improving training accuracy, but validation accuracy remained unstable, indicating potential overfitting or dataset imbalance.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow
- Keras
- NumPy 
- pandas
- Matplotlib 
- PIL (Pillow)
- Pathlib
- os 
- random

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was inspired by the Skin Cancer ISIC – The International Skin Imaging Collaboration, which aims to develop AI models for early skin cancer detection.
The dataset used in this project is sourced from the ISIC dataset, a well-known benchmark dataset for skin lesion classification.


## Contact
Created by [@tallbrat] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
