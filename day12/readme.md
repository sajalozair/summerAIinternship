## implementation of neural network in pytorch and testing model
1:Created a vanilla neural network (extension of linear regression) in PyTorch on Google Colab.<br />
2:Used different modules of PyTorch like torchvision, torch.utils.data, and other Python libraries such as sklearn, matplotlib, numpy, and pandas.<br />
3:Utilized the FashionMNIST dataset containing 10 classes like bags, shirts, sandals, sneakers, and others.<br />
4:Performed forward propagation to pass the input data through the network and obtain predictions.<br />
5:Applied the ReLU activation function in the hidden layer to introduce non-linearity.<br />
6:Conducted backward propagation to calculate the error and gradients to update the model parameters.<br />
7:Used the cross-entropy loss function to measure the discrepancy between predicted and actual class labels.<br />
8:Utilized gradient descent to minimize the loss and update the model parameters iteratively.<br />
9:Trained the model over multiple epochs(5) to improve its performance.<br />
10:Monitored the loss values during training, observing a decreasing trend with each iteration within the respective epoch.<br />
11:Also, monitored the accuracy of the model during training, observing an increasing trend with each iteration within the respective epoch.<br />
12:The training process involved iterative updates of the model's parameters to improve its ability to make accurate predictions.<br />
13:The training process eventually led to a model capable of achieving higher accuracy on the FashionMNIST dataset as the epochs progressed.<br />
14:The graphs for loss vs. iterations and accuracy vs. iterations visually displayed the improvements during the training process.<br />
15:After training the model i tested it on test data i got 64.05 accuracy of model.<br />
16: than i trained the model at 100 epoach and got accuracy of 84.42.<br />
code file is attached below:
