# Pneumonia-Detection

![image 2024-03-20 172902](https://github.com/harshrajput9934/Pneumonia-Detection/assets/90636720/d29dceac-356f-46ef-8b24-b8723fb2a79c)


#This project utilizes deep learning models to detect bacterial and viral pneumonia from chest X-rays.

# Dataset
LINK- https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

# STEPS
1.Import necessary libraries/modules.

2.Define utility functions for directory manipulation, date/time formatting, data visualization, model visualization, etc.

3.Define functions for preprocessing data, such as selecting images by category, counting files in subdirectories, plotting bar charts, etc.

4.Set up directories for input/output, training, validation, testing, and figures.

5.Define image preprocessing/augmentation parameters and create data generators for training, validation, and testing.

6.Compute class weights for training data.

7.Set up directories for model and log storage, and define callbacks for model training.

8.Define the architecture of the neural network model (CNN).

9.Load the pre-trained InceptionV3 model and fine-tune it for the new classification task.

10.Train the model using the defined parameters, data generators, and callbacks.

11.Visualize the model performance over epochs using accuracy and loss plots.

12.Test saved models by evaluating them on the test dataset.

13.Visualize predictions by displaying sample images along with their true and predicted classes.




# sample outputs
![image](https://github.com/harshrajput9934/Pneumonia-Detection/assets/90636720/e556c24c-b6be-484d-9186-b233116e6dda)



