# Deep-Learning-Tutorial-for-Beginners

<font color='green'>
    
**Deep Learning Tutorial for Beginners 은 Deep Learning 을 공부하기 전에 필수(?)적으로 숙지 하여야 할 기본적인 것들을 설명합니다.** 
    
* 이 노트북은 Data ScienceTutorial for Beginners(https://github.com/wowhb/Data-Science-Tutorial-for-Beginners) 를 이어서 작성하는 것으로 Deep Learning Tutorial 이라고 생각하시면 됩니다. kaggle 의 DATAI팀의 작업물을 번역 및 설명을 추가하여 쉽게 풀어쓴 노트북입니다.
    
* 이번 노트북에서 기본적인 모든 것을 하나하나 설명하려고 합니다.     
* 키워드를 중심으로 정의합니다.
* 이 튜토리얼의 끝에는 딥러닝에 대한 충분한 정보가 수록되어 있어 더 깊이 학습할 수 있습니다.


## 데이터셋 

Sign Language Digits Dataset

수화(signed language라고도 함)는 의미를 전달하기 위해 수동 통신을 사용하는 언어다. 이것은 손동작, 움직임, 손가락의 방향, 팔이나 몸의 방향, 그리고 화자의 생각을 전달하기 위한 얼굴 표정을 동시에 사용하는 것을 포함할 수 있다. 
Source: https://en.wikipedia.org/wiki/Sign_language

![image](https://user-images.githubusercontent.com/55519278/78900950-90c7c500-7ab2-11ea-977a-6f53efcd03f4.png)

* Image size: 64x64
* Color space: Grayscale
* File format: npy
* Number of classes: 10 (Digits: 0-9)
* Number of participant students: 218
* Number of samples per student: 10

<font color='red'>
  
## Content:
  
  
  
  
  
* [Introduction](#1)
* [Overview the Data Set](#2)
* [Logistic Regression](#3)
    * [Computation Graph](#4)
    * [Initializing parameters](#5)
    * [Forward Propagation](#6)
        * Sigmoid Function
        * Loss(error) Function
        * Cost Function
    * [Optimization Algorithm with Gradient Descent](#7)
        * Backward Propagation
        * Updating parameters
    * [Logistic Regression with Sklearn](#8)
    * [Summary and Questions in Minds](#9)
    
* [Artificial Neural Network](#10)
    * [2-Layer Neural Network](#11)
        * [Size of layers and initializing parameters weights and bias](#12)
        * [Forward propagation](#13)
        * [Loss function and Cost function](#14)
        * [Backward propagation](#15)
        * [Update Parameters](#16)
        * [Prediction with learnt parameters weight and bias](#17)
        * [Create Model](#18)
    * [L-Layer Neural Network](#19)
        * [Implementing with keras library](#22)
* Time Series Prediction: https://www.kaggle.com/kanncaa1/time-series-prediction-with-eda-of-world-war-2
* [Artificial Neural Network with Pytorch Library](#23)
* [Convolutional Neural Network with Pytorch Library](#24)
* [Recurrent Neural Network with Pytorch Library](#25)
* [Conclusion](#20)

