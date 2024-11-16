

# Runge-Kutta Method for Solving Differential Equations

This project demonstrates the implementation of numerical methods, including the **Runge-Kutta 4th Order Method (RK4)** and **Euler's Method**, for solving Ordinary Differential Equations (ODEs). The project specifically applies these methods to solving the **Lorenz system**, a classic example of a chaotic dynamical system.

---

## Features

- Implementation of **Euler's Method** and **Runge-Kutta 4th Order Method (RK4)** for solving ODEs.
- Solving the **Lorenz system** of equations:
  - A set of coupled nonlinear ODEs that exhibits chaotic behavior.
- Visualization of results:
  - 3D plots of the Lorenz attractor.
  - Time evolution plots of \(X(t)\), \(Y(t)\), and \(Z(t)\) with sensitivity to initial conditions.

---

## Project Structure

```
├── runge_kutta.py         # Implementation of Runge-Kutta and Euler's methods
├── lorenz_system.py       # Lorenz system definition and solver
├── plots.py               # Visualization scripts for results
├── README.md              # Project description
```

---

## Requirements

- Python 3.x
- Required libraries:
  - `numpy`
  - `matplotlib`

You can install the dependencies using:

```bash
pip install numpy matplotlib
```

---

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/Elotmanix/Runge-Kutta-method.git
   cd Runge-Kutta-method
   ```

2. Run the script to solve the Lorenz system and visualize results:

   ```bash
   python plots.py
   ```

3. Modify initial conditions or system parameters in the script to observe different behaviors.

---

## Results

### Lorenz Attractor (3D Trajectory)

The project visualizes the chaotic attractor in 3D space, showing how the system evolves over time.

### Time Evolution of Variables \(X(t)\), \(Y(t)\), \(Z(t)\)

Plots are generated to show the sensitivity of the Lorenz system to initial conditions.

---

## Lorenz System

The Lorenz system is defined by the following equations:

\[
\frac{dx}{dt} = \sigma (y - x)
\]
\[
\frac{dy}{dt} = x (\rho - z) - y
\]
\[
\frac{dz}{dt} = x y - \beta z
\]

The parameters \(\sigma\), \(\rho\), and \(\beta\) can be adjusted in the script.



## Author

**Hamza El Otmani**  
Engineering student specializing in Machine Learning, Physics-Informed Systems, and Data Science.  
