# Melanoma Detection CNN Assignment
CNN Model Development for detecting Melanoma Skin Cancer among various skin diseases


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- To build a multiclass classification model using a custom convolutional neural network in TensorFlow. 
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions

- The final model demonstrates a strong and balanced performance, showing no indication of either underfitting or overfitting.

- The application of class rebalancing has significantly improved the model’s performance on both training and validation sets.

- The minimal gap between training and validation accuracies highlights the strong generalization ability of the final CNN model.

- The inclusion of batch normalization did not lead to any improvement in training or validation accuracy.

## Technologies Used
- tensorflow
- PIL
- numpy
- pandas
- matplotlib

## Acknowledgements

- This project was based on assignment as part of IIITB Upgrad Executive PG Program. Special thanks to the course instructors and IIITB faculty.

## Contact
Created by [@ggkarthik04] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
