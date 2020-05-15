# convolution neural network project

---

### Table of Contents

In this section you will know More bout how to build Neural Network :smiley:

- [Description](#description)
- [Technologies](#Technologies)
- [Link dataset](#dataset)

---

## Description :point_left:



In this project you will learn how to add augmentation to dog and cat dataset to

overcome overfitting which is found in small dataset 

You've heard the term overfitting a number of times to this point. Overfitting is simply the concept of being over specialized

in training -- namely that your model is very good at classifying what it is trained for, but not so good at classifying things

that it hasn't seen. In order to generalize your model more effectively, you will of course need a greater breadth of samples to

train it on. That's not always possible, but a nice potential shortcut to this is Image Augmentation

---

# Augmentation 

Image Augmentation is a very simple, but very powerful tool to help you avoid overfitting your data. The concept is very simple

though: If you have limited data, then the chances of you having data to match potential future predictions is also limited, and 

logically, the less data you have, the less chance you have of getting accurate predictions for data that your model hasn't yet 

seen. To put it simply, if you are training a model to spot cats, and your model has never seen what a cat looks like when lying 

down, it might not recognize that in future.

Augmentation simply amends your images on-the-fly while training using transforms like rotation. So, it could 'simulate' an 

image of a cat lying down by rotating a 'standing' cat by 90 degrees. As such you get a cheap way of extending your dataset 

beyond what you have already.

To learn more about Augmentation, and the available transforms

---


## how-to-use :ear:






---

## Technologies

- image processing
- deep learning
- tensrflow framework
- data augmentation technique

---


## dataset

To download click Here :point_down:

[download](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/May/5aea1b91_train-test-data/train-test-data.zip)




[Back To The Top](#README.md) :point_up:

---

End :raising_hand:
 


