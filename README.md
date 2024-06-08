# 🔎 Iris Flower Image Classification

![image](https://github.com/ARKnajmi/IrisFlowerImageClassification/assets/149140186/1e430339-eb2f-4800-9985-4638d5fca7c1)

This project focuses on using Decision Tree to classify iris flower images. The goal is to accurately categorize iris flowers into different species based on their images.

You can use this Dataset from Kaggle: [Iris Computer Vision](https://www.kaggle.com/datasets/jeffheaton/iris-computer-vision),
or use the one on this repo


## 🚀 Project Overview
The project follows a structured approach, including data preprocessing, model training, evaluation, optimization, and testing. Here are the key steps:

1. Data Preprocessing: The iris flower images are preprocessed, including normalization using the ResNet18 model for feature extraction and oversampling to handle class imbalances.

2. Model Training: A Decision Tree Classifier is trained on the preprocessed data to classify iris flower images into different species.

3. Evaluation: The trained model's accuracy and performance are evaluated using K-Fold cross-validation on both training and test datasets.

4. Optimization: Hyperparameter tuning is performed to find the optimal settings for the Decision Tree Classifier, enhancing its classification performance.

5. Testing and Visualization: The model is tested on new iris flower images, and the results are visualized using classification reports, confusion matrices, and a visualization of the decision tree.

## 🗄️ Project Structure
* ipynb File: Python scripts for data preprocessing, model training, evaluation, optimization, testing, and visualization.
* iris_dataset: Contains the iris flower image dataset.
* iris_data_uji_coba: Contains the iris flower image train dataset.

## ➡️ Getting Started
1. Clone the repository:
   ```bash
    git clone https://github.com/yourusername/iris-flower-image-classification.git
    ```
2. Install the required library/dependencies:
3. Run the ipynb.

## 🏁 Results
![image](https://github.com/ARKnajmi/IrisFlowerImageClassification/assets/149140186/f7788b12-add2-49b1-a5e8-54dc0ad62d55)

The project achieves 75% accuracy on the test dataset, showcasing Decision tree can decently classfying the Iris Image dataset.
