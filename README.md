# Alphabet_Charity_Model
Module 19 Challenge

The model I created for the Module 19 Challenge started off as Deep Learning with 2 layers and 45 neurons but the accuracy for the model only came out to 53%.

Looking at the nature of the dataset, I opted to test a Basic Neural Network. After inputting the data and running the model I achieved a 72% accuracy. I dropped the “NAME”, “EIN”, “CLASSIFICATION” columns and binned the application_type column to pare down the features. I used the Keras Sequential model, with a first layer that contains the inputs and a hidden layer of neurons. I did one neuron in the hidden layer which is standard for the basic model. After building the input and hidden layers, I added an output layer. Then the model was compiled, optimized, train/tested and fitted and an accuracy score was 72%.

Although the requirement was 75%, I could not achieve that level. I tried using a deep learning model which resulted in 53% (no good). I changed the activation method to relu and tanh which resulted in a 71% accuracy which wasn’t as efficient. I also tried pairing down the data by removing variables that would cause the dataset to be confused (“NAME”, “EIN”, “CLASSIFICATION”) and binned the application_type column. I also increased the number of epochs from 50 to 150 which did not result in increasing the accuracy at all.

I would look at different models like SVM since these models can handle unprocessed and processed tabular data. SVMs can analyze and interpret multiple data types, such as images, natural language voice and text, or tabular data. SVMS classify regression using two groups which seem to be a fit for the dataset.
