# LeNet-5
LeNet-5 is a pioneering convolutional neural network (CNN) architecture developed by Yann LeCun and his colleagues in 1998. It was primarily designed for handwritten digit recognition, specifically for the MNIST dataset, and has significantly influenced the field of deep learning.

![image](https://github.com/user-attachments/assets/615e163c-325e-4f5c-9d17-347aaa1507ec)

## Key Features of LeNet-5:
1. **Architecture**: LeNet-5 consists of seven layers (excluding the input layer), including convolutional layers, subsampling (pooling) layers, and fully connected layers.
2. **Layers**:
   - **Input Layer**: Takes 32x32 pixel grayscale images.
   - **C1 - Convolutional Layer**: Applies six 5x5 filters, resulting in six 28x28 feature maps.
   - **S2 - Subsampling Layer**: Performs average pooling with a 2x2 filter, reducing the feature maps to 14x14.
   - **C3 - Convolutional Layer**: Uses sixteen 5x5 filters, producing sixteen 10x10 feature maps.
   - **S4 - Subsampling Layer**: Another average pooling layer, reducing the feature maps to 5x5.
   - **C5 - Convolutional Layer**: Applies 120 5x5 filters, resulting in 120 1x1 feature maps.
   - **F6 - Fully Connected Layer**: Connects the 120 feature maps to 84 neurons.
   - **Output Layer**: Uses a softmax function to classify the input into one of ten categories (digits 0-9).

## Training and Impact:
- **Training**: LeNet-5 is trained using backpropagation and gradient descent, optimizing the weights to minimize classification error.
- **Impact**: It laid the groundwork for modern CNNs and has been foundational in the development of more complex architectures used in various image recognition tasks today¹²³.

# reference：
1, Y. Lecun, L. Bottou, Y. Bengio and P. Haffner, "Gradient-based learning applied to document recognition," in Proceedings of the IEEE, vol. 86, no. 11, pp. 2278-2324, Nov. 1998, doi: 10.1109/5.726791.
keywords: {Neural networks;Pattern recognition;Machine learning;Optical character recognition software;Character recognition;Feature extraction;Multi-layer neural network;Optical computing;Hidden Markov models;Principal component analysis},

2,https://www.bilibili.com/video/BV1AP4y167bX/?p=6&spm_id_from=333.1007.top_right_bar_window_history.content.click&vd_source=454e1c187ea128be5e023c7cc27c1a7b
