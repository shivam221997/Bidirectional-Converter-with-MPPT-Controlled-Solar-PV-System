# Bidirectional Converter with MPPT Controlled Solar PV System
This repository contains the implementation and simulation of a bidirectional DC-DC converter integrated with a solar photovoltaic (PV) system, using Maximum Power Point Tracking (MPPT) for efficient charging and discharging of a battery storage system. The research is conducted by Prashant, Amurt Prakash, Shivam Kumar, Kaushik Dubey, and Prashant Kumar Pandey from the Department of Electrical Engineering, JSS Academy of Technical Education, Noida, U.P, INDIA.

## Abstract
The increasing energy demand and the depletion of fossil fuels necessitate the shift towards renewable energy sources. Solar energy, despite its limitations, has become a popular alternative. This project focuses on improving the reliability and efficiency of solar PV systems using a bidirectional DC-DC converter with MPPT. The proposed system is simulated in Simulink, demonstrating effective battery charging and discharging while interfacing with both DC and AC loads.

## Features
  MPPT Controlled Solar PV System: Implements incremental conductance method for maximum power point tracking to optimize solar energy       utilization.
  Bidirectional DC-DC Converter: Facilitates two-way power flow between the battery and load, operating in both buck and boost modes.
  Simulink Implementation: Comprehensive simulation of the system components and their interactions.
## Table of Contents
### Introduction
### System Design
### Solar PV Cell Modeling
### MPPT Functionality
### Bidirectional DC-DC Converter
### Matlab Simulink Diagram
### Simulation and Results
### Usage
### Contributors
### References

## Introduction
The rapid depletion of fossil fuels and their negative impact on the environment drive the need for renewable energy sources. Solar energy is a viable alternative, though it presents challenges like variability due to environmental conditions. To address these, MPPT techniques and power converters are used to maximize efficiency.

## System Design
Solar PV Cell Modeling
A solar PV system converts sunlight into electrical energy. The equivalent circuit of a solar cell includes photocurrent, shunt resistance, and series resistance. The I-V and P-V characteristics are crucial for understanding the performance under different conditions.

![ef](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/ab83db3a-d0c3-4331-9df9-aefd864f2403)
![io](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/6a925e85-c652-45e1-9dcc-31b6da7cba8e) 
    
  (I-V characteristic of solar cell)


## MPPT Functionality
MPPT ensures that the solar PV system operates at its maximum power point despite changing environmental conditions. The incremental conductance method compares the incremental and instantaneous conductance to determine the optimal operating point.

![image_7](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/116853cd-5371-49dd-aff3-d0d53965bee2)

## Bidirectional DC-DC Converter
The bidirectional converter supports power flow in both directions, acting as a buck converter during charging and a boost converter during discharging. This flexibility makes it ideal for applications in electric vehicles, hybrid systems, and solar PV systems.

### Proposed Bidirectional Converter-
![image_8](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/35c382d4-1718-4099-b058-b48b515973f2)



## Matlab Simulink Diagram
![image_9](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/8e4f4d7c-90f1-42bc-8feb-ade80b502b61)

Read paper for more details.
[https://www.springerprofessional.de/en/bidirectional-dc-dc-converter-as-a-better-alternative-for-chargi/23508976].

### Simulink Parameters-

![image_11](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/23cd6195-18aa-4592-862d-d2c51aa64d2d)

## Simulation and Results
The system is modeled and simulated using Simulink, showing efficient battery management and power delivery to loads. The simulation includes:

### Change in irradiance level with respect to time
![image12](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/22018a6a-fc3a-47ca-9b20-14b935337e22)


### Power output from solar PV module
![image_13](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/48048ce7-96a0-4319-a356-290a1cdf74b7)


### Battery state of charge ( SOC in %)
![image_14](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/69bc0b91-f35a-45a3-baf8-9245df5317e0)

### Battery current and reference current generated by the controller
![image_15](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/f1d846aa-d218-4af8-81db-e46002a68843)


### Battery voltage
![image_16](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/77d4fa71-ee6e-4720-b8cb-311494313467)

### DC Bus Voltage
![iamge_17](https://github.com/shivam221997/Bidirectional-Converter-with-MPPT-Controlled-Solar-PV-System/assets/156662255/079e6dab-a1c8-4c3a-aa5f-d7f1d45b3e9e)


## Contributors
Prashant (prashant27@jssaten.ac.in)

Shivam Kumar (shivamalig22089@gmail.com)

Amurt Prakash (amurtprakash@gmail.com)

Kaushik Dubey (kaushikjss10@gmail.com)

Prashant Kumar Pandey (pp038552@gmail.com)
## References
Authors' original research paper: [https://www.springerprofessional.de/en/bidirectional-dc-dc-converter-as-a-better-alternative-for-chargi/23508976].

National Institute of Solar Energy, India.

Various MPPT and power electronics references cited within the paper.
