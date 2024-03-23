# particle-spray
# Particle Jet Simulation

This Python application simulates a particle jet under various conditions, visualized through 3D plotting, histograms of initial speeds, particle positions on a screen, and impact positions. It uses `matplotlib` for plotting, `numpy` for numerical calculations, and `Tkinter` for the graphical user interface (GUI), allowing users to adjust simulation parameters interactively.

## Features

- Simulate a particle jet with a customizable number of particles and temperature settings.
- Visualize the particle jet in 3D space.
- Display histograms of initial particle velocities.
- Visualize particle positions on a screen in 3D.
- Show the position of particle impacts on a screen.

## Prerequisites

Before running this application, ensure you have Python installed on your system along with the required libraries: `matplotlib`, `numpy`, and `Tkinter`.

## Installation

1. Ensure Python is installed on your system.
2. Install the required Python libraries using pip:

```bash
pip install matplotlib numpy
```
## How to Use

    - Once the application starts, adjust the simulation parameters using the provided sliders:
        - Nombre de particules: Set the number of particles in the jet.
        - Température en kelvin: Adjust the temperature of the particle system.
    - Use the checkboxes to toggle the visualization of the particle jet, histograms of initial speeds, particle positions on a screen, and impact positions.
    - Click on the Lancer button to start the simulation with the current parameters.
    - The Quitter button closes the application.

## Simulation Parameters

    - The simulation allows adjusting the number of particles and their temperature, affecting their speed distribution and trajectory.
    - The application visualizes the trajectory of particles through a predefined space and their interactions with a virtual screen placed in their path.
