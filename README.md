# Neural-Network
Simple neural Network using Python and TensorFlow/Keras framework

Explanation

Step1: Install TensorFlow framework

Step2: Import necessary libraries

Step3: Load MNIST dataset and normalise pixel values between 1 and 0

Step4: Build Sequential Model

-Flatten: 28*28 input images in 1D array

-Dense(128,activation='relu'): connect 128 neurons and ReLU activation function

-dense(10): output layer with 10 neurons, using default linear activation in loss function

Step5: Complile model using Adam Optimizer, sparse categorical crossentropy loss function(for integer-encoded labels), and accuracy metrics

Step6: Train model for 10epochs, and validate on test data

Step7: Evaluate trained model on test data and evaluate accuracy

