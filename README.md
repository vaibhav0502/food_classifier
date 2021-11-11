# food_classifier

## 1.Business Problem:

### 1.1 Description
1. [Dataset is taken from kaggle.](https://www.kaggle.com/rajaraman6195/recipes)
2. Dataset consist of different food listings of images. The dataset includes the set of images for each recipes.
3. [Check Implementation from Kaggle](https://www.kaggle.com/vaibhavkumbhar/food-classifier)

### 1.2 Problem Statemtent:
To build a CNN based model which can accurately detect food.

## 2.Dataset:
The dataset contains 5 sub-directories of food images.
- biryani
- burger
- dosa
- idly
- pizza

## 3.Buid CNN Model:
### 3.1 Model:
![output](https://user-images.githubusercontent.com/42543380/141349762-9c0c92db-4663-4548-ade1-6e43e4d3c064.png)

- Training accuracy is 88% and validation accuracy 80%.
- Model is fluctuating more.
- Let's use augumentation to increase data and check the result.

### 3.2 Augmentor:
Install [Augmentor](https://augmentor.readthedocs.io/en/master/) using command ```pip install Augmentor```

![augment_result](https://user-images.githubusercontent.com/42543380/141344428-eec1b7f2-0367-480f-b6ab-aad19abc45fa.png)

- We can see that after using augumented data model is giving preety good accuracy.
- After using Augmentor accuracy has improved from ```88% to 98%.```
- Also loss and accuracy is not fluctuating.

## 4.Prediction:
![predict](https://user-images.githubusercontent.com/42543380/141344796-e32eb361-1cc7-4b7f-93af-7c576b1a5b72.png)
