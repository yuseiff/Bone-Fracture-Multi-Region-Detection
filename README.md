# Bone Fracture Multi-Region Detection

This project focuses on the detection of bone fractures in medical images using deep learning techniques. The goal is to build a model that can accurately classify X-ray images into two categories: "fractured" and "not fractured." Additionally, the model is designed to identify the specific regions of the bone that are affected by the fracture.

## Project Structure

The project directory contains the following files:

- `main.ipynb`: This Jupyter Notebook file contains the implementation of the bone fracture detection model. It is the main script used for data loading, model training, and evaluation.

- `Data/train`: This directory contains the training dataset, which consists of X-ray images of fractured and non-fractured bones.

- `Data/val`: This directory contains the validation dataset, which is used for monitoring the model's performance during training and for hyperparameter tuning.

- `Data/test`: This directory contains the test dataset, which is used to evaluate the final trained model's performance on unseen data.

## Requirements

The following dependencies are required to run the project:

- TensorFlow
- Matplotlib
- OpenCV (cv2)
- PIL (Python Imaging Library)
- NumPy

## Usage

1. Clone the project repository to your local machine.

2. Install the required dependencies mentioned in the `Requirements` section.

3. Place your training, validation, and test datasets in the respective directories: `Data/train`, `Data/val`, and `Data/test`. Ensure that the images are organized in separate folders based on their classes (fractured or not fractured).

4. Open the `main.ipynb` Jupyter Notebook.

5. Run the notebook cells sequentially to execute the code. This will import the necessary modules, load the data, create the training, validation, and test datasets, and train the bone fracture detection model.

6. After training, the model's performance can be evaluated on the test dataset. The evaluation results, including accuracy and loss, will be displayed in the notebook.

7. You can modify the code in `main.ipynb` to experiment with different hyperparameters, network architectures, or image preprocessing techniques.

## Results

The trained model achieves an accuracy of [insert accuracy value] on the test dataset. It successfully detects and classifies bone fractures in X-ray images and identifies the specific regions of the bone affected by the fracture.

## Conclusion

The Bone Fracture Multi-Region Detection project demonstrates the application of deep learning techniques for automatic identification and classification of bone fractures in medical images. The trained model can be a valuable tool in assisting medical professionals in diagnosing fractures and determining the affected regions, enabling faster and more accurate patient care.


Dataset Link: https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data/code
