# Week 1

In this week, I studied about Neural Networks:

- Neural Networks are layers of nodes where, every all nodes of adjacent layers are interconnected. The connections carry values called weights and each layer has its ownn bias. The first layer of nodes gets input, these inputs are numbers which are operated by weights and biases which creates the next layer. This causes the values to change and in the final layer, we get a tensor of values of each node. The node predicted by a trained model has highest values compared to other nodes. This is the way how a model predicts.

- After every batch, loss is calculated. Loss is basically the sum of squares of differences between predicted values and actual values. The lower the loss the better the model performs. After the loss is calculated, weights and biases are adjusted to get a better prediction. These small adjustments change the affect the predictions made by the model, and after every adjustment, the model predicts better and better.

- We divide the data into train data and test data. This ensures that when a model is tested, It is not being tested on the data that it was trained on and it truly makes predictions for a new data.

- After multilple epochs, the model gets better and better and makes really accurate predictions.

- Overfitting model - A model is overfit if it fits the training data too much which causes it to make bad predictions. The task of a Machine learning model is to make predictions and not to fit the training data. To ensure that a model does not overfit, we add drop in the model, causing it to randomly drop some of the predictions, this makes sure that model does not overfit the training data. 