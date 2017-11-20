---
layout: post
comments: true
title: Learning System (Machine Learning Intro)
category: intro
excerpt: In this post we focused on Learning Systems, giving a very high level overview of Machine Learning and different types of Learning Systems.
---

Hi readers,

This blog post focused on Learning systems, giving a very high level overview of **Machine Learning** and different types of Learning Systems.

## Learning Systems
As described from the previous blog post, **Learning** is a sub-field of AI research that focus on designing and developing intelligent machines that learns from examples (data). The fancy term used to describe activities involving research, development and deployment of Learning systems is **Machine Learning**. Simply put, Machine Learning is a sub-field of AI. Common AI techniques applied in Machine Learning includes; Aritificial Neural Networks (ANN), Support Vector Machines, Logistic Regression, K-means clustering etc. ANN is the most common technique used in Machine Learning, and its recent successes lead to the creation of a new sub-field (in Machine Learning) called **Deep Learning** (more on this later).

## Types of Learning
There are three major types of learning which influence how we design and develop our Learning Sytems. They are:
1. Supervised Learning
2. Reinforcement Learning
3. Unsupervised Learning

## Supervised Learning
Supervised Learning focuses on designing and building Learning Systems that are given examples (data) with labels (correct answer) assigned to each example. A good example of supervised learning process is depicted in how children are taught how to recognise objects (from drawings or images) in primary (elementary) schools. For example, a teacher will show students an "image/drawing of a ball" and then tell students that the object is a "ball". In this example, the image/drawing is the **example (data)** and the word “ball” is the **label** assigned to the example. Therefore, we can think of supervised learning as a **passive form of learning**. In essence, supervised learning enables Learning Systems to deduce patterns/co-relations between examples and their corresponding labels. Once this co-relation is learnt, the system should be able to use the knowledge to predict (to a certain degree of accuracy), what will be the label of an example (data) that it has not seen before. Continuing from our previous example, the teacher may decide to show the students another image/drawing of different ball and ask them what is the correct answer.

In recent years, this has been the most successful type of Learning, making its way out of research papers into real world practical applications ranging from speech recognition (think of Amazon's alexa, Apple's siri, Google speaker), natural language translation (e.g. french to english), facebook photo tagger, google photo search engine, self driving cars and so on.


## Reinforcement Learning
Unlike supervised learning that is passive, reinforcement learning is **active/exploratory form of learning**. Additionally, the Learning System is not given direct examples with their corresponding labels (correct answers). However, the Learning System is allowed to perform sequence of actions/step, and based on their actions, they are either **rewarded or punished**. The reward or punishment is only given at the end of the sequence of actions and not in-between. Using the reward/punishment based system, the Learning Systems attempts to learn to maximise its rewarded while minimising its punishment.

Some examples depicting reinforcement learning includes; 
1. In solving math problems, you perform a sequence of steps (calculation) and your reward will be getting the write answer or punishment as getting the wrong answer.
2. A baby learning how to walk will perform several manuevring steps with the aim to actually walk. The baby is rewarded by actually walking or punished by falling to the ground in attempt to walk.
3. A person whose anger always lead to physical fight is rewarded with a healthy condition if he/she calms down, or punished with a black eye if they choose to fight (and was punched in the eye).
4. Students learning about grades will learn that they are rewarded with a good grade when they work hard or punished with a bad grade when they fail to work hard. Working hard or not working hard is the sequence of steps involved.
5. A taxi driver driving a passenger from point A to B will be rewarded with a "tip" or punished by "no tip" from the passenger, depending on how enjoyable the ride (Adapted from Artificial Intelligence a Modern Approach by Russell and Norvig)

Research into Reinforcement Learning has been gaining tremendous momentum recently, as it is perceived as the next breed of Learning Systems that will have massive real world applications in the near future. Additionally researchers interested in building an Artificial General Intelligence (AGI) system view reinforcement learning as the next step towards that goal.

A recent feat of reinforcement learning was in its application by [DeepMind](https://deepmind.com/) in the AlphaGo software that beat a world champion in the game of Go (see [link](https://en.wikipedia.org/wiki/AlphaGo_versus_Lee_Sedol)). The achievement has spurred a lot of recent interest in this type of learning.

Due to its exploratory nature of learning, researchers usually test their reinforcement learning algorithms in a simulated environment (mostly video game worlds), thus allowing them to explore the simulated environment. Using simulated environment, scientist are using reinforcement learning to build Learning Systems that can learn how to walk. Once this research advances to a particular degree of efficiency, it can the Learning system software can then be implemented in the physical world robots.


## Unsupervised Learning
Unsupervised Learning can be either passive or exploratory (active) depending on the task. It involves designing and building Learning Systems that learns from examples (data) with no labels. The job of such system is to learn complex patterns from the data. This is particularly useful in business environment looking for insights from the business data. In fact, recommender systems popularly used by e-commerce (e.g. amazon, konga, jumia) and movie watch apps (e.g. Netflix) are good examples of application of unsupervised learning. The recommender system recommends other items that you can purchase (or watch as in the case of Netflix) based on your previous purchase/movie-watch history and also what other people with similar interest as yours would have purchased/watched.

Beyond business insights and recommender systems, unsupervised learning is also considered by some researchers as the next frontier for AI breakthrough. For example, common sense is not taught to humans by a teacher and sometimes not by reward/punished based system. We can learn common sense sometimes by observing the world. This can be framed as an unsupervised learning task. Yann LeCun (an AI scientist) believes that the next frontier for AI is building learning systems that [learns common sense from observing the world by watching videos](https://www.technologyreview.com/s/603803/facebooks-ai-chief-machines-could-learn-common-sense-from-video/).

## Extras
There's another type of learning not mentioned earlier. This is called **semi-supervised learning**. If you have a scale of two ends where one end is supervised learning and the other end is unsupervised learning, semi-supervised learning is in-between. It is not yet a very popular approach to learning, however, it is now being explored by researchers as another frontier for the future of learning. It involves designing and buidling learning systems from examples where some examples have labels and some do not have labels. Below is a excerpt about semi-supervised learning from the book **Aritificial Intelligence: A modern approach by Russell and Norvig**

*"
In semi-supervised learning we are given a few labeled examples and must make what we can of a large collection of unlabeled examples. Even the labels themselves may not be the oracular truths that we hope for. Imagine that you are trying to build a system to guess a person's age from a photo. You gather some labeled examples by snapping pictures of people and asking their age. That's supervised learning. But in reality some of the people lied about their age. It's not just that there is random noise in the data; rather the inaccuracies are systematic, and to uncover them is an unsupervised learning problem involving images, self-reported ages, and true (unknown) ages. Thus, both noise and lack of labels create a continuum between supervised and unsupervised learning."*
