# Dog-Breed-Prediction

Dog breed prediction is prediction in which we can predict the breed of the perticular dog from dog's picture.

In this project we will use kaggle dataset of dog pictures. We will create Convolutional Neural Network which will be able to predict what is the dog breed name. We will use different layers and other hyperparameters for building, training and testing this classification model. We will be using tensorflow and keras for this project.

We have some pictures of dogs their's breed are scottish_deerhound, maltese_dog, afghan_hound, entlebucher and bernese_mountain_dog.

With the help of cv2 we will convert the images in array.

After that we will train the data using one hot encoder.

Now we will use the sequential model in that 1st layer we will use conv2D then we will use MaxPooling2D, 3rd is Flatten layer, last layer is Dense model.

After that we will split the data into training and testing set.

We will train the model into number of epochs, the more number of epochs you give the more model accuracy you will get as output.

Now we will plot the Model Accuracy with the help of matplotolib.

We will predict the accuracy over the test set.

Lastly we can see the comparison between original and predicted breed.

