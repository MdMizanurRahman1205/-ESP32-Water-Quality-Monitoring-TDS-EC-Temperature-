# -ESP32-Water-Quality-Monitoring-TDS-EC-Temperature-
This project uses an ESP32, DS18B20 temperature sensor, and a TDS sensor to measure water quality parameters including:  ✅ TDS (Total Dissolved Solids) in ppm  ✅ EC (Electrical Conductivity) in mS/cm  ✅ Temperature in °C and °F

The values are:
Displayed on an SSD1306 OLED
Hosted on a web server accessible via ESP32’s static IP
Continuously updated every 2 seconds

🚀 Features
📡 ESP32 Web Server: Displays real-time TDS, EC, and temperature in a responsive web page.
🎛 OLED Display: Local monitoring with a clean interface.
⚡ Noise Reduction: Averaging algorithm for stable analog readings.
🌐 Static IP Configuration: Reliable connection within the network.
🛠 Calibration Support: Adjustable EC calibration factor for accurate results.

🖼 Web Dashboard Preview
Auto-refreshing web page with clean UI.
Shows TDS, EC, and Temperature values in real time.

🔧 Hardware Required

ESP32 Dev Board
DS18B20 Temperature Sensor
TDS Sensor Module
0.96" SSD1306 OLED Display (I2C)
Jumper Wires + Breadboard

📡 Circuit Connections
DS18B20 → GPIO 26
TDS Sensor (Analog Out) → GPIO 36
OLED (SDA, SCL) → ESP32 I2C Pins (default: GPIO 21, 22)

👨‍💻 Author:
Md Mizanur Rahman
Designed & Developed for IoT-based water quality monitoring.
