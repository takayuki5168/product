# Product
I will show you some of my products!

## Deep Leaning Library for C++
You can make various model of DNN by using this.
```cpp
// init network
auto dnn = initDeepNeuralNetwork();

// build model
dnn->add<Dense>(10, 2);
dnn->add<ReLU>();
dnn->add<Dense>(20);
dnn->add<ReLU>();
dnn->add<Dense>(10);
dnn->add<ReLU>();
dnn->add<Dense>(4);

// set loss and optimizer
dnn->loss<MeanSquaredError>();
dnn->opt<RMSprop>();

// fit
dnn->fit(train_mat, ans_mat, 1000);
```
[Here](https://github.com/takayuki5168/DeepNeuralNetwork/) in detail.

## Hopfield Neural Network

## Star Fox

## Super Mario Brothers

## Flower Specifier
