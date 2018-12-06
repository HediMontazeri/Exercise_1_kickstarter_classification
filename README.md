# Exercise_1_kickstarter_classification
This exercise includes two parts. First part is data exploration which only looks at type of features, tries to gain insight and uncover relations in the data. Also some new features are built, such as time interval between deadline and launch time or spliting the dates into year, month and days. 


The second part tries different methods to predict the new state. 
First method is linear SVM, although based on correlations, chance of success of this method is too low. Accuracy of this method is 0.57. 
Second method is decision tree with accuracy of 0.79. 
Last method is neural network. Tensorflow and keras libraries are being imported to build the neural network. The best model has the following structure:
3 hidden layers of relu(70 neurons), tanh(40 neurons), tanh(30 neurons) and last layer of softmax to predict the dummy variable of 3 classes. 
The accuracy of the neural network is 0.84. So far the best. 

Future possible works:
* I haven't done any feature selection due to lack of time. However, it is a good idea to know which features could be the best predictors before applying any models. 
* Parameter tuning might be helpful to improve the accuracy of the NN.
* Naive bayes is worth a try as well in this multi label classification. 

