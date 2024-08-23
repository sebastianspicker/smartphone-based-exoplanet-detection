# Smartphone-Based Exoplanet Detection Using the Transit Method

This repository provides a collection of Phyphox experiment files designed to simulate the detection of exoplanets using the transit method. By leveraging your smartphone's sensor, you can observe changes in light intensity, mimicking how a planet passing in front of a star causes a dip in brightness.

## Overview

The transit method is a proven technique for discovering exoplanets. This project allows you to replicate this method by using your smartphone's sensors in combination with the Phyphox app. Depending on your setup and available equipment, you can use different devices to measure light intensity and visualize the data in real-time.

## Project Contents

This repository includes multiple `.phyphox` files tailored for various levels of experiment complexity and different measurement devices:

- **Basic Experiments**:
  - `transitmethode_basic.phyphox`: For simple experiments using the smartphone's built-in light sensor.
  - `transitmethode-multimeter_basic.phyphox`: Use a multimeter to measure voltage changes corresponding to light intensity.
  - `transitmethode-sensortag_basic.phyphox`: For setups using a SensorTag to measure light intensity.
  - `transitmethode_arduino-basic.phyphox`: Connect your Arduino to simulate the transit and measure light intensity.

- **Expert Experiments**:
  - `transitmethode_expert.phyphox`: Advanced experiment using the smartphone's sensor with more detailed analysis options.
  - `transitmethode-multimeter_expert.phyphox`: Advanced setup using a multimeter for high-precision measurements.
  - `transitmethode-sensortag_expert.phyphox`: Advanced experiment using a SensorTag for detailed light intensity measurements.
  - `transitmethode_arduino-expert.phyphox`: An Arduino-based setup for more complex simulations and data analysis.

## Getting Started

### Prerequisites

- **Phyphox App**: Ensure the Phyphox app is installed on your smartphone. Available on Android and iOS.
- **Measurement Device**: Depending on your selected experiment file, you will need:
  - A smartphone with a light sensor.
  - A multimeter for voltage measurements.
  - A SensorTag for environmental sensing.
  - An Arduino setup for custom light simulations.

### Setting Up the Experiment

1. **Download the Appropriate Phyphox File**:
   - Choose the `.phyphox` file that matches your experiment level (basic or expert) and the measurement device you are using.

2. **Import the File into Phyphox**:
   - Open the Phyphox app on your smartphone and import the selected experiment file.

3. **Prepare Your Measurement Setup**:
   - If using an Arduino, program it to simulate the transit event with an LED.
   - If using a multimeter or SensorTag, ensure they are correctly connected and calibrated.

4. **Conduct the Experiment**:
   - Start the experiment in the Phyphox app and begin recording data as you simulate the transit by moving an object between the light source and sensor.

### Data Analysis

- **Visualize the Data**:
  - Phyphox will display the recorded light intensity over time. Look for characteristic dips in the light curve that indicate a transit event.
  
- **Compare Basic vs. Expert Experiments**:
  - The expert-level experiments offer more detailed data analysis and visualization options, allowing for a deeper understanding of the transit method.

## Further Information

For more details on how to set up these experiments and the scientific principles behind the transit method, refer to the [original guide](https://www.mint-digital.de/fileadmin/user_upload/Spicker_und_Kuepper-Die_Transitmethode_-_Einsatz_von_Smartphones_in_Experimenten_zur_Suche_nach_Exoplaneten.pdf). This document provides comprehensive instructions and theoretical background for educational purposes.

## Contributing

Contributions to enhance these experiments or expand them with additional features are welcome. Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
