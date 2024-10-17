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
1. Clone the repository:
    bash
    git clone https://github.com/antara02/Efficient-Data-Stream-Anomaly-Detection.git
    cd Efficient-Data-Stream-Anomaly-Detection
    

2. Install required packages:
    bash
    pip install numpy matplotlib rrcf
    
## Algorithm Details
The RCF algorithm is ideal for real-time anomaly detection due to its scalability and adaptability:
- *Random Cut Trees (RCT)*: A set of RCTs are used to form a forest, where each tree learns patterns in the data stream and computes codisplacement scores.
- *Codisplacement Score*: Measures the displacement of data points within the trees to identify anomalies based on deviations from typical patterns.
- *Threshold-based Detection*: A score threshold of 2 times the previous score is used to flag anomalies.

## Results
The project successfully detects anomalies in a simulated data stream, with anomalies visualized in red for easy identification. The RCF algorithm demonstrates high accuracy and adaptability to data stream changes.
