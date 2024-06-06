---
title: Play Chrome's Dino Game Physically 🦕
date: 2021-07-12 10:00:00 +/-0530
categories: [Project, Tutorial]
tags: [project,tinyml,hmi]
---

![Demo](https://hackster.imgix.net/uploads/attachments/1323340/powered_by_(1)_THUZrCwShJ.gif?auto=format%2Ccompress&gifq=35&w=900&h=675&fit=min&fm=mp4)

TL;DR: In this project, we will physically play the Chrome dino game with the help of machine learning and embedded electronics.

Due to the 2nd wave of a global pandemic, I was kept inside my house without doing much physical activity, Last month, I got an Intestinal gas related issue and consulted a doctor, and he mentioned doing small physical activities will help avoid these kinds of problems, I tried to use a mobile application that helped to do physical activities without equipment, I also invited my little nephews to do exercise with me, but they are not interested. Then I thought of doing something fun and burning the calory. That's how the project was born.

This project was both fun and helped us to burn some calories to make us healthy during the pandemic. 🤗

## How It's played?
1. Connect Wio Terminal to Computer
2. Open Dino chrome://dino/
3. Connect Wio Terminal
4. Jump 🙌

## How It's working

The SeeedStudio Wio Terminal is attached to the user body/Placed in the pockets, and it runs EdgeImpluse based tinML model for inferencing, When the User Jump, The Wio Terminal read data from the inbuilt accelerometer and run the edge Impluse based Inferencing inside the Wio terminal and decide the user activity, here it's idle or jump. If it's a Jump activity the wio terminal will simulate keystrokes send to the computer via HID Interface.

![How It's working](https://hackster.imgix.net/uploads/attachments/1323141/archi_WGLSD99tAr.png?auto=compress%2Cformat&w=740&h=555&fit=max)

## How to build one?

Thanks to Tiny Machine learning platform Edge Impulse studio and Wio terminal for making the project easier. The project is a combination of machine learning and embedded electronics, and I will explain step by step to make this project your own.

![How to build one?](https://hackster.imgix.net/uploads/attachments/1323143/archi2_b28LUSQjTG.png?auto=compress%2Cformat&w=740&h=555&fit=max)

First, we need to collect the data, Then we need to train the data set with a specific ML algorithm, after that, we will create an Impulse, Then with the Impulse, we will extract features and create an inferencing model and finally, we load inferencing model to Wio Terminal and inference raw signal and classify.

Don't worry if you can't catch up with all of them, You can follow the steps here at - [Play Chrome's Dino Game Physically 🦕](https://www.hackster.io/Salmanfarisvp/play-chrome-s-dino-game-physically-db42c2)