# Fashion_Mnist

This code performs hyperparameter tuning and training of a deep learning model on the Fashion MNIST dataset using TensorFlow and Keras.
It utilizes keras_tuner for hyperparameter optimization through RandomSearch, searching for optimal units in dense layers, dropout rates, and learning rates. 
The best model configuration is selected based on validation accuracy, trained over 20 epochs, and evaluated on a separate test set. Finally, it plots and compares the training and validation accuracy trends over epochs to assess model performance visually.
