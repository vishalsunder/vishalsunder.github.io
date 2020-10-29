---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
# Course Projects #

## CSE-5243 Introduction to Data Mining (Spring 2020) ##

* Classification of text data (2nd best result in the class) [Report](https://vishalsunder.github.io/files/class_5243.pdf)
* Clustering of text data (Best result in the class; Best report award) [Report](https://vishalsunder.github.io/files/clus_5243.pdf)

# At OSU #

## Studying Ways to Efficiently Handle Class-Imbalance Issues in Closed-Domain Dialogue Systems ##
_Mentor: Dr. Eric Fosler-Lussier_

__Introduction:__ Due to the limited amount of data that can be realistically collected for specialized dialogue domains, the dataset becomes highly class-imbalanced to allow for fine-grained user queries.

* Built a novel, model-agnostic end-to-end pairwise learning framework to tackle the said issue.
* The framework combines a few-shot classification strategy with an interpolation based data-augmentation technique.
* Achieved significant improvements in macro-F1 score for the Virtual Patient dialogue project.

[Code](https://github.com/OSU-slatelab/vp-pairwise), [Paper](https://arxiv.org/pdf/2010.15090.pdf)

# At TCS Research #

## One-shot Information Extraction from Document Images using Neuro-Deductive Program Synthesis ##

_Mentors: Dr. Ashwin Srinivasan (BITS Pilani, Goa), Dr. Lovekesh Vig and Dr. Gautam Shroff (TCS Research, New Delhi)_

__Introduction:__ The task was information extraction from document images in a data-efficient manner.

* Used pre-trained Deep Learning models for reading document images and converting them into a structured form by populating a predefined database schema.
* Entity-specific extraction programs were learnt using proofs constructed by a meta-interpreter in a manner similar to explanation-based generalization.
* In most cases a single training example together with a noisy-clone of itself suffices to learn a program-set that generalizes well on test documents.


## CRESA: A Deep Learning Approach to Competing Risks, Recurrent Event Survival Analysis ##

_Mentors: Dr. Ranjitha Prasad (TCS Research, New Delhi)_

__Introduction:__ The task was to infer survival-time from time-to-event data in a _recurrent event_ scenario in the presence of one or more _competing risks_.

* Developed an _LSTM-based_ model to tackle the recurrent event scenario of the survival analysis.
* Modelled a recurrent time concordance-index based loss function to train the neural network.
* Demonstrated a superior predictive performance of the proposed approach (single and multiple risk scenarios) as compared to traditional model-based approaches, and deep learning based approaches for synthetic and state-of-the-art public datasets.

[Paper](https://vishalsunder.github.io/files/CRESA.pdf)

## Agents with different behaviors for Contract Negotiation using Reinforcement Learning ##

_Mentors: Dr. Lovekesh Vig and Dr. Arnab Chatterjee (TCS Research, New Delhi)_

__Introduction:__ Automating the process of contract negotiation is important not just from an industrial point of view but also for all related problems where negotiation is required. The primary challenge in this endeavor is to suitably model the behavior of an _AI agent_.

* Trained Deep Learning agents capable of negotiating on a set of clauses in a contract agreement using a simple communication protocol using reinforcement learning.
* Modeled selfish and prosocial behavior to varying degrees in these agents and also trained a Meta agent with an ensemble of these behaviors.
* Results demonstrated that the agents are able to hold their own against human players and that the meta agent is able to reasonably emulate human behavior.

[Paper](https://vishalsunder.github.io/files/acan_arxiv.pdf)

## An Ensemble of Deep and Shallow Learning to predict the Quality of Product Titles (CIKM-2017 data challenge) ##

_Self-mentored and co-worked with a teammate_

__Introduction:__  Given a set of product attributes, the task was twofold. First, to predict whether the product title is ’Clear’ and second whether it is ’Concise’.

* Developed an ensemble framework of Deep and Shallow learning.
* An attentive pooling approach was used to augment the learning of traditional CNNs and LSTMs for the given task along with LightGBM for shallow learning.
* Findings showed that an ensemble of these approaches do a better job than using them alone suggesting that the results of the deep and shallow approach are highly complementary.

[Code](https://github.com/vishalsunder/CIKM-AnalytiCup-2017-Lazada-Product-Title-Quality-Challenge) and [Report](https://vishalsunder.github.io/files/cikm-data-challenge.pdf)

## Knowledge Extraction for FAQ ##

_Mentors: Dr. Lovekesh Vig and Dr. Gautam Shroff (TCS Research, New Delhi)_

__Introduction:__ The task was to develop an artiicial agent for retrieving relevant parts of a master document (company's policy document) for assisting human agent in preparing the FAQ list.

* Trained a Siamese LSTM network which tries to align questions and their corresponding answers in a high dimensional space. The available FAQ list was utilized for training the network.

* The resulting network not only learns to align the question not only to its answer but also to its relevant section in the master document.

* The model was tested on a new (updated) master document and achieved a Mean Reciprocal Rank (MRR) of 0.70.

## Information Bottleneck Inspired Method For Chat Text Segmentation ##

_Mentors: Dr. Lovekesh Vig and Dr. Gautam Shroff (TCS Research, New Delhi)_

__Introduction:__ The task was to separate discussions on online chat forums into small granules of independent conversational segments.

* Developed a novel technique for segmenting chat conversations using the Information Bottleneck method, augmented with sequential continuity constraints.
* Utilized critical non-textual clues such as time between two consecutive posts and people mentions within the posts for effective segmentation.
* Experiments demonstrated that our proposed method yields an absolute (relative) improvement of as high as 3.23% (11.25%).

[Paper](https://vishalsunder.github.io/files/ijcnlp2017.pdf)

# Undergrad Projects #

## A package to implement Mason’s Gain Formula ##

_Mentor: Dr Gopal Sharma (Dept. of Electrical Engg., IIT-BHU)_

__Introduction:__ Mason’s Gain Formula is a method for finding transfer function of a linear signal flow graph.

* Developed a robust algorithm to implement Mason’s Gain Formula.
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
