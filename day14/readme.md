## state of art models
### ResNet50
ResNet (short for Residual Network) is a deeper and more powerful architecture than MobileNet.
</br>It utilizes residual blocks to enable training of very deep networks without vanishing gradient problems, making it easier to optimize and capable of learning complex representations.
</br>ResNet is known for its strong performance and state-of-the-art accuracy in various computer vision tasks.
</br>It is more computationally expensive and has a larger number of parameters compared to MobileNet.
</br>I created a network using pre-trained model ResNet50 in Pytorch on google colab using pytorch in-build models “from torchvision.models import resnet50”

</br>I used different modules of pytorch like torchvision, torch.utlis.data and other python libraries like sklearn, matplotlib, numpy and pandas.
</br>I used images dataset---FashionMNIST dataset that contain 10 classes like bags, shirts, sandals, sneakers and few other.
</br>During training I modified last layer of ResNet50 model   giving it only 10 classes to classify images. also the model is trained on images with 3 channels so, I transformed the dataset images to 3 channels that previously had 1 channel .
</br>I allowed 20 epochs over the dataset for better training of model and got accuracy of 99.46%.
