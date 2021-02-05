### 🚗Distracted Driver MultiAction Classification
This notebook builds an end-to-end multi class multi label prediction for stack overflow questions.

## 1. Problem

Our goal is to predict the likelihood of what the driver is doing in each picture.

We need to classify images into these 10 classes 

* c0: safe driving
* c1: texting - right
* c2: talking on the phone - right
* c3: texting - left
* c4: talking on the phone - left
* c5: operating the radio
* c6: drinking
* c7: reaching behind
* c8: hair and makeup
* c9: talking to passenger

## 2. Data

The data we're using is from Kaggle's State Farm Distracted Driver Detection.

https://www.kaggle.com/c/state-farm-distracted-driver-detection/data


## 3. Features

**Some information about the data:**

In this competition we are given driver images, each taken in a car with a driver doing something in the car (texting, eating, talking on the phone, makeup, reaching behind, etc). 

#### This is organized as three tables:


* **imgs.zip** - zipped folder of all (train/test) images.
* **sample_submission.csv** - a sample submission file in the correct format.
* **driver_imgs_list.csv** - a list of training images, their subject (driver) id, and class id.
