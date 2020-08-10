# super-mario-Reinforcement-learning
It's a repository for super-mario Reinforcement learning

## Introduction
The objective of this repository is to explore the reinforcement-learning models for playing super-mario.

<p align="center">
  <img src="output1/video_1_1.gif">
  <img src="output1/video_1_2.gif">
  <img src="output1/video_1_4.gif"><br/>
  <img src="output1/video_2_3.gif">
  <img src="output1/video_3_1.gif">
  <img src="output1/video_3_4.gif"><br/>
  <img src="output1/video_4_1.gif">
  <img src="output1/video_6_1.gif">
  <img src="output1/video_7_1.gif"><br/>
  <i>Sample results</i>
</p>

## Method 

Reinforcement learning 

algorithm of reinforcement learning 

The algorithmn having model tring out different possibilities and improved based on the feedback give back by the environment. In this case, the game is the enviroment and the score or the distance traveled is the feedback. 

# Super Mario Bro Procedure (how to run code) 

 Git clone
 
 Create virtual environment
 
 Before modify model, delete all the weights
 
 ### on computer terminal:
 
 Python3 pip install pipenv
 
 Python3 -m pip install gym gym-super-mario-bros opencv-python torch torchvision
 
 Brew install ffmpeg
 
 pip3 install tensorboardX
 
 python3 train.py
 
 python3 test.py
 
 
 
 ### on Google colab:
 
 move git clone into colab
 
 !pip install gym gym-super-mario-bros opencv-python torch torchvision
 
 !pip install tensorboardX
 
 !python train.py
 
 !python test.py
 
 # Conclusion 
 
 This type of reinforcement learning algorithm is good for conquering simple game. The advantage that this type has is that the model is relativly simple and fast. The disadvantage is that it can only conquer simple game and takes many iterations in the enviroment to get to a relative good place, however getting environment that allows many attempts and processing at high speed is hard. Having complex model with previous knowledges and other features might be a good idea for dealing with complex game, but the problem is that the previous knowledges might takes years to train. 
