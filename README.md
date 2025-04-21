# Orbital Mechanics and Magnetic Field Analysis

This repository contains a MATLAB implementation to model the orbital mechanics of a satellite, including the calculation of orbital parameters and position vectors. It also incorporates magnetic field analysis using two methods (`igrfmagm` and `wrldmagm`) to compute the Earth's magnetic field in both ECI and ECEF coordinates.

## Features

- **Orbital Mechanics**: The code models the satellite's orbit with parameters such as inclination, RAAN, argument of perigee, and true anomaly.
- **Position Vectors**: Calculates the satellite's position in 3D space, with the ability to visualize the orbital path in multiple planes (3D, X-Y, X-Z, Y-Z).
- **Coordinate Transformations**: Converts the satellite's position from the ECI (Earth-Centered Inertial) frame to the ECEF (Earth-Centered Earth-Fixed) frame.
- **Magnetic Field Analysis**: Computes the Earth's magnetic field using the `igrfmagm` and `wrldmagm` functions, comparing the results in both ECI and ECEF frames.
- **Visualization**: Provides various plots, including altitude vs time, longitude vs latitude, and magnetic field components over time.

## Prerequisites

- MATLAB (R2020a or later recommended)
- Basic understanding of orbital mechanics and magnetic field modeling.
- `igrfmagm` and `wrldmagm` functions from the IGRF and WMM models, respectively.

## Usage

1. Clone or download this repository.
2. Open the `orbit_and_magnetic_field_analysis.mlx` file in MATLAB.
3. Run the script to simulate the satellite's orbit and magnetic field data.

The code will produce:
- A 3D plot of the satellite’s orbit around Earth.
- X-Y, X-Z, and Y-Z plane projections of the orbit.
- Plots of altitude vs time and longitude vs latitude.
- Magnetic field component plots in both ECI and ECEF frames using `igrfmagm` and `wrldmagm`.
- A comparison of the magnetic field results from the two methods.

## How to Contribute

Feel free to fork the repository and submit pull requests with improvements or bug fixes. Ensure that you follow MATLAB code standards and include comments explaining any changes made.



