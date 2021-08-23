## Digit Classification
* **####MNIST Dataset**  
MNIST dataset was used to train the CNN model, and predict the digit in the test images.

####* **SVHN Dataset**  
SVHN dataset was used to train two models, MLP neural network classifier and CNN classifier. Callbacks were used to get more control over the training process, i.e. to stop the training early to avoid overfitting (EarlyStopping callback) and to save the best weights after every epoch (ModelCheckpoint callback). It can be observed that the CNN model gives better accuracy even though it has fewer trainable parameters than the MLP model.
