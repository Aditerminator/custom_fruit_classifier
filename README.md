# custom_fruit_classifier

Custom Fruit Classifier

This repository contains code for building a custom fruit classifier using deep learning techniques with TensorFlow and Keras. The classifier is trained to recognize different types of fruits including apples, pomegranates, guavas, watermelons, and pears.

Getting Started
Download Data: The data used for training and validation is required to be organized in specific folders. 
** The dataset is not so big as it it directly collected goggle images.
The notebook includes code to download data from Google and organize it into separate folders.
Dependencies: Ensure you have the necessary dependencies installed. The notebook imports libraries such as TensorFlow, Keras, and PIL (Python Imaging Library) for image processing.
Data Preprocessing
Before training the model, the images undergo preprocessing steps:

Conversion to JPEG: Images are converted to JPEG format for uniformity.
Error Image Handling: In case there are any images with invalid formats, they are removed from the dataset.
Model Building
The model architecture consists of Convolutional Neural Networks (CNNs) followed by fully connected layers. Data augmentation is applied using ImageDataGenerator to increase the dataset size and improve model performance.

Training the Model
The model is trained on the preprocessed data. Training and validation data generators are created using ImageDataGenerator.flow_from_directory. The model is compiled with appropriate loss function and optimizer.

Evaluating Model Performance
Model performance is evaluated using training and validation accuracy and loss. Plots are generated to visualize the training and validation metrics.

Making Predictions
Finally, the trained model is used to make predictions on test images. Test images are preprocessed and passed through the model for classification. Predicted class labels and accuracy percentages are displayed along with the test images.

Example Usage
To use the custom fruit classifier:

Ensure the data is organized correctly.
Execute each cell in the notebook sequentially to download data, preprocess it, build the model, train it, and make predictions.
Note
Adjustments may be required based on your specific dataset and requirements.
Replace class labels and paths with your own if necessary.
Experiment with different architectures, hyperparameters, and augmentation techniques for better performance.
For detailed implementation and explanation, refer to the notebook in this repository.
