# Emotion Recognition through Facial Expressions.

Model Building:
The emotion recognition model is build using the following steps
1)Preprocessing the data using the imageDatagenrator for training and validation data
2)Using the Haarcascade file to recognise the objects as images for emotion recognition.
3)Creating two models for checking which has better accuracy by using optimizers and loss functions.
4)Evaluating the models performance using the validation data.

#  DATA SET

We have used Fer2013 dataset for this process we can get the dataset in the kaggle .

https://www.kaggle.com/datasets/deadskull7/fer2013

Download the fer data set and keep it in the same path for the results.


Running Process.

1)Run the Preprocessing file for preprocessing the data and  saving the images into separate folders based on their labels. It splits the dataset into a training set and a test set, and saves the images accordingly.

2)Run the CNN and Resnet file for validation accuracy for sepearetely.


Results:
![model accuracy](https://github.com/preethamveerepalli/Final_project/assets/59497185/216bd90f-ab0e-48ce-bf7e-64affbe6d312)
 CNN RESULTS
 
 
![Resnet](https://github.com/preethamveerepalli/Final_project/assets/59497185/0cae3d2b-dda9-4c58-a3c4-66878749f309)

ResNet.



