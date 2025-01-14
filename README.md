# Omdena-Quantum-Self-Driving Project 2023

## Project Lead: Raghav Thiruvallur (Please contact raghav.thiruv@gmail.com for any questions)

# Variational Quantum Convolutional Neural Network for Image Recognition to Determine Steering Angle for Autonomous Vehicles 

## Goal
Design and implement a Variational Quantum Algorithm alongside a classical Machine Learning model to determine the steering angle correction for self-driving vehicles

## Motivation
* Existing classical deep neural networks yield good performance
* Aim for more generalized models and higher efficiency while training and testing
* Can we harness the power of quantum computing to help increase generality and/or efficiency?

## Project Approach
1. Dataset: 
    * Find a dataset which contains front-camera view of the road and corresponding steering wheel angle change to keep the car straight.
    * Understand the dimensions and variety of input images
    * Clean and preprocess the dataset
2. Build the Quantum and Classical Models
    * Group 1: Create a classical Convolutional Neural Network (CNN) to predict the vehicle's steering angle based on images
    * Group 2: Simultaneously build and test a Variational Quantum Algorithm (VQA) 
        * Use a simple existing vanilla neural network in place of the CNN
        * Build various ansatze circuits and compare their performances (e.g., convergence, accuracy, loss, runtime, etc.) 
3. After initial development, combine CNN and VQA, and fine-tune the model
4. Import the model and work with vehicle-environment simulations (e.g., CARLA, AirSim) and test hybrid model in the environment. 

## Project Architecture
<p align="left">
  <img src="https://user-images.githubusercontent.com/69136009/216572541-905d78ac-8088-46e0-b9a3-590c36a0bd00.png" width="745" title="VQCNN Architecture">
</p>

### Deep Learning Neural Networks + Variational Quantum Circuit 
Training models using 4 qubit HVA circuit + Deep Learnning Neural netwwrk

## Resource
- Omdena Local Chapter Link [here](https://omdena.com/chapter-challenges/quantum-self-driving-neural-networks/)
- Omdena Github Link [here](https://github.com/raghav-thiruv/Omdena-Quantum-Self-Driving)
- Other Link [here](https://github.com/soundwaverohit/QuantumSelfDriving)

