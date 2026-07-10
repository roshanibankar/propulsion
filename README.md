

# Sensor Data Recorder & Analysis


## Overview
A high-performance pipeline designed to log, process, and analyze high-frequency sensor streams (IMU, GPS, Barometer, Thermocouples). This repository includes both the embedded data-logging scripts and a comprehensive Python-based desktop suite for post-flight/post-test data analysis, visualization, and anomaly detection.

## Features
* **High-Speed Logging:** Binary packet serialization to maximize SD card write speeds and prevent data loss.
* **Data Extraction:** Parses raw binary/HEX logs into clean CSV or Parquet formats.
* **Analysis Suite:** Interactive dashboards featuring 3D flight paths, sensor fusion visualization (Kalman filtering), and spectral analysis (FFT).
* **Automated Reporting:** Generates PDF summaries detailing peak values, system anomalies, and flight stats.

## Installation
```text

git clone [https://github.com/your-username/sensor-data-recorder-and-analysis.git](https://github.com/your-username/sensor-data-recorder-and-analysis.git)
cd sensor-data-recorder-and-analysis
pip install -r requirements.txt
