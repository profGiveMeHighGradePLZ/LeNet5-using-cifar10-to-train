![image](https://github.com/user-attachments/assets/615e163c-325e-4f5c-9d17-347aaa1507ec)

In the US, bank checks with handwritten digits were automatically classified using LeNet-5 on a large scale. 

LeNet-5 is a very basic network by today's standards. It only has seven layers total: the output layer is positioned after two sub-sampling (pooling) layers (S2 and S4), one fully connected layer (F6), and three convolutional layers (C1, C3, and C5). 5 by 5 convolutions with stride 1 are used in convolutional layers. Two by two average pooling layers are sub-sampling layers. The network as a whole uses tanh sigmoid activations. LeNet-5 made a number of intriguing architectural decisions that are uncommon in the current deep learning era.


reference：
1,https://www.bilibili.com/video/BV1AP4y167bX/?p=6&spm_id_from=333.1007.top_right_bar_window_history.content.click&vd_source=454e1c187ea128be5e023c7cc27c1a7b
2,https://medium.com/@pechyonkin/key-deep-learning-architectures-lenet-5-6fc3c59e6f4
