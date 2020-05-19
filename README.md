# MUST READ #

# *All notebooks, saved models and dataset folders must be inside your CWD

# Download Dataset & Saved Model
https://www.kaggle.com/fushenggg/3-class-cat-dog-car-dataset

*Contains SavedModel1.h5 file to load model (Saves time from training)

Unzip the file and place the 'cat-dog-car' folder into your CWD (current working directory) 

Download the ipynb files and place in CWD

Drag the saved model and place in CWD 

# Running the notebook 
1. Check where your CWD is located at

To view your CWD import os os.getcwd()

Mine is 'C:\Users\kansh\Desktop\FYP'

2. Loading of folder from CWD (Changes to make)

Windows uses "\\" & Linux uses "//" for directory path

3. Ensure all directory path for train_generators are specified as well

# There are TWO WAYS to LOAD the folder from directory path
1. filenames = os.listdir('C:\\Users\\kansh\\Desktop\\FYP\\cats_dogs_cars\\train\\'

2. filenames = os.listdir('cats_dogs_cars\\train')

