# DC Motor Position Identification and PID Control

This project presents the model identification of a DC motor based on its position step response and the design of a PID controller using MATLAB/Simulink.

## Project Overview

The DC motor position response is analyzed to extract key step response parameters such as maximum overshoot and settling time. These parameters are used to estimate the damping ratio and natural frequency of an equivalent second-order transfer function. After identifying the motor model, a PID controller is designed and tuned using PID Tuner.

## Main Features

- DC motor position step response analysis
- Calculation of overshoot and settling time
- Estimation of damping ratio and natural frequency
- Identification of an equivalent transfer function
- Continuous PID controller design
- Discrete PID controller implementation
- Comparison between the motor response and the identified model response

## Tools Used

- MATLAB
- Simulink
- PID Tuner

## Repository Structure

```text
Report/          Final project report
Simulink_Model/  Simulink model files
MATLAB_Code/     MATLAB scripts
Figures/         Step response and PID tuning figures
Results/         Identified transfer function and numerical results
