# udacity-carnd-2017
List of projects and notes when going through Udacity's Self-driving Car Nanodegree in 2017

## Table of Content

* [Term1: Computer Vision and Deep Learning](#term1-computer-vision-and-deep-learning)
  * [Project1: Finding Lane Lines](#project1-finding-lane-lines)
  * [Lab: TensorFlow Neural Network](#lab-tensorflow-neural-network)
  * [Lab: LeNet In TensorFlow](#lab-lenet-in-tensorflow)
  * [Project2: Traffic Sign Classification](#project2-traffic-sign-classification)
  * [Lab: AlexNet](#lab-alexnet)
  * [Lab: VGG, Inception (GoogLeNet) and ResNet](#lab-vgg-inception-googlenet-and-resnet)


---
## Term1: Computer Vision and Deep Learning

Useful resources:
* python environment: https://github.com/udacity/CarND-Term1-Starter-Kit
* wrote quite a few markdown reports, here are few useful tools for markdown
  * cheatsheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
  * local rendering: https://github.com/joeyespo/grip
    * run ```grip --user <your username>``` to avoid reaching github api call limits for anonymous users
  * generating TOC: https://github.com/ekalinin/github-markdown-toc
* tensorflow best practice: https://github.com/aicodes/tf-bestpractice

---
### Project1: Finding Lane Lines

Instruction: https://github.com/udacity/CarND-LaneLines-P1

Solution: https://github.com/dingran1019/lane-detection

Notes: 
 * HSV really helped in some cases to resolve yellow-vs-light-gray confusion in grayscale
 * Start with more line segments then rigorously reject
 * Wish I could use info from past frames to track lanes, not easily done in current framework

---
### Lab: TensorFlow Neural Network
https://github.com/dingran1019/CarND-TensorFlow-Lab

---
### Lab: LeNet In TensorFlow
https://github.com/dingran1019/CarND-LeNet-Lab

--- 
### Project2: Traffic Sign Classification

Instruction: https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project

Solution: https://github.com/dingran1019/traffic-sign-classifier

Notes:
 * Grayscale seems more reliable than color images
 * Augmenting data set really helped
 * Retraining model worked well
 * Mutli-scale feature CNN worked well but not as impressive as anticipated
 * Learned a lot from https://navoshta.com/traffic-signs-classification/

---
### Lab: AlexNet
https://github.com/dingran1019/CarND-Alexnet-Feature-Extraction

---
### Lab: VGG, Inception (GoogLeNet) and ResNet
https://github.com/dingran1019/CarND-Transfer-Learning-Lab




