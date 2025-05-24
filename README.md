# Classify Object Behavior to Enhance the Safety of Autonomous Vehicles

## Overview
### Industrial-Project
Our project for Matlab Challenge 221: **Classify Object Behavior to Enhance the Safety of Autonomous Vehicles**. This project implements a **classifier to learn the behaviors of safe and risky actors in the scenario** using **MATLAB**. 

## Features
- **48 scenarios**: All realistic scenarios can be divided into three categories according to the object type - Ego vehicle with vehicles only, Ego vehicle with pedestrians only and Ego vehicle with vehicles and pedestrians.
- **radar sensor**: Mounted at the front of the ego vehicle, with the field of view azimuth set to 360 degrees. Data is updated every 100ms.
- **extracted features**: Positions(x, y, z), Velocities(vx, vy, vz), Speeds, Yaws, Angular Velocities, ActorID.
- **training model**: Medium Neural Network, best performance, with accuracy of 97.23% and 86.57% on validation and test sets respectively.

## Installation
Ensure you have **MATLAB_2024b** installed along with the following toolboxes and applications:

- Driving Scenario Designer from [Automated Driving Toolbox™](https://www.mathworks.com/products/automated-driving.html): Design driving scenarios, configure sensors, and generate synthetic data.
    
- Classification Learner from [Statistics and Machine Learning Toolbox™](https://www.mathworks.com/products/statistics.html): Train models to classify data using supervised machine learning.

### Running the Scenarios Simulation and Trained Classifier
Clone the repository and open scenario datasets in Driving Scenario Designer app, classification learner session in Classification Learner app.

## Files
- [ClassificationLearnerSession.mat](https://github.com/zly9604/Industrial-Project/blob/main/ClassificationLearnerSession.mat) - Classification Learner Session
- [MNN.m](https://github.com/zly9604/Industrial-Project/blob/main/MNN.m) - Medium Neural Network Model Program Code

## License
This project is licensed under the **MIT License**.
