🌐 IoT Environmental Monitoring System (CIS600 – Assignment 3)

This project simulates a cloud-based IoT system that collects environmental sensor data from virtual stations and sends it to the ThingSpeak cloud platform using HTTP. The system includes virtual sensors that generate random values for temperature, humidity, and CO₂, and visualizes this data in real-time using Python and Google Colab.

📌 Project Details
Course: CIS600 – Internet of Things: Application Development
Assignment: 3
Submitted by: Vansh Rahate

📋 Features
Simulates a virtual environmental station with:
Temperature sensor (°C)
Humidity sensor (%)
CO₂ sensor (ppm)
Sends data to ThingSpeak via HTTP
Visualizes sensor data (last 5 hours) using Colab and Matplotlib
Uses ThingSpeak’s REST API to retrieve data
🚀 How to Use

Clone this repository git clone https://github.com/your-username/iot-environmental-sensors.git

Update API Keys In virtual_station.py or the Colab notebook: Replace the WRITE_API_KEY with your ThingSpeak write key Replace the READ_API_KEY if your channel is private

Run Sensor Simulation (Locally)

View Visualization Open the visualization.ipynb notebook to: Fetch data from ThingSpeak Plot temperature, humidity, and CO₂.

📷 Screenshots See the /screenshots/ folder for: Colab output ThingSpeak channel view Visualizations

🧰 Tech Stack Python 3 Google Colab ThingSpeak (IoT Cloud Platform) Matplotlib, Pandas, Requests

🪞 Reflection During this project, I learned how to adapt when technical limitations (like MQTT not working in Colab) require a shift in approach. Using HTTP instead of MQTT taught me how APIs work in cloud-based IoT systems, and visualizing the sensor data gave me a better understanding of data handling in IoT applications.
