## Shrimp Farm Automation

### IoTEaiser

### Description:
A POC project for shrimp farm automation.

This project had two major components.

The first part included integrating existing sensors, such as water quality measurement tools, power meters, flow meters, and temperature sensors, into our remote sensor hub. This standardized the data format and allowed the data to be sent to our cloud platform.

The second part was building a cloud platform that serves as a data pipeline. The cloud platform collected data from our test sites and conducted pre-processing. Then, the data was stored in a database and displayed in real-time on a control dashboard, also hosted on the cloud. The control dashboard contained a UI for viewing sensor readings, data history, and graphs. Moreover, the dashboard also had a UI for control. Users could control remote equipment like water valves and wheels (via MQTT and our remote sensor hub). The dashboard also allowed users to schedule tasks.

The next step was to apply machine learning techniques to the collected data to extract useful insights. Then, we could combine these insights with experts' domain knowledge to build a machine-learning model. The ultimate goals were to automate shrimp farm operations based on sensor readings and set up anomaly detection.

### Role:
1. Designed and implemented data pipelines using AWS IoT, TimeStream, Lambda, EC2, Grafana, and Node-Red.
2. Developed STM32L4 MCU firmware for the remote sensor hub
3. Led the integration of various sensors and equipment used in this project with the remote sensor hub
