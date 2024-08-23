# Phyphox Experiment: Detecting Exoplanets using the Transit Method

This repository contains the materials and instructions for conducting an experiment to detect exoplanets using the transit method. The experiment leverages the Phyphox app on a smartphone to simulate the detection of exoplanets by observing the dimming of a star as a planet transits in front of it.

## Overview

The transit method is one of the most successful techniques for discovering exoplanets. In this experiment, we simulate this process using a light sensor connected to a smartphone running the Phyphox app. By monitoring changes in light intensity, participants can simulate the detection of an exoplanet as it passes in front of a star.

## Project Contents

- **Phyphox Experiment File**: A `.phyphox` file configured to measure and record light intensity over time.
- **Arduino Code**: (Optional) Code for controlling an LED setup to simulate the star and the planet transit.
- **Experiment Instructions**: Step-by-step guide on setting up and conducting the experiment.
- **Data Analysis Guide**: Instructions on how to analyze the collected data to identify potential transits.

## Getting Started

### Prerequisites

- **Phyphox App**: Download and install the Phyphox app on your smartphone. It is available on both Android and iOS platforms.
- **Light Sensor**: A light sensor compatible with Phyphox (e.g., the phone’s ambient light sensor).
- **Experiment Setup**: An LED or similar light source to act as the "star" and an object to simulate the "planet."

### Setting Up the Experiment

1. **Download the Phyphox File**: 
   - Download the `transit_method_experiment.phyphox` file from this repository.
   - Import the file into the Phyphox app on your smartphone.

2. **Set Up the Light Source**:
   - Position the LED to represent a star. Ensure it provides a steady light source.
   - Place the light sensor (your smartphone) at a fixed distance from the LED.

3. **Simulate the Transit**:
   - Slowly move an object (representing a planet) between the light source and the sensor. 
   - Phyphox will record the changes in light intensity as the object passes in front of the LED.

### Running the Experiment

1. **Start the Experiment**:
   - Open the imported experiment in the Phyphox app.
   - Begin recording data as you simulate the transit with your object.

2. **Analyze the Data**:
   - After the experiment, review the recorded light intensity data.
   - Look for dips in the light curve that correspond to the transit of the object.

3. **Interpretation**:
   - Compare the detected dips with the expected behavior during a real exoplanet transit.
   - Discuss the limitations and accuracy of this method in a classroom or learning environment.

## Further Reading

For a detailed explanation of the experiment, the scientific principles behind the transit method, and how smartphones can be used in educational settings to simulate exoplanet detection, refer to the [original document](https://www.mint-digital.de/fileadmin/user_upload/Spicker_und_Kuepper-Die_Transitmethode_-_Einsatz_von_Smartphones_in_Experimenten_zur_Suche_nach_Exoplaneten.pdf).

## Contributing

Contributions to improve this experiment or expand it with additional features (e.g., more detailed data analysis) are welcome. Please fork this repository and submit a pull request.

## License

This project is licensed under the GPL-3.0 license. See the `LICENSE` file for more information.
