# Classic gradient descent

Iterative approach for finding the (local) optimum of the function. Algorithm consider function that has been optimized, gradient, starting point, number of iterations and learning rate. The examples is shown on basic function and corresponding gradient.

# Stochastic gradient descent

The approximation of classic GD, with modification of randomly selecting the initial point. Additionally, stochastic GD algorithm takes batches which randomly dissect all points. Correction of learning rate value is achieved with cosidering previous vector update, and it's computation when calculating the successor. The decay factor value defines the intesity of previous vector impact.

## SGD & Adam
So far I've implemented two methods using numpy.
The packages such as **TensorFlow** and **Keras** are offering the stochastic gradient as [SGD](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/SGD) object, and [Adam optimizer](https://keras.io/api/optimizers/adam/) since 2015.
