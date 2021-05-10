# Introduction to Machine Learning and Deep Learning using Python

Python is one of the most widely used and highly valued programming languages in
the world, and is especially widely used in machine learning and for deep
learning. In this two day course, we provide an introduction to machine learning
and deep learning using Python. We begin by providing an overview of the machine
learning and deep learning landscape, and discuss the prominent role that Python
has come to play in this area. We then turn to machine learning in practice, and
for this, we will primarily using the widely used and acclaimed `scikit-learn`
toolbox. We begin with  binary and multiclass classification problems, then
look at decision trees and random forests, then look at unsupervised learning methods, all of which are major topics in
machine learning. We then cover artificial neural networks and deep learning.
For this, we will using the PyTorch deep learning toolbox. Here, we will cover
the relatively easy to understand *multilayer perceptron* and then turn to
*convolutional neural networks*.

## Intended Audience

This course is aimed at anyone who is interested in learning the machine
learning or deep learning using Python, both of which have major applications
both in industry and in academia.

## Teaching Format

This course will be hands-on and workshop based. Throughout each day, there will
be some brief introductory remarks for each new topic, introducing and
explaining key concepts.

The course will take place online using Zoom. On each day, the live video
broadcasts will occur between (UK local time) at:

* 12pm-2pm
* 3pm-5pm
* 6pm-8pm

All sessions will be video recorded and made available to all attendees as soon
as possible, hopefully soon after each 2hr session.

Attendees in different time zones will be able to join in to some of these live
broadcasts, even if all of them are not convenient times.

By joining any live sessions that are possible, this will allow attendees to
benefit from asking questions and having discussions, rather than just watching
prerecorded sessions.

Although not strictly required, using a large monitor or preferably even a
second monitor will make the learning experience better.

All the sessions will be video recorded, and made available immediately on a
private video hosting website. Any materials, such as slides, data sets, etc.,
will be shared via GitHub.

## Assumed quantitative knowledge

We will assume familiarity with some general statistical and mathematical
concepts such as matrix algebra, calculus, probability distributions. However,
expertise with these concepts are not necessary. Anyone who has taken any
undergraduate (Bachelor's) level course in mathematics, or even advanced high
school level, can be assumed to have sufficient familiarity with these concepts.

## Assumed computer background

We assume familiarity with using Python, general purpose programming in Python,
and numerical programming in Python.  Note that both of these topics covered
comprehensively in two preceding two-day courses, which together will provide
all the computing prerequisites for this course.


## Equipment and software requirements

Attendees of the course must use a computer with Python (version 3) installed.
All the required software, including Python itself, the development and
programming environment tools, and the Python packages, are free and open source
and are available on Windows, MacOs, and Linux. Instructions on how to install
and configure all the software are [here](software.md).
We will also provide time during the workshops to ensure that all software is
installed and configured properly. For deep learning, we will also make use of
Google's Colaboratory https://colab.research.google.com/, which will give us
access to graphical processing units.

# Course programme

## Day 1

* Topic 1: *Machine learning and Deep Learning Landscape*. Concepts like machine
learning, deep learning, big data, data science have become widely used and
celebrated in the last 10 years. However, their definitions are relatively
nebulous, and how they related to one another and to major fields like
artificial intelligence and general statistics are not simple matters. In this
introduction, we briefly overview the field of machine learning and deep
learning, discussing its major characteristics and sub-topics, and also discuss
the prominence of Python in the area.

* Topic 2: *Classification problems*. Classification problems is one of the
bread and butter topics in machine learning, and is usually the first topic
covered in introductions to machine learning. Here, we will cover image
classification (itself a "hello world" type problem in machine learning), and
particularly focus on logistic regression and support vector machines (SVMs).

* Topic 3: *Decision trees and random forests*. Decision trees are a widely  
used machine learning method, particularly for classification. Random forests  
are an *ensemble learning* extension of decision trees whereby large number of
decision tree classifiers are aggregated, which often leads to much improved
performance.

## Day 2

* Topic 4: *Unsupervised machine learning*. Unsupervised learning is essentially
a method of finding patterns in unclassified data. Here, we will look at two of
the most widely used unsupervised techniques: k-means clustering and
probabilistic mixture models.

* Topic 5: *Introducing artificial neural networks and deep learning with
PyTorch*. Python provides many popular libraries for artificial neural networks
and deep learning. These include Keras and TensorFlow. Here, we will use
PyTorch, which is a relatively new but increasingly high-level neural network
model building and training language. These models often use graphical
processing units (GPUs) for computing. Given that most personal computers don't
have adequate GPUs, we will use Google's Colaboratory
https://colab.research.google.com/, which is a free Python Jupyter notebook
service from Google.

* Topic 6: *Multilayer perceptons*. Multilayer perceptrons are very powerful,
yet relatively easy to understand, artificial neural networks. They are also the
simplest type of deep learning model. Here, we will build and train a
multilayer perceptron for a classification problem.

* Topic 7: *Convolutional neural networks*. Convolutional neural networks (CNNs)
have proved high successful at image classification, primarily due to their
*translation invariance*, which is highly suitable for computational vision.
Here, we use PyTorch to build and train a CNN for image classification.
