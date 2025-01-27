# Propulsion-Model
# Electric Driveline Model: Fuel Cell and Battery Integration

## Overview
This repository contains a high-fidelity Simulink model of an electric driveline that integrates a Proton Exchange Membrane (PEM) fuel cell and a lithium-ion battery pack. The model offers high design flexibility, low computational demand, and detailed representation of system dynamics. It serves as a powerful tool for research and development in sustainable transportation technologies.
The model integrates all components of the driveline using a high level of detail, relying on real physical and analytical equations to accurately describe the behaviour of each component. This approach ensures precision and reliability in the representation of system dynamics.
The model offers the opportunity to simulates the electric propulsion under different conditions. It is characterized by great parameter handling, allowing the implementation of systems with a broad range of power ratings.
Furthermore, a modular architecture was adopted during the model's design, facilitating the customization and incorporation of supplementary elements
The model is validated against a Simscape-based equivalent, demonstrating equivalent performance with significantly reduced computational time. (CITARE PAPER)

The content of folder '*****.zip' is protected by a passaword that can be requested and will be provided via email: ale.brusasco@gmail.com

---

## Features
- **Hybrid Electric Driveline**: Combines PEM fuel cell and lithium-ion battery technologies.
- **Real Equations**: Incorporates analytical and physical equations to model the behaviour of each component.
- **Modular Architecture**: Enables customization and integration of additional components.
- **High Fidelity**: Includes detailed modeling of fuel cell thermodynamics, electrochemistry, and energy management.
- **Validated Performance**: Tested using real-world load cycles with comparative results. CITA PAPER
- **Open Source with Restrictions**: Accessible for research and educational purposes under specified license terms.
  
---

## Repository Contents
The file ‘******.zip’ is organized as follows:
- **Simulink Model**: ‘Propulsion_model.slx’ contains the Simulink implementation of the electric driveline.
- **MATLAB Script**: ‘Propulsion_script.m’ contains the setting parameters and running code for the simulations.
- **Documentation**: ‘Report.text’ fearures a detailed description of the model components. 
- **Example Load Cycles**: ‘Load_cycle_example.m’ contains an example of drive cycle. The data are stored in the ‘Load Cycle Example’ folder.
- **Parameters initialization**: The folder ‘Callback Function’ comprises the supporting functions for defining essential parameters of the model.
- **Usage Guide**: ‘User_guide.text’ includes all the instructions for setting up and running simulations.
- **Simulink icon**: ‘Figure’ folder contains the icons of the Simulink components.
- **License**: ‘License.text’ defines usage terms.
- **README** file.
  
---

## Simulink Model Components
- **Fuel Cell Stack**: PEM fuel cell with detailed auxiliary system modeling (H2 tank, air compressor, humidifiers, cooling system and H2 recirculation).
-**Battery Pack**: Li-ion battery modelling using an equivalent circuit model.
-**Electric Motor**: Brushed DC motor equation with cascade control.
-**Power Conditioning**: DC-DC converters for voltage regulation. FC boost converter and motor Buck-Boost converter. Electric model of DC Bus.
-**Energy Management System (EMS)**: State-based control logic for balancing power between fuel cell and battery.
  
--

## Requirements
- MATLAB and Simulink (R2024a or later recommended)
-Access to the password for protected files (request it via email: ale.brusasco@gmail.com)

---

## Installation
1. Clone this repository:
   
  git clone https://github.com/your-username/electric-driveline-fuelcell-battery.git CAMBIA NOME

 3. Extract the file '*****.zip'.
    
 4. Enter the provided password to open the selected files.

 Refer to the 'User_guide' file for further information.
 
--

## License
This project is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) ** License.
See the ‘License.text’ file for further details.

The files are protected by a password that can be requested to the owner and will be provided. The password request via email at: **ale.brusasco@gmail.com**. 

--

## Acknowledgments
This project is based on the research paper: %%NOME PAPER%% Author(s): Alessandro Brusasco, Mauro Bonfanti, Francesco Balestrieri, Giulio Gennaro, Stefano Mauro.
Department of Mechanical and Aerospace Engineering, Politecnico di Torino, Italy.

--

## Contact
For questions or feedback, please contact:
**ale.brusasco@gmail.com**
