# EthicalWiFiMapper-EMPGuard

**EthicalWiFiMapper-EMPGuard** is a privacy-focused, non-intrusive WiFi signal mapping tool enhanced with real-time space weather and EMP impact modeling. It helps visualize and analyze WiFi device activity and signal strength while accounting for environmental disturbances such as solar flares, geomagnetic storms, and electromagnetic pulses.

---

## Features

- Passive WiFi probe request and beacon monitoring without network disruption  
- Real-time signal heatmap visualization and device movement tracking  
- Integration of space weather data (solar flares, geomagnetic storms) to simulate signal degradation  
- EMP event simulation and adaptive scanning based on environmental conditions  
- Ethical safeguards via device whitelisting and data anonymization  
- Export collected data to CSV and Parquet formats for offline analysis  
- Modular architecture with dependency injection for extensibility  
- Encrypted audit logging and optional TPM hardware security support  
- Async WebSocket server for real-time updates and interactive visualization  

---

## Installation

Requires Python 3.8+ with dependencies:

```bash
pip install numpy matplotlib scapy pandas requests scipy pyqt5 cryptography aiohttp dependency-injector
