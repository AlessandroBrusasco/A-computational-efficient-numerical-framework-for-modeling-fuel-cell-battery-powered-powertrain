# A computational efficient numerical framework for modeling fuel cell-battery powered powertrain

## Overview
This repository contains a high-fidelity Simulink model of an electric driveline that integrates a Proton Exchange Membrane (PEM) fuel cell and a lithium-ion battery pack. The model offers high design flexibility, low computational demand, and detailed representation of system dynamics. It serves as a powerful tool for research and development in sustainable transportation technologies.
The model integrates all components of the driveline using a high level of detail, relying on real physical and analytical equations to accurately describe the behaviour of each component. This approach ensures precision and reliability in the representation of system dynamics.
The model offers the opportunity to simulates the electric propulsion under different conditions. It is characterized by great parameter handling, allowing the implementation of systems with a broad range of power ratings.
Furthermore, a modular architecture was adopted during the model's design, facilitating the customization and incorporation of supplementary elements
The model is validated against a Simscape-based equivalent model exploiting real load cyces, demonstrating equivalent performances with significantly reduced computational time[1].

The folder 'Fuel_cell-battery_powertrain.zip' contains all the files needed.

The author of the repository are:
- Alessandro Brusasco
  
  alessandro.brusasco@polito.it
  
  ale.brusasco@gmail.com
  
  ORCID: https://orcid.org/0009-0006-5942-6024

- Mauro Bonfanti
  
  mauro.bonfanti@polito.it
  
  mauro.bonfanti.92@gmail.com
  
  ORCID: https://orcid.org/0000-0001-7729-6936

  
---

## Features
- **Hybrid Electric Driveline**: Combines PEM fuel cell and lithium-ion battery technologies.
- **Real Equations**: Incorporates analytical and physical equations to model the behaviour of each component.
- **Modular Architecture**: Enables customization and integration of additional components.
- **High Fidelity**: Includes detailed modeling of fuel cell thermodynamics, electrochemistry, and energy management.
- **Validated Performance**: Tested using real-world load cycles with comparative results[1].
- **Open Source with Restrictions**: Accessible for research and educational purposes under specified license terms.
  
---

## Repository Contents
The file ‘Fuel_cell-battery_powertrain.zip’ is organized as follows:
- **Simulink Model**: ‘Propulsion_model.slx’ contains the Simulink implementation of the electric driveline.
- **MATLAB Script**: ‘Propulsion_script.m’ contains the setting parameters and running code for the simulations.
- **Documentation**: ‘Report.text’ fearures a detailed description of the modeling methodology.
- **Usage Guide**: ‘User_guide.text’ includes all the instructions for setting up and running simulations.
- **Example Load Cycles**: ‘Load_cycle_example.m’ contains two examples of drive cycle. The data are stored in ‘Load Cycle Example’ folder.
- **Parameters initialization**: The folder ‘Callback Function’ comprises the supporting functions for defining essential parameters of the model.
- **Simulink icon**: ‘Figure’ folder contains the icons of the Simulink components.
- **License**: ‘License.text’ defines usage terms.
- **README** file.
  
---

## Simulink Model Components
- **Fuel Cell Stack**: PEM fuel cell with detailed auxiliary system modeling (H2 tank, air compressor, humidifiers, cooling system and H2 recirculation).
- **Battery Pack**: Li-ion battery modelling using an equivalent circuit model.
- **Electric Motor**: Brushed DC motor electromechanical equations with cascade control technique.
- **Power Conditioning**: DC-DC converters for voltage and current regulation: a FC boost converter and a motor Buck-Boost converter. Electric model of DC Bus.
- **Energy Management System (EMS)**: State-based control logic for balancing power between fuel cell and battery.
- **Control Functions**: Regulation of fuel cell and BoP operation, control of motor speed and torque, voltage and current regulation via DC-DC converters.
  
---

## Requirements
- MATLAB and Simulink (R2024a or later recommended)

---

## Installation
 1. Clone this repository:
   
  git clone https://github.com/AlessandroBrusasco/A-computational-efficient-numerical-framework-for-modeling-fuel-cell-battery-powered-powertrain.git

 2. Extract the file 'Fuel_cell-battery_powertrain.zip'.

 Refer to the 'User_guide' file for further information.
 
---

## License
This project is licensed under the **Creative Commons Attribution-ShareAlike (CC-BY-SA) 4.0** License.
See the ‘License.text’ file for further details.

---

## Acknowledgments
This project is based on the research paper: (to be published) Author(s): Alessandro Brusasco, Mauro Bonfanti, Francesco Balestrieri, Giulio Gennaro, Stefano Mauro.
Department of Mechanical and Aerospace Engineering, Politecnico di Torino, Italy.

---

## Contact
For questions or feedback, please contact:
**ale.brusasco@gmail.com**
