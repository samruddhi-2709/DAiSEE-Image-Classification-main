# DAiSEE Image Classification

This project aims to classify images from the DAiSEE dataset into five categories: Boredom, Engagement, Confusion, Frustration, and Neutral. We utilized a Convolutional Neural Network (CNN) for this task, specifically employing the EfficientNetB0 architecture.

## Project Overview

The DAiSEE dataset provides a comprehensive set of images for detecting different states of user engagement. This project leverages the power of CNNs to automatically classify these images into predefined categories. The goal is to create a model that can accurately identify the engagement state of individuals based on their facial expressions.

## DAiSEE Image DataSet
The DAiSEE dataset provides a comprehensive set of images for detecting different states of user engagement. 
To access the dataset, go to the following link:
https://people.iith.ac.in/vineethnb/resources/daisee/index.html

MY DATASET LINK: 
https://drive.google.com/drive/folders/1iZvMsAbbRDvDnw0swsWAv61amzB_u_7Z?usp=sharing

## Methodology

1. **Data Preprocessing**: 
   - Images were resized to match the input size required by EfficientNetB0.
   - Normalization was applied to ensure consistent input data.

2. **Model Architecture**:
   - We used EfficientNetB0, a state-of-the-art CNN architecture known for its efficiency and accuracy.
   - The base model was pre-trained on ImageNet and fine-tuned on the DAiSEE dataset.
   - The final layers were modified to suit our classification task with five output classes.

3. **Training**:
   - The model was trained using the Adam optimizer and categorical cross-entropy loss.
   - Training and validation data were used to monitor the model’s performance and prevent overfitting.

4. **Evaluation**:
   - The trained model was evaluated on a separate test set.
   - Metrics such as accuracy and loss were used to assess the model's performance.

## Results

The model achieved the following performance metrics on the test set:

- **Accuracy**: 94.62%
- **Loss**: 0.2807

These results indicate that the model is highly effective in classifying the different states of engagement in the DAiSEE dataset.

## Conclusion

This project demonstrates the capability of CNNs, specifically EfficientNetB0, in the field of image classification for engagement recognition. The high accuracy achieved suggests that this approach can be used for practical applications in educational technology, user experience research, and other domains requiring automatic engagement detection.
