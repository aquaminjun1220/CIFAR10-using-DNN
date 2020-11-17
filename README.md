# CIFAR10-using-DNN
CIFAR-10- It dataset consists of 60000 32x32 colour images in 10 classes. Please find your dataset from the link- https://www.tensorflow.org/datasets/catalog/cifar10.
1. Import dataset/ libraries
  a. Import required libraries (recommended- use tensorflow/keras library).
  b. Import the dataset (use Google Drive if required).
  c. Check the GPU available (recommended- use free GPU provided by Google Colab).
2. Data Visualization
  a. Plot at least one sample from each class of the dataset (use matplotlib/seaborn/any other library).
  b. Print the shapes of train and test data.
3. Data Pre-processing
  a. Bring the train and test data in the required format.
4. Model Building
  a. Sequential Model layers- Use AT LEAST 3 dense layers with appropriate input for each. Choose the best number for hidden units.
  b. Add L2 regularization to all the layers.
  c. Add one layer of dropout at the appropriate position
  d. Choose the appropriate activation function for all the layers.
  e. Print the model summary.
5. Model Compilation
  a.Compile the model with the appropriate loss function
  b.Use an appropriate optimizer
  c. Use accuracy as metric.
6. Model Training
  a.Train the model for an appropriate number of epochs (print the train and validation accuracy/loss for each epoch). Use the appropriate batch size.
  b. Plot the loss and accuracy history graphs. Print the total time taken for training.
7. Model Evaluation
  a.Print the final test/validation loss and accuracy.
  b. Print confusion matrix and classification report for the validation dataset.
8. Hyperparameter Tuning- Build two more models by changing hyperparameters one at a time
  a. Batch Size: Change the value of batch size in model training
  b. Optimiser: Use a different optimizer with the appropriate LR value
