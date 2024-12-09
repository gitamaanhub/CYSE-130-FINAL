# CYSE-130-FINAL
## Overview

This repository contains the final project for CYSE 130, focusing on the automation of system monitoring, network analysis, and threat detection using Python. The project integrates various cybersecurity tools and techniques to enhance system security, monitor performance, and provide real-time alerts.

## Features

- **System Monitoring**: Tracks CPU and memory usage using the `psutil` library, with email alerts for threshold breaches.
- **Log Analysis**: Analyzes Linux system logs (`Linux_2k.log`) for anomalies like failures or unknown events.
- **Network Scanning**: Performs Nmap scans and packet capturing with Python’s subprocess module and Scapy.
- **Threat Detection**: Identifies potential vulnerabilities and suspicious activities.
- **Data Visualization**: Generates trend analysis dashboards for system performance and network activity (planned integration with tools like Grafana or Kibana).
  
## Key Objectives

1. Automate the analysis of system logs to detect security incidents.
2. Monitor system performance metrics and respond to resource spikes.
3. Conduct network scans to identify vulnerabilities and potential threats.
4. Provide recommendations for improved system security and scalability.

## Requirements

### Software and Libraries
- Python 3.x
- `psutil` for performance monitoring
- `smtplib` for email alerts
- `Scapy` for packet analysis
- `Nmap` (requires installation on the system)
- Visualization tools (e.g., Grafana, Kibana - optional)



## Challenges and Insights

### Challenges
- Handling data inconsistencies and large datasets.
- Addressing memory management issues.
- Mitigating hardcoded credential vulnerabilities.

### Insights
- Observed clear trends in system performance and user behavior.
- Detected security vulnerabilities like weak authentication mechanisms.

## Future Enhancements

- **Modular Design**: Add intrusion detection and advanced network scanning capabilities without redesigning the system.
- **Machine Learning**: Integrate adaptive log analysis to identify novel threats.
- **Enhanced Security**: Replace hardcoded credentials with secure storage mechanisms.

## Usage

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Configure the script parameters in `config.json` (e.g., log file paths, email credentials).
4. Run the Python scripts to start monitoring and analysis.

```bash
python monitor_system.py
python analyze_logs.py
python network_scan.py
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any feature suggestions or bug fixes.

