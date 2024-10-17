# Efficient Data Stream Anomaly Detection

## Project Overview
The **Efficient Data Stream Anomaly Detection** project focuses on developing a Python-based solution for detecting anomalies in continuous data streams. This solution simulates real-time sequences of floating-point numbers, which can represent various metrics such as financial transactions or system metrics. The primary goal is to identify unusual patterns, such as exceptionally high values or deviations from the norm.

## Objectives
- **Algorithm Selection**: Implement a suitable algorithm for anomaly detection capable of adapting to concept drift and seasonal variations.
- **Data Stream Simulation**: Create a function to emulate a data stream, incorporating regular patterns, seasonal elements, and random noise.
- **Anomaly Detection**: Develop a real-time mechanism to accurately flag anomalies as data is streamed.
- **Optimization**: Ensure the algorithm is optimized for speed and efficiency.
- **Visualization**: Create a straightforward real-time visualization tool to display both the data stream and any detected anomalies.

## Key Features
- **Data Generation**: A module to generate synthetic data streams with defined patterns, seasonal variations, and random noise.
- **Anomaly Injection**: Capability to introduce anomalies into the data stream for testing and validation of the detection mechanism.
- **Random Cut Tree (RCT) Algorithm**: Utilization of RCT for efficient anomaly detection in data streams, maintaining a balance between accuracy and performance.
- **Real-Time Visualization**: Dynamic visualization of the data stream and anomaly scores, allowing for easy identification of detected anomalies.

## Installation
To run the project, ensure you have Python 3.x installed along with the necessary libraries. You can install the required packages using:
