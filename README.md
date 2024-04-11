# Project Name
> This project focuses on building a custom convolutional neural network (CNN) using TensorFlow for multiclass classification of skin diseases, particularly melanoma. The goal is to accurately detect melanoma from image data obtained from the International Skin Imaging Collaboration (ISIC) dataset. By automating the detection process, the project aims to contribute to early diagnosis and treatment of melanoma, a deadly form of skin cancer. The dataset consists of 2357 images categorized into various skin diseases, providing a diverse set of samples for training and validation. The project pipeline includes data preprocessing, model building, training, and evaluation to develop an effective solution for melanoma detection.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information


* This project aims to build a multiclass classification model using a custom convolutional neural network (CNN) in TensorFlow. The model is designed to accurately detect various skin diseases, including melanoma, using image data.

* Skin cancer, particularly melanoma, is a significant public health concern worldwide. Early detection of melanoma is critical for effective treatment and improved prognosis. However, diagnosing melanoma accurately can be challenging due to its visual similarity to benign skin lesions.

* The business problem this project addresses is the accurate detection of melanoma through automated image analysis. Melanoma is a deadly form of skin cancer that accounts for a significant portion of skin cancer-related deaths. Detecting melanoma early can significantly improve patient outcomes by enabling timely treatment interventions.


* The dataset used in this project comprises 2357 images of malignant and benign oncological diseases obtained from the International Skin Imaging Collaboration (ISIC). These images are categorized into various skin diseases, including melanoma, nevus, squamous cell carcinoma, etc. Each image is labeled with its corresponding disease category for supervised learning.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
* The implementation of class rebalancing effectively mitigated overfitting issues, consequently leading to a decrease in loss. However, this improvement came at the cost of a notable reduction in accuracy.

* Initially, the absence of ImageDataGenerator resulted in significant data overfitting.

* The subsequent inclusion of dropout and ImageDataGenerator techniques successfully alleviated overfitting concerns.

* Finally, the utilization of Batch Normalization and Augmentation strategies significantly contributed to ongoing improvements in the model's performance.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow 2.15.0
- numpy 1.25.2
- pandas 2.0.3
- PIL 9.4.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- I got to work on this project due to Upgrad learning platform
- This project was based on [this tutorial](https://learn.upgrad.com/course/4705/segment/47956/289239/880085/4398556).


## Contact
Created by [@mayur200] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
