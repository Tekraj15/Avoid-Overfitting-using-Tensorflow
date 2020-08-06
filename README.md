# Avoid Overfitting using Regularization in Tensorflow
Overfitting happens when a model learns the detail and noise in the training data to the extent that it negatively impacts the performance of the model on new data. Therefore, it’s necessary to avoid overfitting. And Regularization is one technique to avoid overfitting.

When we train neural network models, you may notice the model performing significantly better on training data as compared to data that it has not seen before, or not trained on before. This means that while we expect the model to learn the underlying patterns from a given data-set, often the model will also memorize the training examples. It will learn to recognize patterns that may be anomalous or may learn the peculiarities in the data-set. This phenomenon is called over-fitting and we should avoid overfitting to make the predictions accurate.

And it’s a problem because a model that is over-fit to the training data will not be able to generalize well to the data that it has not seen before. And that sort of defeats the whole point of making the model learn anything at all. We want models that are able to give us predictions as accurately on new data as they can for the training data.

