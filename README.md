# Multi Class Image Classifier

You can download the dataset used in my notebook from kaggle in the link provided below:
https://www.kaggle.com/fushenggg/3-class-cat-dog-car-dataset

Unzip the file and drag the 'cat-dog-car' folder into your current working directory
Download the ipynb file and make the following changes to the directory

To view your CWD
import os
os.getcwd()

Mine is 'C:\\Users\\kansh\\Desktop\\FYP'

There are TWO WAYS to LOAD the folder from directory path

1. filenames = os.listdir('C:\\Users\\kansh\\Desktop\\FYP\\cats_dogs_cars\\train')
       OR
2. filenames = os.listdir('cats_dogs_cars\\train') 

Once you finish specifying all directory path for train_generators etc, you can run the whole file and create your first CNN model
