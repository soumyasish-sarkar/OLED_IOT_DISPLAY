IoT Enabled Text Display on OLED Screen using Arduino Cloud IoT Platform
ISEA Phase III Bootcamp on SDN, IoT, and Network Slicing in 5G and Beyond
Submitted by: Group 3
Soumyasish Sarkar
Ranveer Bharti
Harsh Kumar
Souhardyo Sikder
Debasmita Sarma
Tezpur University
📅 February 2025

📌 Project Overview
This project demonstrates how to display text on an OLED screen using an ESP32/NodeMCU and the Arduino Cloud IoT platform. The system enables real-time text updates via a mobile app or web interface.

🛠 Hardware and Software Requirements
🔩 Hardware
S. No	Component	Specification	Quantity
1	Microcontroller Board	NodeMCU / ESP32	1
2	OLED Display	128×64 px (SSD1306)	1
3	Breadboard	-	1
4	Jumper Wires	Male-Male, Female-Female	As required
5	USB Cable	Micro USB/Type-C	1
💻 Software
S. No	Software	Description	Availability
1	Arduino IDE	Programming the microcontroller	Download
2	Arduino IoT Cloud	IoT cloud platform for text input	Website
3	Libraries	Adafruit GFX, Adafruit SSD1306, Wire, ArduinoIoTCloud	Installed via Arduino IDE
🔌 Connection Diagram
Connect the OLED display to the ESP32/NodeMCU as follows:

OLED Display Pin	ESP32/NodeMCU Pin
VCC	3.3V
GND	GND
SDA	GPIO 21
SCL	GPIO 22
🚀 Step-wise Procedure
1️⃣ Step 1: Hardware Connections
Connect VCC, GND, SDA, and SCL of the OLED display to the ESP32/NodeMCU.
Use a breadboard and jumper wires for stable connections.
Power the board using a USB cable.
2️⃣ Step 2: Software Setup
Install Arduino IDE and required libraries:
Adafruit GFX
Adafruit SSD1306
Wire
ArduinoIoTCloud
Set up an Arduino IoT Cloud account.
3️⃣ Step 3: Configure Arduino IoT Cloud
Create a variable displayText in Arduino IoT Cloud.
Associate your ESP32/NodeMCU with the cloud.
Enter Wi-Fi credentials in the setup.
4️⃣ Step 4: Upload Code
Copy the Arduino Sketch from main.ino.
Open Arduino IDE, paste the code.
Select the correct Board & Port and upload.
📜 Program Files
main.ino → Arduino Sketch (Contains main program logic)
thingProperties.h → Cloud configurations and variable linking
📌 Features
✅ Real-time text updates from Arduino IoT Cloud
✅ Supports ESP32/NodeMCU with SSD1306 OLED Display
✅ Simple Wi-Fi connectivity for remote text updates
✅ Uses Arduino IoT Cloud for easy IoT integration

📌 Output
Once uploaded, the OLED screen will display text received from Arduino IoT Cloud, and updates will be reflected in real-time.

📢 Conclusion
This project successfully implements IoT-enabled text display on an OLED screen using ESP32/NodeMCU and Arduino IoT Cloud. The system allows real-time text updates via mobile and web interfaces, making it an effective demonstration of IoT applications in text-based display systems.
