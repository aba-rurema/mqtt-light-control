# MQTT-Based Light Control

This project implements an MQTT-based light control system using a web interface and a simulated IoT device.

## Features
- Web interface (`index.html`) with buttons to turn a light ON or OFF.
- Uses **MQTT.js** to send messages via WebSockets.
- Python script (`light_simulation.py`) simulates an ESP8266, listening for messages.

## Setup Instructions
1. Open `index.html` in a browser to control the light.
2. Run `light_simulation.py` in Python (`python3 light_simulation.py`).
3. Click ON/OFF buttons in the browser and observe the output in Python.

## Dependencies
- MQTT.js (CDN included in HTML)
- Python: `paho-mqtt` (`pip install paho-mqtt`)
