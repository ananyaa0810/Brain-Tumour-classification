# Brain-Tumour-classification
This project aims to classify brain tumor images into two categories: images with no tumor and images with tumors.

## Dataset Description
The dataset consists of two classes:
- No Tumor: 98 images
- Tumor: 259 images

Images were loaded and preprocessed using TensorFlow/Keras, including resizing to 128x128 pixels and normalization.

## Model Architecture
The CNN model architecture consists of:
- Conv2D layers with ReLU activation
- MaxPooling2D layers for downsampling
- Flatten layer to flatten the 2D output to 1D
- Dense layers with ReLU activation
- Dropout layers for regularization

## Training Process
The model was trained for 20 epochs with a batch size of 32 using the Adam optimizer with a learning rate of 0.001. Data augmentation techniques were applied to increase the diversity of training examples.

## Evaluation Metrics
- Accuracy: 92%
- Precision: 0.93
- Recall: 0.91
- F1-score: 0.92
- Confusion Matrix:
- [[37  5]
 [ 3 55]]

## Results
The model achieved an accuracy of 92% on the test set. Training and validation curves show consistent improvement over epochs with minimal overfitting observed.

## Conclusion
The CNN model demonstrated effective classification performance on brain tumor images. Future work could explore fine-tuning hyperparameters or using more advanced CNN architectures for further improvements.
