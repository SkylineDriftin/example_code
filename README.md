# Code Examples

A collection of source code modules and scripts from previous engineering and research projects, focusing on aerospace dynamics and orbital mechanics.

---

## Project Overview

### 1. Rocket Thrust Vector Control (TVC) Drivers
**File:** `servo_drivers.cpp`  
**Language:** C++  
**Context:** Developed for a rocket team project to control a 2-axis gimbaled toolhead.  
* Implements a `Gimbal` class to coordinate Y and Z axis servo movements.
* Manages pulse-width modulation (PWM) mapping to translate orientation angles from radians to microsecond signals.
* Accounts for mechanical variables including axis offsets and gear ratios.

### 2. Asteroid Orbital Determination
**File:** `OD_Code_Clean.ipynb`  
**Language:** Python (Jupyter Notebook)  
**Context:** Research conducted at the Summer Science Program (SSP) utilizing university telescope observations.  
* Implements the **Method of Gauss** to determine the orbital elements of observed asteroids.
* Extracts and processes position and velocity vectors from JPL ephemeris data.
* Calculates fundamental orbital elements including semi-major axis, eccentricity, inclination, and longitude of ascending node.

### 3. Rigid Body Rocket Simulation
**File:** `rocket.py`  
**Language:** Python  
**Context:** A numerical integration framework developed for rocket team flight simulations.  
* Features a 6-DOF (Degrees of Freedom) physics model for linear and angular motion.
* Utilizes quaternions for orientation tracking to avoid gimbal lock and ensure numerical stability.
* Modular architecture allows for the application of various force and torque components (thrust, drag, gravity) during each simulation step.

---

## Technical Skills Demonstrated
* **Languages:** C++, Python (NumPy), also familiar with Java
* **Mathematics:** Numerical integration, Vector calculus, Orbital mechanics, Quaternions
* **Skills:** Embedded systems, hardware interfacing, scientific computing, visualizations (matplotlib)
