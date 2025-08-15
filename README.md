# Thermal_analysis_on_a_hot_pot
##  Overview
This project demonstrates both **steady-state** and **transient** thermal analyses of a teapot made from two different materials: **porcelain** and **steel**.  
The goal is to study how material properties affect temperature distribution and heat loss through **conduction, convection, and radiation**.

##  Objectives
- Perform **steady-state** thermal analysis for porcelain and steel teapots.
- Perform **transient** thermal analysis to observe cooling over time.
- Compare thermal performance between materials.

##  Modeling Procedure
1. **Setup**
   - Open **ANSYS Workbench**.
   - Create a **Steady-State Thermal** system.
2. **Material Properties**
   - Define and assign properties for porcelain and steel.
3. **Geometry**
   - Import the teapot model.
   - Suppress half of the geometry for symmetry to reduce computational cost.
4. **Thermal Contacts**
   - Use the default thermal contact between lid and main body.
5. **Boundary Conditions**
   - Tea inside teapot: 100 °C.
   - Apply convection, temperature, and radiation boundary conditions to external surfaces.
6. **Meshing**
   - Apply linear mesh for accuracy.
7. **Solution**
   - Solve for temperature distribution (steady state).
   - Plot heat flux vectors to visualize conduction, convection, and radiation.
8. **Material Change**
   - Repeat the above steps for steel material.
9. **Transient Analysis**
   - Change analysis type to transient.
   - Simulate 100 s of cooling from 100 °C to ambient 22 °C.
   - Compare porcelain and steel results.

## Results
- **Temperature Distribution (Steady-State)**
  - Visual representation of temperature gradients across the teapot.
- **Heat Flux Plot**
  - Vector visualization showing heat flow through the teapot body and lid.
- **Transient Cooling Curves**
  - Time-dependent temperature changes for both materials.

## 📂 Repository Structure
