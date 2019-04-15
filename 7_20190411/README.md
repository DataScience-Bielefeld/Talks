# DataScience MeetUp #7
## Building Interpretable Neural Networks with Keras and LIME - Shirin Glander

Keras is a high-level open-source deep learning framework that by default works on top of TensorFlow. Keras is minimalistic, efficient and highly flexible because it works with a modular layer system to define, compile and fit neural networks. It has been written in Python but can also be used from within R. Because the underlying backend can be changed from TensorFlow to Theano and CNTK (with more options being developed right now) it is designed to be framework-independent. Models can be trained on CPU or GPU, locally or in the cloud.

Shirin will show an example of how to build an image classifier with Keras. We'll be using a convolutional neural net to classify fruits in images. But that's not all! We not only want to judge our black-box model based on accuracy and loss measures - we want to get a better understanding of how the model works. We will use an algorithm called LIME (local interpretable model-agnostic explanations) to find out what part of the different test images contributed most strongly to the classification that was made by our model.
Shirin will introduce LIME and explain how it works. And finally, she will show how to apply LIME to the image classifier we built before, as well as to a pre-trained Imagenet model.

## Note(s)
Also see the blog entries on Shirin's website to [image classifiers with Keras](https://shirinsplayground.netlify.com/2018/06/keras_fruits/) and [explaining such classifiers with Lime](https://shirinsplayground.netlify.com/2018/06/keras_fruits_lime/).
