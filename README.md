# Images classification
## Introduction
- Using python to Engage in a research project on images classification through TensorFlow framework.
- A convolutional neural network with two convolutional layers, two pooled layers, and two fully connected layers was designed to classify the CIFAR-10 dataset and obtains 85% accuracy.
- Analyzed the influence on accuracy based on different batch sizes, pooling methods and activation functions
## Structure of CNN
[Structure of CNN](https://github.com/neollen/Images-classification/blob/master/Structure%20of%20CNN.png)
## Structure of First Layer
[Structure of first layer](https://github.com/neollen/Images-classification/blob/master/structure%20of%20first%20layer.png)
## Different paramters 
- Batch size



batch size= 64,128,256,512.  step=1000
 
| Batch size | lost function | precision |
| ------ | ------ | ------ |
| 64 | 3.458 | 0.2 |
| 128 | 3.187 | 0.257 |
| 256 | 3.176| 0.266 |
| 512 | 3.459 | 0.2812|
- Pooling method



Max pooling and Average pooling. step=10000
  
| polling methid | lost function | precision |
| ------ | ------ | ------ |
| Max pooling| 0.758 | 0.83 |
| Average pooling| 0.955 | 0.74 |
- Activation Function



Sigmoid,ReLU,ELU.   step=10000

| polling methid | lost function | 
| ------ | ------ | 
| Sigmoid| 2.319 | 
| ReLU| 0.75 | 
| ELU| 0.76 | 


 
