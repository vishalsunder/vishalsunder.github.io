---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

# At TCS Research #

## Agents with different behaviors for Contract Negotiation using Reinforcement Learning ##

_Mentors: Dr. Lovekesh Vig and Dr. Arnab Chatterjee (TCS Research, New Delhi)_

__Introduction:__ Automating the process of contract negotiation is important not just from an industrial point of view but also for all related problems where negotiation is required. The primary challenge in this endeavor is to suitably model the behavior of an _AI agent_.

* Trained Deep Learning agents capable of negotiating on a set of clauses in a contract agreement using a simple communication protocol using reinforcement learning.
* Modeled selfish and prosocial behavior to varying degrees in these agents and also trained a Meta agent with an ensemble of these behaviors.
* Results demonstrated that the agents are able to hold their own against human players and that the meta agent is able to reasonably emulate human behavior.

## An Ensemble of Deep and Shallow Learning to predict the Quality of Product Titles (CIKM-2017 data challenge) ##

_Self-mentored and co-worked with a teammate_

__Introduction:__  Given a set of product attributes, the task was twofold. First, to predict whether the product title is ’Clear’ and second whether it is ’Concise’.

* Developed an ensemble framework of Deep and Shallow learning for predicting the Clarity and Conciseness of the titles of marketed products.
* An attentive pooling approach was used to augment the learning of traditional CNNs and LSTMs for the given task along with LightGBM for shallow learning.
* Findings showed that an ensemble of these approaches do a better job than using them alone suggesting that the results of the deep and shallow approach are highly complementary.

[Report](https://vishalsunder.github.io/files/cikm-data-challenge.pdf)

## Information Bottleneck Inspired Method For Chat Text Segmentation ##

_Mentors: Dr. Lovekesh Vig and Dr. Gautam Shroff (TCS Research, New Delhi)_

__Introduction:__ The task was to separate discussions on online chat forums into small granules of independent conversational segments.

* Developed a novel technique for segmenting chat conversations using the Information Bottleneck method, augmented with sequential continuity constraints.
* Utilized critical non-textual clues such as time between two consecutive posts and people mentions within the posts for effective segmentation.
* Experiments demonstrated that our proposed method yields an absolute (relative) improvement of as high as 3.23% (11.25%).

# Undergrad Projects #

## A package to implement Mason’s Gain Formula ##

_Mentor: Dr Gopal Sharma (Dept. of Electrical Engg., IIT-BHU)_

__Introduction:__ Mason’s Gain Formula is a method for finding transfer function of a linear signal flow graph.

* Developed a robust algorithm to implement Mason’s Gain Formula for finding the transfer function of a linear signal flow graph.
* Implemented the algorithm in C++ and developed a package for the same.
* This project was funded by the Design and Innovation Hub (DIH), IIT-BHU.

[Code](https://github.com/vishalsunder/MasonGain) and [Report](https://vishalsunder.github.io/files/REPORT_DIH.pdf)

## Face Recognition using Principal Component Analysis (PCA) and Neural Network ##

_Mentor: Dr. Sanjay Kumar Singh (Dept. of Computer Science and Engg., IIT-BHU)_

__Introduction:__ The aim was to build a package which can be used for classifying different face images into their corresponding identities.

* Obtained reduced set of features for a face image by applying PCA on a set of training images from the ORL face dataset.
* Trained a 2 layer neural network using the reduced set of features as input to predict the identity of a face. Used Matlab for implementation.
* Successfully classified 40 subjects achieving an accuracy of 97.5%.

[Code](https://github.com/vishalsunder/PCA-for-face-recognition)
