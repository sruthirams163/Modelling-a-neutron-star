# 🌌 Modeling of a Neutron Star using Numerical Methods

This project was created as part of the **Udemy Certification Course** under **Spartificial Innovations Pvt. Ltd.**  
It demonstrates the use of **numerical methods** to model a **neutron star**, one of the densest forms of matter in the universe.  
The goal is to explore how **numerical computation** and **physics** intertwine to simulate such extreme astronomical objects.

---

##  Overview

A **neutron star** forms when a massive star exhausts its nuclear fuel and collapses under its own gravity, following a **supernova explosion**.  
The pressure becomes so intense that protons and electrons merge to form neutrons, resulting in an incredibly dense and compact stellar object.

This project models a neutron star using a **computational approach**, solving key **astrophysical equations numerically** to estimate its **mass**, **radius**, and **pressure profile**.

---

##  Theoretical Background

The structure of a neutron star can be described using two main physical models:

### 1. **Hydrostatic Equilibrium Equation (Classical Model)**
- Balances the **gravitational force** pulling inward and the **pressure** pushing outward.  
- Provides an approximate structure of the star using **classical physics**.  

### 2. **TOV Equation (Relativistic Model)**
- The **Tolman–Oppenheimer–Volkoff (TOV)** equation extends hydrostatic equilibrium by including **General Relativity**.  
- Provides a much more **accurate model** for neutron stars where **relativistic effects** are dominant.

To simplify the calculations, the **Planck system of units** is used, where:
c = ħ = G = 1

This normalization helps make the equations dimensionless and easier to compute numerically.

##  Computational Approach

This project applies **numerical computation** to solve complex **stellar equations** that cannot be solved analytically.

###  1. Numerical Simulations
#### a) **Runge–Kutta 4th Order Method (RK4)**
Used to solve the coupled **ordinary differential equations (ODEs)** for the **mass** and **pressure** gradients within the neutron star.

#### b) **Newton–Raphson Method**
Used to iteratively calculate the **initial number density of neutrons** inside the star, ensuring the equations converge accurately.

---

###  2. Coding and Visualization
The project is implemented using **Python**, a powerful scientific computing language.  

**Libraries Used:**
- **NumPy** → For array-based mathematical and numerical operations  
- **Matplotlib** → For visualizing **mass** and **pressure** profiles of the modeled neutron star  

Simulation parameters are fine-tuned to model both **classical** and **relativistic** neutron star structures, enabling a comparison between their radii and total masses.

## Results and Observations
**Classical Model**: Produces unrealistic neutron star properties, highlighting its limitations at extreme densities.

**Relativistic Model**: Provides accurate results aligning with real astrophysical expectations.

The results confirm that relativistic modeling is essential for neutron star analysis.
