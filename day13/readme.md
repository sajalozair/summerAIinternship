## state of art models
### MobileNet
MobileNet is designed for efficiency, particularly on mobile and embedded devices with limited computational power and memory.</br>
It uses depthwise separable convolutions to reduce computation and model size while preserving reasonable accuracy.</br>
MobileNet is well-suited for scenarios where computational resources are a significant concern, such as on mobile phones, IoT devices, and edge computing.</br>
I created a network using pre-trained model  MobileNet in Pytorch on google colab using pytorch in-build models “ from torchvision.models import mobilenet_v2.”
</br>I used different modules of pytorch like torchvision, torch.utlis.data and other python libraries like sklearn, matplotlib, numpy and pandas.
</br> I used images dataset---FashionMNIST dataset that contain 10 classes like bags, shirts, sandals, sneakers and few other. 
</br>During training I modified last layer of mobilenet model   giving it only 10 classes to classify images. also the model is trained on images with 3 channels so, I transformed the dataset images to 3 channels that  previously had 1 channel .
</br>I allowed  10 epochs over the dataset for better training of model and got accuracy of 98.01%.
