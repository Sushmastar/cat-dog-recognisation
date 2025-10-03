# Cat vs Dog Image Classification using SVM

## Project Overview
This project implements a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs.  
The goal is to build a simple image classifier that can predict whether a given image belongs to a cat or a dog.

## Dataset
We are using the Cat and Dog dataset, which contains thousands of labeled images of cats and dogs.  
You can download it from Kaggle: [Cats and Dogs Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

## Technologies Used
- Python
- Pandas, NumPy (Data Handling)
- OpenCV / Pillow (Image Processing)
- Scikit-learn (SVM Classifier, Model Training)
- Matplotlib (Visualization)
## Steps Involved
1. Load and preprocess the dataset (resize images, convert to grayscale or flatten pixels).
2. Split the dataset into training and testing sets.
3. Extract features from images.
4. Train an SVM classifier on the training set.
5. Evaluate the classifier using accuracy and confusion matrix.
6. Test the model on unseen images.
## Results
The trained SVM model is able to classify images into two categories:
- Cat
- Dog

The performance may vary based on preprocessing and feature extraction methods used.

