# Deep-Learning-Challenge
# Challenge 21


## Step 1: Preprocess the data

* Read in the charity_data.csv to a Pandas DataFrame
* Drop the EIN and NAME columns.
* Determine the number of unique values for each column.
* For those columns that have more than 10 unique values, determine the number of data points for each unique value.
* Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, Other, and then check if the binning was successful.
* Use pd.get_dummies() to encode categorical variables

## Step 2: Compile, Train, and Evaluate the Model

* Create a neural network model by assigning the number of input features and nodes for each layer using Tensorflow Keras.
* Create the first hidden layer and choose an appropriate activation function.
* If necessary, add a second hidden layer with an appropriate activation function.
* Create an output layer with an appropriate activation function.
* Check the structure of the model.
* Compile and train the model.
* Create a callback that saves the model's weights every 5 epochs.
* Evaluate the model using the test data to determine the loss and accuracy.
* Save and export your results to an HDF5 file, and name it AlphabetSoupCharity.h5.

## Step 3: Optimize the Model

*Optimize your model in order to achieve a target predictive accuracy higher than 75% by using any or all of the following:*

* Adjust the input data to ensure that there are no variables or outliers that are causing confusion in the model, such as:
* Adding more neurons to a hidden layer.
* Adding more hidden layers.
* Using different activation functions for the hidden layers.
* Adding or reducing the number of epochs to the training regimen.


1. Create a new Jupyter Notebook file and name it AlphabetSoupCharity_Optimzation.ipynb.
2. Import your dependencies, and read in the charity_data.csv to a Pandas DataFrame.
3. Preprocess the dataset like you did in Step 1, taking into account any modifications to optimize the model.
4. Design a neural network model, taking into account any modifications that will optimize the model to achieve higher than 75% accuracy.
5. Save and export your results to an HDF5 file, and name it AlphabetSoupCharity_Optimization.h5.


## Step 4: Write a Report on the Neural Network Model
*The report is attached in this repo under the name "Analysis.pdf".*
