# general-ai
Experiments on general AI


## Overview 

In general this repo is about effort which does not assume that everything has to be learnt from data from scratch. E.g. A vision system does not have to learn that color is a concept. It just is because our vision has that as inbuilt aspect of vision. Similarly for depth of field etc. Similarly auditory system does not have to learn what volume is or pitch or frequency is, it just knows. And touch does not have to learn what temprature is, it just knows. 

Also, a lot of ML Is based on only data driven knowledge, but logic is to large extend ignored. This repo has belief that logic and reasoning by analogy and generalization is important. 

How all these concepts be introduced into AI is not known, but we know these are needed for general AI. Maybe it would be based on deep learning, maybe based on hard coded programming, maybe something else. As a github repo, we want to be able to do lot of experiments cheaply and fast. 

## Weakness of present approaches

Present ML approaches are purely statistical/mathematical in nature and create one model per task. This works for narrow intelligence but breaking out of narrow zone requires more than this approach. Below are some areas that need improvements

1. New Concept - Present approaches lack ability to create new concept without any supervision or with minimal supervision
1. Logical Thinking Based on Attention - We humans can pay attention to a topic, and literally logically derive a conclusion without any stats or maths involved (except logic). Machines Presently don't do that. There is excessive dependency of prediction functions. 
1. Knowledge Graph / Memory - Present approaches devliver one new model for every narrow intelligence task. We on other hand don't do just one task but many and can switch models being used quickly depending on task at hand. There has to be a coordination mechanism for
1. Isolated Models - A vision model and NLP model and Concept Model and Memory Model should not work in isolation but together


## Experiments

1. [Extracting Spatial Concepts (New Concept Automatically)](01-SpatialConceptsModel/SpatialConcept.md)- Much of vision ML field is filled with prediction based on image vector, using for example CNN model. This whole approach is neglecting a more basic problem of extracting concept from image, or segmenting the image into different conceptual areas based on spatial, depth and boundaries information. This experiment would try to extract these concepts out of image. The concepts would have no name early on but could later tie to a NLP or memory model concept. The whole idea of using a non spatial vector and looking at whole vector, instead of each pixel individually and as whole, is flawed.

2. Combined Vision, NLP Model and Memory Model - Vision by itself is much less useful without language and language by itself is much less useful without vision. Why do present models specialize in either vision or lanaguage but not both. Morever, Memory is important to tie these together. This experiment would try to train a Vision model (which can extract spatial concepts automatically), with a language and memory model           



![Combined Model](/images/combined-model.png)
