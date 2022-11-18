This analysis was used to compare a multiude of factors present in the data to what is being defined as a successful use of capital by a fictional charity. The factor then is a categorical number referred to as 'IS_SUCCESSFUL'. The desired outcome is creating a deep learning model that fits well that will help the charity to best determine where to send its resources.

The target variable is the 'IS_SUCCESSFUL' column which is a binary of 1 for successful and a 0 for not successful.
The features of information beyond idenitifiers which is application type, affiliation, classification, use case, organization, status, income amount, special considerations, and the ask amount.

The EIN and name values were removed as they bear no relevence to our results.

Several attmpets were made to tune the neural network that was created however the best result I could create was a function with an approx 55% loss and a 73% accuracy. This contained an inital layer of 5 neurons, two hidden layers of 3, and 2 neurons respectively and the end layer with one neuron. I maniuplated the number of neurons in each layer, I also modified the amount of information present in some of the binning that was done in the data cleaning step as well as adding a second hidden layer into the model. In each case there was a minimal change in both the loss and the accuracy of this information. 

If I were to repeat this or further work on it to optimize it I would reshape the data for a more diagnostic approach to optimizing the hyperparameters for this model to detemine optimal outcome. I would also work to take greater care in the cleaning to see if removing some parameters would allow for a better fit. 
