---
layout: default
---
# SLAM and Reinforcement Learning in 3D environments

## Introduction and Motivation 

The idea for the project started from a very basic desire to use this time to learn more about SLAM and RL. 
After some research and reading papers about LSD Slam and ORB-Slam(or ORB slam), we formed the problem statement:
_How augmenting input features from SLAM affects the performance of RL in 3D environments?_
We each tried a different slam library pyslam, orbslam2 and orbslam3 and deep q learning architecture in the [gym-miniworld 3d environment](https://github.com/maximecb/gym-miniworld). 

__Why is this important?__

We are looking into a future where a robot might be used to solve some challenging and difficult task without apriori knowledge about the environment. 
Very briefly explained SLAM has three important features: pose estimation, mapping in real-time and efficiently and planning where to go next.
For the RL we have an agent that chooses actions and the environment to interact with. 
In this project we used a minimalist 3D RL environment with navigation based reward. 
The idea behind the solution is the assumption that SLAM will localize more efficiently than a DQN. 
However, one downside is the complexity of implementation for SLAM that slows it down. 


## Project Proposal

[Link to the project proposal](./assets/766_final_project.pdf)

## Midterm Report 

[Link to the midterm report](./assets/766_midterm_report.pdf)


## Project Timeline

| When                 | Task                                               | 
|:---------------------|:---------------------------------------------------|
| Before Feb 24        | Project Proposal and the initial webpage           | 
| Feb 25 - Mar 10      | Create DQN Miniworld benchmark                     | 
| Mar 11- Mar 20       | Set up SLAM with Miniworld                         |
| Mar 21- Apr 6        | Design input encoding for SLAM features into       | 
| Apr 7 - Apr 21       | Contrast performance of DQN on Miniworld           | 
| Before May 5         | Complete project writeup and presentation          | 

## Background

## Approach

## Results

### PySLAM

### ORB-SLAM2

### ORB-SLAM3

## Demos
