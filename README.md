# MATLAB Code and Results
This repository contains the MATLAB code and supplementary results for my Bachelor thesis on comparing a PID controller and a PPO reinforcement-learning controller for rover path following.

## Files
- `Code.zip`  
  Contains the main MATLAB code used for the project, including the PID controller, PPO training scripts, environment functions, path generation, and error calculations.
- `PID.zip`  
  Contains the PID simulation results and figures for the four reference paths.
- `RL_Final.zip`  
  Contains the final PPO agents, test results, metrics, and figures for the five training seeds per reference path.
- `RL_Test Runs.zip`  
  Contains additional PPO test runs and intermediate training results.

## How to use
1. Download and unzip `Code.zip`.
2. Open the folder in MATLAB.
3. Add the folder and subfolders to the MATLAB path.
4. Run `PID_Rover.m` for the PID results.
5. Run `main_train_PPO.m` to train PPO agents.
6. Run `main_test_PPO.m` to test a trained PPO agent.

The PPO code requires the MATLAB Reinforcement Learning Toolbox.

## Author
Nicolás Nogués Sarmiento  
Bachelor thesis, University of Groningen
