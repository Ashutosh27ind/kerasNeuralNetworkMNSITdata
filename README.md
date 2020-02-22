# kerasNeuralNetworkMNSITdata
Demonstration of how Keras works as a wrapper and how to build a model in Keras on the **MNIST** dataset

## Platfor used :
https://www.nimblebox.ai/
(_Platform to enable work faster on AI projects with customizable GPU and CPU machines_)

Keras is a high-level library designed to work on top of Theano or Tensorflow. The main idea of Keras is to be an easy to use,   minimalistic API which can be used to build and deploy deep learning models quickly. Due to its simplicity, Keras' syntax and model     building pipeline is  easy to learn for beginners (though it does not compromise on flexibility - you can do almost everything with Keras which you can do with pure Tensorflow or Theano).  

Keras by default uses TensorFlow as the backend. If you wish to use it with Theano backend, you need to find the 'keras.json' file and change the "backend":"tensorflow" to "backend":"theano" in the .json file.  

In this assignment, we'll implement a L-layer deep model on MNIST dataset using Keras.  
The **MNIST** dataset contains tens of thousands of scanned images of handwritten digits, together with their correct classifications. MNIST's name comes from the fact that it is a modified subset of two data sets collected by NIST, the United States' National Institute of Standards and Technology.

