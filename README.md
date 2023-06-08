# Sign-language-detection
The model aims at recognizing sign kanuage, the language commonly used to communicate with deaf people.
The data used for the model is the MNIST dataset which can be found on kaggle using the link https://www.kaggle.com/datasets/datamunge/sign-language-mnist
The model is able to predict accurately with an accuracy of 92%.
The model uses the image processing techniques such as ImageDataGen to perform augmentation of data.
The model comprises of 2 Convolutional layers and 2 MaxPooling layers with 2 Dense kayers with Softmax function as the activation function in the last layer.
The model uses RMSprop as the optimizer and sparse_categorical_crossentropy as its loss function.
