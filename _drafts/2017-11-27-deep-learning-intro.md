Hello,

Continuing from our [last blog post]({{ site.url }}/intro/2017/11/20/Learning-Systems.html) on **Machine Learning**, this blog post will focused on providing an overview of **Deep learning**.

## Deep Learning
Deep learning is a subfield of Machine learning. The best way to explain deep learning is to take a sneak peak into history. So here goes our attempt to explain to you what deep learning is really about.

## … Some History …
From our earlier blog post, we mentioned some AI techniques used in Learning systems research (Machine learning). These techniques includes: Support Vector Machine (SVM), Linear regression, Artificial Neural Network (ANN), Particle Swarm Optimisation, Ant Colony Optimisation, Genetic Algorithms and so on. Among these techniques, SVMs and ANNs really stood out (enjoying some reasonable level of success) and gained a lot of popularity earlier on. However, the successes of these two techniques came from learning **shallow (simple)** representations of knowledge from data (examples. Researchers wanted to push the boundaries even further to design learning systems that can learn **deep (complex)** representation of knowledge from data. 

SVMs did not really survive the transformation of research into learning more complex representation of data, therefore, it lost a lot of excitement in its research. Initially, ANNs also faced similar issues of scaling it to lear more complex representations . However, some break throughs (see [link](http://www.iro.umontreal.ca/~pift6266/H10/notes/deepintro.html#breakthrough-in-learning-deep-architectures)) and better computing power (in form of GPUs) helped overcome some of the challenges. This gave birth to the field we now know as **Deep learning**. Therefore, we can say that the AI technique that powers the deep learning field is almost exclusively ANNs. Some of the early intuitions (backed by some knowledge from the field of Neuroscience) behind deep learning has been well documented in this [link](http://www.iro.umontreal.ca/~pift6266/H10/notes/deepintro.html).

## Artificial Neural Network (ANN)
ANN is a computational model that is loosely inspired by the structure of the brain. Brains in animals contains neurons interconnected by synapsis thus forming a structure referred to as Biological Neural Network. A typical ANN is divided into 3 layers, they include: **input layer, hidden layer and the output layer**. Having an understanding of ANN is important because it is the technique that powers deep learning. Therefore, if we want to understand deep learning and apply it to solving practical problems in our society, a knowledge of ANN is pre-requisite. We will review ANN in-depth in a future blog post.

## Shallow ANNs, Deep ANNs
A shallow ANN is a neural network with 1 or 2 hidden layers. This type of network was used along side other techniques in early Machine learning research. **A deep ANN – popularly called Deep Neural Network (DNN)** - is a type of neural network with many hidden layers. Mordern Deep Neural Networks can contain over 100 hidden layers. DNNs now powers several mordern AI systems that we now use today, either in form of speech recognition, language translation etc.

For some time, researchers were stuck using shallow ANNs for Machine Learning even when they wanted to be able to use Deep Neural Networks. The reason was because DNNs were quite difficult to train mostly due to numerical instability of the network that culminates under two major problems: either the gradient (a key ingredient in implementations of ANNs) becomes too small and this is called **vanishing gradient** or it becomes too large and this is called **exploding gradient**. Computation of gradient is important to ANNs because it helps the network determine how to adjust itself (its parameters) to “improve its learning”. Today, the problem has been solved via new better tools (e.g. better initialization and better activation function) employed in the Deep Neural Networks.


## Summary
In essence, Deep Learning is a sub-field of Machine Learning that studies the design and development of learning systems that uses Deep Neural Networks (which has mutliple hidden layers)

In the next blog post, we will discuss about some of the nuances of (Deep) Neural Networks with focus on terms you need to know about (more like a cheat sheet to neural networks). Until then, bye...