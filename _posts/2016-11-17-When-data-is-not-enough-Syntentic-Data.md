---
layout: post
title: 'When data is not enough, Synthetic Data'
published: true
---


In machine learning is a common problem is the amount of data that we have, not always we can have gigabytes of information on our databases, data is the most precious result in machine learning and is understandable that is very scarce for our problems, the ones who own most of the data are the kings in the machine learning world, for example, Google has been gathering our data for years with only on objective in mind to mine this date using sophisticated statistics algorithms or machine learning algorithms.

Most of the machine learning algorithms find patterns in the data, if this data is scarce the algorithm simply does not work, in this case, our only choice is to tweak the current data and feed it to the algorithm or create new data ourselves.

## Synthetic data by Tweaking
A good example of tweaking de data is when your neural network is learning to recognize characters and we have a bunch of images each one representing a character, lets say that we have pictures from the letter A to the Z that's 23 pictures with different writings and that we have like a 20 sets of this 23 set pictures with different writings, this maybe could be enough to feed the neural network but we can do it better by rotating the images from each seat by a couple of degrees at random configurations and feed it to the neural network by doing this we are boosting the neural network confidence because now the neural network can understand the concept of the letter and just the concept of the image.

## Synthetic data by Creation
A good example of data by creation is when for example your are trying to create a neural network for autonomous cars like tesla or google, a nice approach will be to attach a camera to a car to capture pictures every second of the front road and pair it with the wheeling steer degree angle, with a couple of test with cars and real drivers we could get a bunch of data, but if you think about it, we were only be constrained to the test roads that we are testing! and that could be kind of insecure and dangerous for the autonomous car.
In this case we can make use of synthetic data by creation, for example we can spend more time creating a car simulator that behaves like a game simulator that could take months to do if not years, this simulator could generate random roads and try using the currently trained network if the predictions over the road are ok or it got crashed, with this kind of automation we are generating tons of data in a simulated environment and if you think about it makes sense although is not real. I think Tesla or Google have been working on programs of simulators just to feed the neural network for the autonomous car.
