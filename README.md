# Neural-network-framework-and-CNN-model
a new neural network framework by python, and a CNN model built from this framework/一个新的神经网络框架及基于此框架的CNN模型

language: python3.7.2
platform: jupyter notebook

According to the principles of neural network, this project uses Python to write a new neural network framework, which can be used to build different neural network models.
The framework adopts modular design, including convolution layer, pooling layer, BN layer, fully connected layer and Softmax layer, which can be used to build neural network models freely. The convolutional layer has a small residual network option that can be optionally turned on or off.
The framework has basic forward and backward propagation, training, query, and visualization functions, and the visualization is not very complete.
This framework was used to build a CNN network, which was improved based on Lenet-5. After training, the recognition accuracy of MNIST reached 99.42%.

Many of the techniques used by this framework are outdated.
This framework only uses the single core of CPU for neural network training. In the future improvement, multi-threading can be used to make full use of CPU, and then GPU can be used to accelerate training.

此项目根据神经网络相关原理，利用python编写了一个新的神经网络框架，能利用此框架构建不同的神经网络模型。
框架采用模块化设计，有卷积层、池化层、BN层、全连接层以及softmax等网络层，能利用这些层自由组合神经网络模型。其中卷积层加入了一个小型残差网络选项，可以选择是否开启。
框架具有基本前向后向传播、训练、查询、以及可视化等功能，可视化还不是很完善。
利用这个框架建立了一个CNN网络，基于LeNet-5进行改进，我训练后对mnist的识别正确率达到99.42%。

此框架使用的许多技术已经过时，仅供参考。
此框架仅利用了CPU的单核进行神经网络训练，后续改进的话可以利用多线程充分利用CPU，然后利用GPU加速训练。
