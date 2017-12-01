---
layout: post
comments: true
title: Deep Learning Introduction
category: intro
excerpt: Deep learning is a subfield of Machine learning. The best way to explain deep learning is to take a sneak peak into history. So here goes our attempt to explain ...
---

Hello,

Continuing from our [last blog post]({{site.url}}/intro/2017/11/20/learning-systems.html) on **Machine Learning**, this blog post will focused on providing an overview of **Deep learning**.

## Deep Learning
Deep Learning is a subfield of Machine Learning. The best way to explain Deep Learning is to take a sneak peak into history. So here goes our attempt to explain to you what Deep Learning is really about.

## … Some History …
From our earlier blog post, we mentioned some AI techniques used in Learning systems research (Machine learning). These techniques includes: Support Vector Machine (SVM), Linear regression, Artificial Neural Network (ANN), Particle Swarm Optimisation, Ant Colony Optimisation, Genetic Algorithms and so on. Among these techniques, SVMs and ANNs really stood out (enjoying some reasonable level of success) and gained a lot of popularity earlier on. However, the successes of these two techniques came from learning **shallow (simple)** representations of knowledge from data (examples. Researchers wanted to push the boundaries even further to design learning systems that can learn **deep (complex)** representation of knowledge from data. 

SVMs did not really survive the transformation of research into learning more complex representation of data, therefore, it lost a lot of excitement in its research. Initially, ANNs also faced similar issues of scaling it to lear more complex representations . However, some break throughs (see [link](http://www.iro.umontreal.ca/~pift6266/H10/notes/deepintro.html#breakthrough-in-learning-deep-architectures)) and better computing power (in form of GPUs) helped overcome some of the challenges. This gave birth to the field we now know as **Deep learning**. Therefore, we can say that the AI technique that powers the deep learning field is almost exclusively ANNs. Some of the early intuitions (backed by some knowledge from the field of Neuroscience) behind deep learning has been well documented in this [link](http://www.iro.umontreal.ca/~pift6266/H10/notes/deepintro.html).

## Artificial Neural Network (ANN)
ANN is a computational model that is loosely inspired by the structure of the brain. Brains in animals contains neurons interconnected by synapses thus forming a structure referred to as Biological Neural Network. A typical ANN is divided into 3 layers, they include: **input layer, hidden layer and the output layer**. Having an understanding of ANN is important because it is the technique that powers deep learning. Therefore, if we want to understand deep learning and apply it to solving practical problems in our society, a knowledge of ANN is pre-requisite. We will review ANN in-depth in a future blog post.

## Shallow ANNs, Deep ANNs
A shallow ANN is a neural network with 1 or 2 hidden layers. This type of network was used along side other techniques in early Machine learning research. **A deep ANN – popularly called Deep Neural Network (DNN)** - is a type of neural network with many hidden layers. For example, a DNN can be designed to contain over 100 hidden layers. They are being used to power several modern AI systems that we now use today, either in form of speech recognition, language translation etc.

For some time, researchers were stuck using shallow ANNs for Machine Learning even when they wanted to try out deeper neural networks. The reason was because DNNs were quite difficult to train. One of the reasons for training difficulty (of DNNs) was as a result of numerical instability of the network that culminates under two major problems: either the gradient (a key ingredient in implementations of ANNs) becomes too small and this is called **vanishing gradient** or it becomes too large and this is called **exploding gradient**. Computation of gradient is important to ANNs because it helps the network determine how to adjust itself (its parameters) to “improve its learning”. Today, the problem has been solved via new better tools (e.g. better initialization and better activation function) employed in the Deep Neural Networks.

## Note
In the last 2 years (or even further back) of AI research, the term **Deep Learning** has started to encompass other AI techniques as well. For example, some researchers employ evolutionary techniques (like Genetic Algorithm) as a sub-part of Deep Learning systems being designed and developed.

## Summary
In essence, Deep Learning is a sub-field of Machine Learning that studies the design and development of learning systems that use Deep Neural Networks (which has mutliple hidden layers)

In the next blog post, we will discuss about some of the nuances of (Deep) Neural Networks with focus on terminologies that you need to know about (more like a cheat sheet to neural networks). Until then, bye...

