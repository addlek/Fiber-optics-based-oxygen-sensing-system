# Fiber-optics-based-oxygen-sensing-system

## Project Overview
This repository contains a Python-based application designed to interface with a fiber-optic oxygen sensing system. It processes optical signal data to measure and log oxygen concentration levels from a serial interface.

## System Block Diagram
```mermaid
graph LR
    A[Optical Light Source] -->|Fiber Cable| B(Oxygen Sensor Probe)
    B -->|Optical Signal| C[Photodetector]
    C -->|Analog Voltage| D[Data Acquisition Unit]
    D -->|Digital Interface| E[Python Script]
    E -->|Process & Compute| F[(Data Log .csv)]
```

## Getting Started
1. Clone this repository to your laptop.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the primary script: `python main.py`
