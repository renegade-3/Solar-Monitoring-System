# Solar Array Monitoring System
Ishaan Mukherjee (PES1UG19EE041)
Divyansh Mitra (PES1UG19EE032)
M Ankur Bheemaiah (PES1UG19EE051)

Developed over the course of the internship for the IoT Dept at PESU.
This project is able to provide realtime monitoring of a solar panel along with a connected energy storage. Monitored data
includes voltage, current, power, light level, charging status, etc.

## Overview
### 1. Arduino Setup
### 2. Web App Setup

## Arduino Setup
1. The hardware setup is provided as a reference image in the repository named _circuit-diagram-01.png_.
2. With the above hardware setup built, download the _esp32_main.ino_ file.
3. Open the _esp32_main.ino_ file using Arduino or any other IDE.
4. Modify the `WIFI_SSID` and `WIFI_PASSWORD` variables to your personal or work network details.
5. Modify the `API_KEY` and `DATABASE_URL` variables to your required database details.
6. Upload the code to the ESP32.

## Web App Setup
1. Download the respository and move it to any folder of choice.
2. Open your CLI in the selected directory and run `npm init` to download all necessary node modules.
3. Modify _firebase.js_ to make any changes to the database credentials as and when required.
4. Run `npm start` to run the app in development mode.
