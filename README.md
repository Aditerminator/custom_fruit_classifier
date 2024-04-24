

# 🍎🍐🍉 Custom Fruit Classifier 🍏🍊🍇

This repository contains code for building a custom fruit classifier using deep learning techniques with TensorFlow and Keras. The classifier is trained to recognize different types of fruits including apples, pomegranates, guavas, watermelons, and pears.

## Getting Started 🚀

<h2>Download Data</h2>
The data used for training and validation is required to be organized in specific folders. **The dataset is not so big as it is directly collected from Google Images.** The notebook includes code to download data from Google and organize it into separate folders.

<h2>Dependencies</h2>
Ensure you have the necessary dependencies installed. The notebook imports libraries such as TensorFlow, Keras, and PIL (Python Imaging Library) for image processing.

## Data Preprocessing 📊

Before training the model, the images undergo preprocessing steps:

<ul>
  <li><b>Conversion to JPEG:</b> Images are converted to JPEG format for uniformity.</li>
  <li><b>Error Image Handling:</b> In case there are any images with invalid formats, they are removed from the dataset.</li>
</ul>

## Model Building 🏗️

The model architecture consists of Convolutional Neural Networks (CNNs) followed by fully connected layers. Data augmentation is applied using ImageDataGenerator to increase the dataset size and improve model performance.

## Training the Model 🏋️‍♂️

The model is trained on the preprocessed data. Training and validation data generators are created using ImageDataGenerator.flow_from_directory. The model is compiled with an appropriate loss function and optimizer.

## Evaluating Model Performance 📈

Model performance is evaluated using training and validation accuracy and loss. Plots are generated to visualize the training and validation metrics.

## Making Predictions 🎯

Finally, the trained model is used to make predictions on test images. Test images are preprocessed and passed through the model for classification. Predicted class labels and accuracy percentages are displayed along with the test images.

<div class="note">
  <b>Note:</b><br>
  - Adjustments may be required based on your specific dataset and requirements.<br>
  - Replace class labels and paths with your own if necessary.<br>
  - Experiment with different architectures, hyperparameters, and augmentation techniques for better performance.<br>
  - For detailed implementation and explanation, refer to the notebook in this repository.
</div>
