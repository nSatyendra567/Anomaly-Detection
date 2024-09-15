# Efficient Data Stream Anomaly Detection

## Project Overview
This project focuses on detecting anomalies in a real-time data stream using Python. The data stream simulates continuous sequences of floating-point numbers, representing metrics like financial transactions or system performance indicators.

## Key Objectives
- **Algorithm Selection**: Utilized the Z-Score method for anomaly detection, which adapts to the dynamic nature of the data stream.
- **Data Stream Simulation**: Created a simulated data stream with patterns, seasonal variations, and random noise to mimic real-world scenarios.
- **Anomaly Detection**: Implemented real-time anomaly detection that accurately flags unusual values based on statistical thresholds.
- **Optimization**: Optimized for both speed and resource efficiency to handle continuous data streams.
- **Visualization**: Provided real-time graphical representation of the data stream, highlighting detected anomalies for better interpretability.

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create and activate a virtual environment**:
    - On Windows:
      ```bash
      python -m venv venv
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      python3 -m venv venv
      source venv/bin/activate
      ```

3. **Install required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the project**:
    ```bash
    python main.py
    ```

## Project Dependencies
- `numpy`: For efficient numerical computations.
- `matplotlib`: For real-time data visualization.

## How It Works
The script:
1. Simulates a continuous data stream with regular patterns, random noise, and occasional spikes (representing anomalies).
2. Applies the Z-Score method to detect anomalies by calculating the deviation from the mean within a moving window.
3. Updates a real-time graph that displays both the data stream and detected anomalies.

