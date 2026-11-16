# Potato Leaf Disease Classification using CNN

## Project Overview
A Convolutional Neural Network (CNN) built using TensorFlow and Keras to classify potato leaf images into three categories:

- Healthy
- Early Blight
- Late Blight

## Project Workflow
1. **Data Loading:** Loaded potato leaf images from the PlantVillage dataset.
2. **Data Preprocessing:** Resized images to 128×128, converted them to RGB, and normalized pixel values.
3. **Data Augmentation:** Applied random flipping and rotation to improve generalization.
4. **CNN Architecture:** Built a CNN using Conv2D, ReLU, MaxPooling, Flatten, Dense, Dropout, and Softmax layers.
5. **Model Training:** Trained the model using the Adam optimizer and Sparse Categorical Crossentropy loss.
6. **Model Evaluation:** Evaluated performance using accuracy, precision, recall, F1-score, and a confusion matrix.
7. **Prediction:** Tested the trained model on potato leaf images and saved it in `.keras` format.

## Technologies Used
Python, TensorFlow, Keras, NumPy, Matplotlib, Pillow, Scikit-learn, Jupyter Notebook.

## How to Run
1. Install the required libraries.
2. Download the PlantVillage potato leaf dataset and place the three class folders inside `data/`.
3. Open `cnn_code.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells sequentially to train, evaluate, and test the CNN model.

## Note
The dataset and trained model are not included in this repository. This project is intended for educational purposes.