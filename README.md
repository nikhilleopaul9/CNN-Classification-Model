# CNN-Classification-Model
Classification model based on CNN with different techniques like Image Augmentation and Transfer Learning to improve the overall accuracy and generalization ability of the model.The model was trained on the famous Cats vs Dogs dataset.

* First a basic CNN Model was on the dataset with 2 Convolution Layers and 2 MaxPooling layer.The model gave a Traning accuracy greater than 99% and test accuracy of 83% which clearly indicates that the model is **Overfitting**.

*  **Image augmentation** artificially creates training images through different ways of processing or combination of multiple processing, such as random rotation, shifts, shear and flips, etc.Since the previous was overfitting the training data, we can introduce **Image Augmentation** to increase variation in our dataset and decrease the generalzation error. The model gave a Training accuracy of 80% and Testing accuracy of 85% which indicates the model is not performaing very well with the training dataset, but has decreased the generalization error.

* **Transfer learning (TL)** is a research problem in machine learning (ML) that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem. For example, knowledge gained while learning to recognize cars could apply when trying to recognize trucks. 

> **Inception V3**- Inception-v3 is a convolutional neural network that is 48 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. We used it to train our dataset and gave a training accuracy of 96% and test accuracy of 97%. 

> **Resnet50**- ResNet-50 is a convolutional neural network that is 50 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. We used it to train our dataset and gave a trainiing accuracy of 99% and testing accuracy of 98%. 
