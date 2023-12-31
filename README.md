# Driver-Drowsiness-Detection
Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fell asleep while driving. This technology will alert the driver when drowsiness is detected.

<img align="right" alt="GIF" height=200 src="https://github.com/rudrabarad/Driver-Drowsiness-Detection/blob/main/driver.gif" />

## Contents of the Repository
- [CNN Approach](https://github.com/rudrabarad/Driver-Drowsiness-Detection/tree/main/DDDS_CNN)
- [Transfer Learning Approach](https://github.com/rudrabarad/Driver-Drowsiness-Detection/tree/main/Transfer_learning)
- [Readme](https://github.com/rudrabarad/Driver-Drowsiness-Detection#readme)
- [Dataset](https://github.com/rudrabarad/Driver-Drowsiness-Detection#dataset)
- [Required Libraries](https://github.com/rudrabarad/Driver-Drowsiness-Detection#required-libraries)
- [Installation Setup](https://github.com/rudrabarad/Driver-Drowsiness-Detection#installation-setup)
- [Results](https://github.com/rudrabarad/Driver-Drowsiness-Detection#results)
- [Research Article](https://github.com/rudrabarad/Driver-Drowsiness-Detection/blob/main/Research%20Article.docx)
- [Video Demonstration](https://github.com/rudrabarad/Driver-Drowsiness-Detection#video)

## Dataset
Sorry we were not able to upload dataset on GitHub due to size limitation :octocat: <br>
But you can find the links to download the dataset from the following text files
1. For CNN - [Dataset.txt](https://github.com/rudrabarad/Driver-Drowsiness-Detection/blob/main/DDDS_CNN/Dataset.txt)
2. For Transfer Learning - [get_dataset.txt](https://github.com/rudrabarad/Driver-Drowsiness-Detection/blob/main/Transfer_learning/get_dataset.txt)

## Required Libraries
- keras
- cv2
- pygame
- numpy
- matplotlib
- glob
- tqdm

## Installation Setup
#### 1. Clone the repository
You can clone this repository using command: ``git clone https://github.com/rudrabarad/Driver-Drowsiness-Detection.git``
#### 2. Training respective model
- For CNN open and run ``DDDS_CNN/model_training.py``
- For Transfer Learning open and run ``Transfer_learning/Model_Training_TL.ipynb`` 

#### 3. Execute all the cells consecutively to see the accuracy of both models.
#### 4. Execute programs using the models
- For CNN run ``DDDS_CNN/main_capture.py``
- For Transfer Learning run ``Transfer_learning/tl_capture.py``

> **Note:** Currently there is no **Models** folder in both CNN & Transfer folders but it will be created as soon as user executes model training file

## Results
Approach| Training Accuracy | Validation Accuracy
------------ | ------------------|--------------------
CNN | 99.01% | 95.19%
Transfer Learning | 82% |  79%
 
