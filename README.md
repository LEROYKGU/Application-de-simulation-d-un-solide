# Mechanical Solid Simulation Interface

## Overview
This project is a graphical simulation interface developed for modeling and analyzing the mechanical behavior of solids subjected to elastic loading conditions.

The application simulates mechanical stresses and deformations under:
- Traction
- Compression
- Shear loading

The software provides an educational and engineering-oriented environment for understanding the behavior of materials and solid mechanics concepts within the elastic domain.

---

# Project Objectives

The main objectives of this project are:

- Develop an interactive mechanical simulation interface
- Model elastic deformation behavior of solids
- Simulate mechanical loading conditions
- Visualize simulation workflows
- Create an educational engineering tool for solid mechanics

---

# Features

## Geometry Definition
Users can define or configure the geometry of the simulated solid.

Possible parameters:
- Dimensions
- Shape configuration
- Structural properties

---

## Material Selection
The application allows users to specify material properties such as:
- Young’s modulus
- Poisson’s ratio
- Elastic properties

---

## Mechanical Loading
The interface supports several loading conditions:
- Traction
- Compression
- Shear stress

Users can apply forces expressed in Newtons.

---

## Boundary Conditions
The software includes configuration of:
- Fixed supports
- Constraints
- Mechanical boundary conditions

---

## Meshing
The application integrates a meshing stage required for numerical simulation workflows.

Main objective:
- Discretization of the solid domain

---

## Simulation Execution
The system executes simulations and provides numerical or graphical outputs related to the mechanical response of the solid.

---

# Graphical User Interface

The project includes:

## Welcome Interface
A startup interface introducing the simulation environment and application objectives.

### Main actions:
- Launch application
- Exit application

---

## Main Simulation Interface
The main interface contains:
- Geometry configuration
- Material selection
- Load application
- Boundary condition management
- Meshing tools
- Simulation controls

The interface was designed to provide:
- Simplicity
- Educational accessibility
- Structured engineering workflow

---

# Project Structure

```bash
Mechanical-Solid-Simulation/
│
├── Traction-Compression.ipynb     # Main simulation notebook
├── Interface.png                  # Main simulation interface screenshot
├── Fond_d'acceuil.png             # Welcome interface screenshot
├── README.md                      # Project description
└── rapports.pdf                   # Project documentation
```
---
# Technologies Used
## Programming Language
  Python
## Environment
  Jupyter Notebook
## Possible Libraries
* Tkinter (GUI)
* NumPy
* Matplotlib
* Scientific computing libraries
---
# Simulation Workflow

The simulation process follows these steps:

1. Define geometry
2. Select material properties
3. Apply mechanical loads
4. Define boundary conditions
5. Generate mesh
6. Run simulation
7. Analyze results
---
# Engineering Concepts Covered

This project demonstrates concepts related to:

* Solid Mechanics
* Elasticity Theory
* Mechanical Stress Analysis
* Finite Element Method (FEM)
* Structural Simulation
* Numerical Modeling
---
# Educational Purpose

This application was developed as an educational engineering project to:

* Facilitate understanding of mechanical simulations
* Visualize elastic behavior of solids
* Introduce simulation workflows
* Practice scientific programming and GUI development
---
# Installation 
Clone the repository:
```bash
git clone https://github.com/LEROYKGU/your-repository-name.git
```
Navigate to the project directory:
```bash
cd your-repository-name
```
Install required dependencies:
```bash
pip install numpy matplotlib
```
----
# Usage

Launch Jupyter Notebook:
```bash
jupyter notebook
```
Open:
```bash
Traction-Compression.ipynb
```
Run the notebook cells sequentially to start the simulation interface.
---
# Screenshots
## Welcome Interface

The startup interface introduces the application and simulation objectives.
---
# Main Simulation Interface

The main interface provides access to:

* Geometry
* Material properties
* Loading conditions
* Boundary conditions
* Meshing
* Simulation execution
---
# Learning Outcomes

This project demonstrates practical skills in:

+ Scientific computing
+ Engineering simulation
+ GUI development
+ Numerical modeling
+ Python application development
+ Mechanical system analysis
---
# Future Improvements

Potential future enhancements include:

- Full finite element implementation
- 3D visualization
- Real-time stress visualization
- Advanced meshing algorithms
- Material nonlinearity
- Dynamic simulations
- Exportable simulation reports
---
# Author

KGU
Mechanical Simulation Enthusiast | Scientific Computing Practitioner | AI & Engineering Explorer

GitHub: https://github.com/LEROYKGU

# License

This project is licensed under the MIT License.
