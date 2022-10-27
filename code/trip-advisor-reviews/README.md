
 ### Trip Advisor Reviews

NLP Dataset: Dataset consisting of 20k reviews from trip advisor (https://www.kaggle.com/datasets/andrewmvd/trip-advisor-hotel-reviews)

 - Data Visualization
    Print at least two records from each class of the dataset, for a sanity check that labels match the text.
    
    Plot a bar graph of class distribution in the dataset. Each bar depicts the number of records belonging to a particular class in the dataset. (recommended - matplotlib/seaborn libraries)
    
    Any other visualizations that seem appropriate for this problem are encouraged but not necessary, for the points.
    Print the shapes of train and test data.
 

- Data Pre-processing 
    Need for this Step- Since the models we use cannot accept string inputs or cannot be of the string format. We have to come up with a way of handling this step. 

    Please usethis pre-trained embedding layer  ( https://tfhub.dev/google/nnlm-en-dim128/2 from TensorFlow hub for this). This link also has a code snippet on how to convert a sentence to a vector. Refer to that for further clarity on this subject.
    
    Bring the train and test data in the required format.
 

- Model Building 
    Sequential Model layers- Use AT LEAST 5 hidden layers with appropriate input for each. Choose the best number for hidden units and give reasons.
    
    Add L1 regularization to all the layers.
    
    Add one layer of dropout at the appropriate position and give reasons.
    
    Choose the appropriate activation function for all the layers.
    
    Print the model summary.   
 

- Model Compilation 
    Compile the model with the appropriate loss function.
    Use an appropriate optimizer. Give reasons for the choice of learning rate and its value.
    Use accuracy as a metric.
 

- Model Training
    Train the model for an appropriate number of epochs. Print the train and validation accuracy and loss for each epoch. Use the appropriate batch size.
    Plot the loss and accuracy history graphs for both train and validation set. Print the total time taken for training.
 

- Model Evaluation
    Print the final train and validation loss and accuracy. Print confusion matrix and classification report for the validation dataset. Analyse and report the best and worst performing class.
    Print the two most incorrectly classified records for each class in the test dataset.
 

- Hyperparameter Tuning
    Build two more models by changing the following hyperparameters one at a time. Write the code for Model Building, Model Compilation, Model Training and Model Evaluation as given in the instructions above for each additional model. (1 + 1 = 2 marks)

- Regularization
    Train a model without regularization

- Dropout
    Change the position and value of dropout layer

- Write a comparison between each model and give reasons for the difference in results.

- Plot the decision boundary, visualize training and test results of all the models 