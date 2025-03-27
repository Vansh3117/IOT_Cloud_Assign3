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
Sends data to ThingSpeak via MQTT
Visualizes sensor data  using Colab and Matplotlib
Uses ThingSpeak’s REST API to retrieve data
🚀 How to Use

Clone this repository git clone 

Update API Keys In py file or the Colab notebook: Replace the WRITE_API_KEY with your ThingSpeak write key Replace the READ_API_KEY if your channel is private

Run Sensor Simulation (Locally)

View Visualization Open the .ipynb notebook to: Fetch data from ThingSpeak Plot temperature, humidity, and CO₂.

📷 Screenshots See the /screenshots/ folder for: Colab output ThingSpeak channel view Visualizations

🧰 Tech Stack Python 3 Google Colab ThingSpeak (IoT Cloud Platform) Matplotlib, Pandas, Requests

🪞 Reflection 
This assignment helped me understand how IoT systems interact with cloud platforms using real-world protocols like MQTT. I found it fascinating to see how a virtual sensor system could stream live data into a web-based dashboard with real-time visualization. Initially, I encountered an issue with the paho-mqtt client due to a version mismatch, but resolving it helped me better understand Python’s evolving libraries. Another challenge was formatting MQTT payloads correctly for ThingSpeak, which I overcame by carefully checking the documentation and payload structure. Overall, I feel more confident working with IoT data, APIs, and cloud platforms now, and I enjoyed the process of solving real-world problems during this project.
