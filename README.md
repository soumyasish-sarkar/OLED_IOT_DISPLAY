IoT Enabled Text Display on OLED Screen using Arduino Cloud IoT Platform<br>
ISEA Phase III Bootcamp on SDN, IoT, and Network Slicing in 5G and Beyond<br>
Submitted by: Group 3<br>
Soumyasish Sarkar<br>
Ranveer Bharti<br>
Harsh Kumar<br>
Souhardyo Sikder<br>
Debasmita Sarma<br>
Tezpur University<br>
📅 February 2025<br><br>

📌 Project Overview<br>
This project demonstrates how to display text on an OLED screen using an ESP32/NodeMCU and the Arduino Cloud IoT platform.<br>
The system enables real-time text updates via a mobile app or web interface.<br><br>

🛠 Hardware and Software Requirements<br>
🔩 Hardware<br>
S. No Component Specification Quantity<br>
1 Microcontroller Board NodeMCU / ESP32 1<br>
2 OLED Display 128×64 px (SSD1306) 1<br>
3 Breadboard - 1<br>
4 Jumper Wires Male-Male, Female-Female As required<br>
5 USB Cable Micro USB/Type-C 1<br><br>

💻 Software<br>
S. No Software Description Availability<br>
1 Arduino IDE Programming the microcontroller Download<br>
2 Arduino IoT Cloud IoT cloud platform for text input Website<br>
3 Libraries Adafruit GFX, Adafruit SSD1306, Wire, ArduinoIoTCloud Installed via Arduino IDE<br><br>

🔌 Connection Diagram<br>
Connect the OLED display to the ESP32/NodeMCU as follows:<br><br>

OLED Display Pin → ESP32/NodeMCU Pin<br>
VCC → 3.3V<br>
GND → GND<br>
SDA → GPIO 21<br>
SCL → GPIO 22<br><br>

🚀 Step-wise Procedure<br>
1️⃣ Step 1: Hardware Connections<br>
- Connect VCC, GND, SDA, and SCL of the OLED display to the ESP32/NodeMCU.<br>
- Use a breadboard and jumper wires for stable connections.<br>
- Power the board using a USB cable.<br><br>

2️⃣ Step 2: Software Setup<br>
- Install Arduino IDE and required libraries:<br>
  - Adafruit GFX<br>
  - Adafruit SSD1306<br>
  - Wire<br>
  - ArduinoIoTCloud<br>
- Set up an Arduino IoT Cloud account.<br><br>

3️⃣ Step 3: Configure Arduino IoT Cloud<br>
- Create a variable `displayText` in Arduino IoT Cloud.<br>
- Associate your ESP32/NodeMCU with the cloud.<br>
- Enter Wi-Fi credentials in the setup.<br><br>

4️⃣ Step 4: Upload Code<br>
- Copy the Arduino Sketch from `main.ino`.<br>
- Open Arduino IDE, paste the code.<br>
- Select the correct Board & Port and upload.<br><br>

📜 Program Files<br>
- `main.ino` → Arduino Sketch (Contains main program logic)<br>
- `thingProperties.h` → Cloud configurations and variable linking<br><br>

📌 Features<br>
✅ Real-time text updates from Arduino IoT Cloud<br>
✅ Supports ESP32/NodeMCU with SSD1306 OLED Display<br>
✅ Simple Wi-Fi connectivity for remote text updates<br>
✅ Uses Arduino IoT Cloud for easy IoT integration<br><br>

📌 Output<br>
Once uploaded, the OLED screen will display text received from Arduino IoT Cloud, and updates will be reflected in real-time.<br><br>

📢 Conclusion<br>
This project successfully implements IoT-enabled text display on an OLED screen using ESP32/NodeMCU and Arduino IoT Cloud.<br>
The system allows real-time text updates via mobile and web interfaces, making it an effective demonstration of IoT applications in text-based display systems.<br>
