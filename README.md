# udacity-carnd-2017
List of projects and notes when going through Udacity's Self-driving Car Nanodegree in 2017

## Term1: Computer Vision and Deep Learning

Useful resources:
https://github.com/udacity/CarND-Term1-Starter-Kit


### Project1: Finding Lane Lines

Instruction: https://github.com/udacity/CarND-LaneLines-P1

Solution: https://github.com/dingran1019/lane-detection

Notes: 
 * HSV really helped in some cases to resolve yellow-vs-light-gray confusion in grayscale
 * Start with more line segments then rigorously reject
 * Wish I could use info from past frames to track lanes, not easily done in current framework


### Project2: Traffic Sign Classification

Instruction: https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project

Solution: https://github.com/dingran1019/traffic-sign-classifier

Notes:
 * grayscale seems more reliable than color images
 * augmenting data set really helped
 * retraining model worked well
 * mutli-scale feature CNN worked well but not as impressive as anticipated
