# Tumor-detection
# Tumor-detection-using-CNN

This project utilizes a Convolutional Neural Network (CNN) to detect tumors in medical images. The dataset consists of tumor and non-tumor images, and the CNN is trained on this dataset for binary classification.

### Dataset

- The dataset includes tumor and non-tumor images.
- Images are resized to (128, 128) for consistency.

### Model Architecture

- CNN with convolutional layers, max pooling, flattening, and dense layers.
- Binary classification output using sigmoid activation.

### Training

- Dataset is split into training and testing sets.
- Images are normalized using TensorFlow functions.
- Model is compiled with 'adam' optimizer and 'binary_crossentropy' loss.
- Training is performed for 5 epochs.

### Results

- Model accuracy is plotted and saved.
- Model evaluation on the test set includes accuracy and a classification report.

### Prediction

- The model is tested with sample images, and predictions are made.
- Example predictions are provided.

### Usage

- Install required libraries: `pip install numpy matplotlib opencv-python tensorflow tqdm scikit-learn`.
- Run the script: `python tumor_detection.py`.
