# food_classifier
## Problem statement:

To build a CNN based model which can accurately detect food.

[Dataset is taken from kaggle.](https://www.kaggle.com/rajaraman6195/recipes)

[Check Implementation from Kaggle](https://www.kaggle.com/vaibhavkumbhar/food-classifier)

### About this Dataset
This is a list of different food listings of images. The dataset includes the set of images for each recipes.

The dataset contains 5 sub-directories of food images.
- biryani
- burger
- dosa
- idly
- pizza

## Augmentor:
Use augumentation to increase data and check the result.

Install [Augmentor](https://augmentor.readthedocs.io/en/master/) using command ```pip install Augmentor```

![augment_result](https://user-images.githubusercontent.com/42543380/141344428-eec1b7f2-0367-480f-b6ab-aad19abc45fa.png)

- We can see that after using augumented data model is giving preety good accuracy.
- Model is no more overfitting.
- Also loss and accuracy is not fluctuating.
- After using Augmentor accuracy has improved from ```88% to 98%.```

## Prediction:
![predict](https://user-images.githubusercontent.com/42543380/141344796-e32eb361-1cc7-4b7f-93af-7c576b1a5b72.png)
