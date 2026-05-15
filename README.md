# PMSM-Drive-FOC-dSPACE
Real-time PMSM motor drive implementation using FOC and SVPWM on dSPACE Scalexio for EV applications.
# Three-Phase VSI-Based PMSM Drive using dSPACE Scalexio

## Overview
This project presents the real-time implementation of a three-phase Voltage Source Inverter (VSI) based PMSM drive system for Electric Vehicle (EV) and industrial motor control applications using dSPACE Scalexio and MATLAB/Simulink.

The system implements advanced motor control techniques including:
- Field Oriented Control (FOC)
- Space Vector PWM (SVPWM)
- Closed-loop current and speed PI controllers

The project focuses on achieving high dynamic response, low torque ripple, and accurate speed tracking under varying load conditions.

---

## Objectives
- Implement real-time PMSM motor control using dSPACE Scalexio
- Develop SVPWM-based three-phase inverter control
- Achieve stable speed and torque response
- Minimize steady-state error and torque ripple
- Analyze real-time motor performance using ControlDesk

---

## Tools & Technologies
- MATLAB/Simulink
- dSPACE Scalexio
- ControlDesk
- PMSM Motor
- Voltage Source Inverter (VSI)
- Field Oriented Control (FOC)
- SVPWM
- PI Controllers

---

## System Architecture

### Main Components
- PMSM Motor
- Three-Phase VSI
- dSPACE Scalexio Controller
- Current Sensors
- Speed Feedback Encoder
- DC Supply

---

## Control Algorithm

### Field Oriented Control (FOC)
FOC is implemented using:
- Clarke Transformation
- Park Transformation
- dq-axis current control
- PI current regulators

### SVPWM
Space Vector PWM is used for:
- Better DC bus utilization
- Reduced harmonic distortion
- Improved inverter efficiency

---

## Features
- Real-time closed-loop motor control
- High-speed response
- Stable operation under load variation
- Reduced torque ripple
- Accurate speed tracking

---

## Results
### Achievements
- Settling time reduced to less than 35 ms
- Steady-state speed error below 2%
- Torque ripple reduced by approximately 20%
- Improved DC bus utilization using SVPWM

---

## Repository Structure

```text
MATLAB_Simulink_Model/   -> Simulink models
ControlDesk_Setup/       -> dSPACE ControlDesk files
Waveforms/               -> PWM and phase current waveforms
Results/                 -> Speed and torque response plots
Hardware_Setup/          -> Hardware setup images
Documentation/           -> Reports and technical notes
