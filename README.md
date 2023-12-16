# AccelerationModels

<b>Task:</b>
* <b>dataset CIFAR-100:</b> train a neural network that distinguishes the classes 'bicycle', 'motorcycle', 'background':
  
  * Analysis of results (confusion matrix, dependence of accuracy on external conditions, comparison of models, analysis of metrics,...)
  * Comparison of performance in different runtimes: onnxruntime, tensorrt, tvm, tflite, pytorch-keras, openvino,... 
  * Demonstrate the manipulation of weights: transform the first layer so that the number of input channels in the first convolution is not 3, but 1 with minimal loss of accuracy. That is, the grid should work on grayscale.
