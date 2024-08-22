# Vehicle Tracking System Using Google Maps and Arduino

## Introduction
This project lets you track your vehicle's location on Google Maps using an Arduino, GPS module, and Wi-Fi module. You'll be able to view your vehicle's location by clicking a link on a webpage.

## Components Required
- Arduino UNO
- Wi-Fi Module ESP8266
- GPS Module
- USB Cable
- Connecting Wires
- Laptop
- Power Supply
- Breadboard

## How I Set It Up

1. **Connect the Components:**
   - Connect the GPS Module to the Arduino using UART (TX to RX, RX to TX).
   - Connect the ESP8266 Wi-Fi Module to the Arduino.

2. **Configure the Wi-Fi Module:**
   - In the code, update the Wi-Fi SSID and password to match your Wi-Fi network.
   - The ESP8266 will connect to your Wi-Fi and get an IP address.

4. **Track Your Vehicle:**
   - Open the serial monitor in the Arduino IDE to view the IP address assigned to the ESP8266.
   - Enter this IP address in your web browser.
   - The webpage will display a link to Google Maps with your vehicle's location. Click the link to view your vehicle's position on the map.

## Running the System
1. Power up the Arduino and all connected modules.
2. Refresh the webpage on your browser to get the latest location coordinates.
3. Click the Google Maps link to see your vehicle's location.
