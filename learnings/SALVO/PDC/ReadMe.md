# Plant Disease Classification
### Dataset :-
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

### Model :-
### **ResNeT-12 Varient architecture**
**ResNet**: The main ResNet architecture. It builds the network using a series of residual blocks.

**So what is residual blocks in residual learning?:**
>**Residual Blocks**: The core idea of ResNet is the use of residual blocks, which include skip (or shortcut) connections. These connections allow the network to learn residual mappings rather than the direct mapping, making it easier to train very deep networks.

>**Skip Connections**: These connections bypass one or more layers, allowing the network to learn an identity function if it is optimal, thus preventing the degradation problem in very deep networks.

**Convolution Layer**: A single convolutional layer followed by a batch normalization and ReLU activation.

![Convolution Layer](https://github.com/user-attachments/assets/2295a947-d71c-48c5-a1e7-24c84204cf07)

**BasicBlock**: Defines the residual block used in ResNet-12. Each block consists of two convolutional layers.

![BasicBlock](https://github.com/user-attachments/assets/25b3b8f3-dcea-4b67-8a8a-e87caa517ada)

**Residual Blocks**: 

![Residual Blocks](https://github.com/user-attachments/assets/61fa893c-302e-43d3-a161-fb1b97f82559)

·  **Average Pooling**: Applied before the final fully connected layer.

·  **Fully Connected Layer**: The final classification layer.
