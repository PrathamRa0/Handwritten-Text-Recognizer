# Handwritten Text Recognizer
Deep Learning Model to recognize and display the handwritten text given by the user.

The system is trained using a CNN model to recognize and differentiate between different characters. The characters are then combined to form the text phrase and is displayed to the user. 


## Built With: ##
* Python
* Tensorflow
* Keras
* OpenCV
* Numpy


## Dataset sources: ##
* For character recognition: https://www.kaggle.com/datasets/vaibhao/handwritten-characters
* For handwritten text recognition: https://www.kaggle.com/datasets/landlord/handwriting-recognition

## Procedure: ##
* **Step-1:** Install the datasets on to the Google colab directly from kaggle, unzip it into the drive, this will save a lot of time.
* **Step-2:** Use `!pip install imutils` command to make the basic image processing functions easier.
* **Step-3:** Import all the necessary libraries. Separate the dataset into training set (x, y) and testing set (x, y) on the basis of the features and labels given in the dataset. The train_x and test_x are the numpy arrays containing numbers from 0-255 representing the shade on gray scale accordingly for different images.
* **Step-4:** Create a CNN to train the dataset. The `features` and `labels` from training dataset will be validated against the features and labels from the testing dataset and model will be trained.
* **Step-5:** Once the model is trained, plot a graph between `actual accuracy vs validation accuracy` to know how our model performed.
* **Step-6:** Upload different images and check if the obtained output is same as the expected output.


## Conclusion: ##
* This Machine Learning model gave a accuracy of approximately 93%.
* The characters in the images are highlighted, so that comparison with the output is easy.

