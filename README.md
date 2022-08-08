# Rice-Leaf Disease Prediction
 
The file identifies the Disease affecting the rice crops by using Convolution neural network.

The target has three classes namely
* Bacterial Leaf Blight
* Brown Spot
* Leaf Smut

The project is done using two separate methods but both yield the same result.
* One way was using train-test-split method of cross validation and the images were resized and scaled explicitly.
* The other way was that the images were preprocessed using the ImageDataGenerator from the Tensorflow library.

The neural network model is initialised with 3 hidden layers in addition to the input and output layers.

The model is deployed using the Flask framework.
