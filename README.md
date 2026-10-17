# Deposition Welding Simulation Using MSC Simufact Welding 2024

## 📌 Project Overview

This research project focuses on the numerical simulation of the deposition welding process to study its thermal and mechanical behaviour during multilayer material deposition. The simulation was carried out using **MSC Simufact Welding 2024**, which enables the analysis of temperature distribution, welding-induced stresses, and deformation associated with the deposition process.

Deposition welding involves melting and depositing material onto a substrate to build up a new layer or restore an existing component. During this process, localized heating and subsequent cooling generate temperature gradients, repeated thermal cycles, residual stresses, and potential distortion.

The project investigates these effects using a finite element simulation model consisting of a base substrate and two deposited layers of IN-718 nickel-based alloy.

## 🎯 Project Objectives

- Simulate the deposition welding process using MSC Simufact Welding 2024.
- Study the thermal behaviour and temperature distribution during multilayer deposition.
- Analyse the equivalent stress generated due to localized heating and cooling.
- Understand the effects of heat-source movement and repeated thermal cycles.
- Investigate how non-uniform heating and cooling contribute to residual stress and distortion.
- Understand the role of simulation in reducing physical trials and improving welding process development.

## 🛠️ Tools and Technologies

- **MSC Simufact Welding 2024:** Numerical simulation of the welding and deposition process.
- **Finite Element Analysis (FEA):** Numerical evaluation of thermal and mechanical behaviour.
- **3D Geometry Modelling:** Representation of the substrate and deposited layers.
- **Meshing:** Discretization of the model into finite elements.
- **Thermal Analysis:** Study of heat transfer and temperature distribution.
- **Structural Analysis:** Evaluation of equivalent stress and deformation.

## ⚙️ Simulation Model and Input Parameters

The simulation model was configured using the following parameters documented in the project presentation.

| Parameter | Description |
|---|---|
| Base substrate dimensions | 100 × 100 × 10 mm |
| Deposition bead area | 30 × 30 mm |
| Number of deposited layers | 2 |
| Deposition material | IN-718 nickel-based alloy |
| Simulation software | MSC Simufact Welding 2024 |
| Analysis type | Thermal and mechanical simulation |

The welding process parameters include current, voltage, welding speed, heat-source efficiency, deposition rate, and layer height. These parameters are used to represent the deposition process within the numerical model.

## 🔬 Methodology

### 1. Geometry Creation

The substrate geometry was created or imported into the simulation environment using the specified dimensions of 100 × 100 × 10 mm. The deposition region was defined to represent the area where the material would be added.

### 2. Material Definition

IN-718, a nickel-based alloy, was selected as the deposition material. The relevant material properties are required to represent its thermal and mechanical response during heating, deposition, and cooling.

### 3. Meshing

The model was divided into small finite elements to enable numerical computation. Particular attention was given to the deposition region, where high temperature gradients and localized thermal effects can occur.

A finer mesh in critical regions can improve the representation of local behaviour, although excessive mesh refinement increases computational cost.

### 4. Heat-Source Definition

A heat source was defined to represent the energy input during the deposition process. The applied heat input governs the local temperature rise and influences the formation of the molten region.

### 5. Deposition Path and Process Parameters

The deposition path was defined to represent the movement of the heat source along the intended deposition region. Process parameters, including current, voltage, welding speed, heat-source efficiency, deposition rate, and layer height, were considered in setting up the simulation.

### 6. Thermal Boundary Conditions

Thermal boundary conditions were specified to represent the model's initial and surrounding thermal environment. These include initial temperature, ambient temperature, convection, radiation, and thermal contact, as applicable to the model.

### 7. Mechanical Constraints

Mechanical constraints and restraints were defined to represent the restrictions imposed on the substrate during the simulated process. These conditions influence the predicted deformation and stress distribution.

### 8. Simulation and Post-Processing

After defining the geometry, material, mesh, heat source, deposition path, process parameters, and boundary conditions, the simulation was run in MSC Simufact Welding 2024.

The outputs were examined to understand temperature distribution and equivalent stress, along with the thermal and mechanical effects associated with multilayer deposition.

## 📊 Simulation Results

The project presentation reports the following simulation results:

| Simulation Output | Reported Result | Significance |
|---|---:|---|
| Maximum temperature | 1336.11 °C | Indicates the peak thermal condition reported by the simulation |
| Maximum equivalent stress | 1017.40 MPa | Indicates the maximum equivalent stress reported by the simulation |

### 1. Thermal Analysis and Temperature Distribution

The thermal analysis examines how temperature changes as the heat source moves along the deposition path.

The project investigates the following thermal phenomena:

- Localized temperature rise near the heat source.
- Heat conduction from the deposition region into the surrounding substrate.
- Cooling of previously heated regions as the heat source moves forward.
- Reheating of previously deposited material during subsequent layer deposition.
- Repeated heating and cooling cycles during multilayer deposition.

The reported maximum temperature is 1336.11 °C. Temperature contours and temperature-versus-time data can be used to examine the thermal history of the deposited material and substrate.

### 2. Equivalent Stress Analysis

The mechanical analysis evaluates the equivalent stress generated during the deposition process.

The reported maximum equivalent stress is 1017.40 MPa. Welding-induced stress develops because the material undergoes localized heating, thermal expansion, cooling, and contraction while being constrained by the surrounding material and boundary conditions.

The equivalent stress result helps identify regions requiring further investigation. Its implications for material performance depend on the relevant temperature-dependent material properties, simulation assumptions, and applicable failure criteria.

### 3. Residual Stress and Distortion

Non-uniform heating and cooling can produce residual stresses and dimensional changes in welded or deposited components. Mechanical restraints and repeated thermal cycles may further influence these effects.

The project considers residual stress and distortion as important aspects of the thermal-mechanical behaviour of deposition welding. Quantitative conclusions about maximum residual stress or deformation should be reported only when confirmed by the corresponding simulation outputs.

## 💡 Key Learnings

- Understanding the fundamental sequence of deposition welding: heating, melting, deposition, and solidification.
- Learning the simulation workflow in MSC Simufact Welding 2024.
- Understanding the importance of geometry, material properties, meshing, and boundary conditions.
- Investigating temperature distribution and thermal cycles during multilayer deposition.
- Understanding the relationship between non-uniform thermal behaviour, equivalent stress, and potential distortion.
- Applying finite element simulation to investigate welding processes before physical experimentation.

## 🏭 Engineering Applications

Deposition welding simulation is relevant to several manufacturing and repair applications:

- Repair and restoration of worn mechanical components.
- Surface cladding and material addition.
- Welding process development and optimization.
- Multilayer deposition and additive manufacturing.
- Thermal-mechanical assessment of welded structures.
- Reduction of trial-and-error during manufacturing process development.

## 🔮 Future Scope

The project presentation identifies the following opportunities for further investigation:

- Experimental validation of the simulation results.
- Optimization of current, voltage, and welding speed.
- Investigation of additional deposition layers.
- Comparison of different materials and heat-source models.
- Study of distortion control and microstructure prediction.
- Extension of the simulation methodology toward additive manufacturing.

## 📝 Conclusion

This project applies MSC Simufact Welding 2024 to study the thermal and mechanical behaviour of multilayer deposition welding using an IN-718 nickel-based alloy. The simulation model represents a 100 × 100 × 10 mm substrate with two deposited layers.

The reported maximum temperature of 1336.11 °C and maximum equivalent stress of 1017.40 MPa provide key outputs for investigating the process's thermal and mechanical response. The project demonstrates how numerical simulation can support the understanding of heat transfer, welding-induced stress, and potential distortion, providing a foundation for future process optimization and experimental validation.

## 👥 Project Team

- Gaurav Kumar
- Sharansh
- Akanksha Sharma

**Supervisor:** Dr. Yogesh Kumar

**Department:** Mechanical Engineering, National Institute of Technology Patna

**Project:** Research Project I (ME071601)

**Date:** September 2026
