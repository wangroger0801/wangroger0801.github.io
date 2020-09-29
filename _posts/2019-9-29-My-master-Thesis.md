---
layout: post
title: "A deep reinforcement learning agent modelfor autonomous racing"
author: "Naichen"
categories: experience
tags: [a,b]
image: master-thesis.gif
---
### An end-to-end Q-learning approach
In this thesis, an investigation of autonomous formula racing car driving by two deep reinforcement learning model is presented. The goal was to model a real-world problem and adapt two popular reinforcement learning method: deep deterministic policy gradient (DDPG) and dueling double Q-learning (DDQN). Furthermore, investigate methods of improving the training efficiency. The model uses an end-to-end strategy, where the input is a visual drive view from the OpenAI gym racing simulator, and the output is the steering, acceleration, and brake signals to the simulation. However, due to difficulties in training, the outputs were eventually reduced to steering actuation only. To improve training, the two extensions of human demonstration and convolutional variational autoencoder (CVAE) were introduced into the training program.The performance of the trails were of varied performance, where one agent the out of the rest trained by DDQN are managed to drive and finish the driving task after 30 epochs. The probable reasons for the success and failure using different modelling methods are discussed in this thesis.