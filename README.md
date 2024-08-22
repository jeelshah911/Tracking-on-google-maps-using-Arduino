# Tracking-on-google-maps-using-Arduino

# Introduction
This project lets you track your vehicle's location on Google Maps using an Arduino, GPS module, and Wi-Fi module. You'll be able to view your vehicle's location by clicking a link on a webpage.


# How I Set It Up
Connect the Components:
1.)       **Connect the GPS Module to the Arduino using UART (TX to RX, RX to TX).**
2.)       **Connect the ESP8266 Wi-Fi Module to the Arduino.**
3.)       Optionally, connect a 16x2 LCD to the Arduino for status updates.
4.)       Connect the Arduino to your laptop using a USB cable.
5.)       Configure the Wi-Fi Module:

You should update the Wi-Fi SSID and password to match your Wi-Fi network.
The ESP8266 will connect to your Wi-Fi and get an IP address.

# How I tracked my vehicle

1.)       Open the serial monitor in the Arduino IDE to view the IP address assigned to the ESP8266.
2.)       Enter this IP address in your web browser.
3.)       The webpage will display a link to Google Maps with your vehicle's location. Click the link to view your vehicle's position on the map.
4.)       Power up the Arduino and all connected modules.
5.)       Refresh the webpage on your browser to get the latest location coordinates.
