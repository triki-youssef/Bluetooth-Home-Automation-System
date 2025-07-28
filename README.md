 
<h1> 🔌🏠  Bluetooth Home Automation System</h1>

<h2> 🔸 Description : </h2>

<h3>📲 Control Your Entire Home from Your Smartphone </h3>
This project allows you to remotely control up to 8 electrical devices (like lights, fans, TV, or any home appliance) using your smartphone via Bluetooth. It’s built using an Arduino Uno, HC-05 Bluetooth module, and a 5V 8-channel relay module — and paired with a custom app developed in MIT App Inventor.

Whether you're relaxing on your couch or managing devices from across the room, this system makes your home smarter and more convenient.

<h3>🔑 Key Features : </h3>
- ✅ Bluetooth Control: Remotely turn ON/OFF up to 8 devices using your smartphone via Bluetooth (no internet required).

- 📱 Custom Mobile App: Android app built using MIT App Inventor — clean UI with individual buttons for each appliance.

- ⚡ Control High-Voltage Devices: Each relay channel can handle standard AC appliances like lights, fans, or TVs.

- 💡 Independent Channels: Control devices individually — each relay works separately for flexibility.

- 🔒 Secure Connection: Only paired devices can send commands, ensuring basic security.

- 🔌 Plug & Play: Easy-to-understand wiring and simple setup using Arduino Uno.

- 🔋 Low Power: Operates on a 5V relay system, ideal for low-power automation.

- 🛠️ Expandable: Can be upgraded to include sensors, Wi-Fi, or voice control in the future.


<br />


<h2> 🔧 Components and Tools Used : </h2>


<h3>Hardware Components:</h3>

<h4> - Microcontroller:</h4> Arduino Uno

<h4> - Wireless Module:</h4> HC-05 (Bluetooth Module)

<h4>⚡ 5V 8-Channel Relay Module</h4>

<h4>🔌 Household appliances (bulbs, fan, etc.)</h4>



<h4> - Power Supply:</h4> 5V, 2A 


<h3> 🧰 Software & Utilities Used</h3>

<h5> - Arduino IDE:</h5> For programming the microcontroller firmware

<h5> -📱 MIT App Inventor  </h5> Used to design and develop the custom mobile application.
<br />
<br />

<p align="center">
Application Demo (Controlling Window Shutters) <br/>
<img src="https://i.imgur.com/KzRAT9k.jpeg" height="60%" width="60%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/8y9c5TU.jpeg" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
RemoteXY settings  <br/>
<img src="https://i.imgur.com/YeBJQEL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Pins & Variables Declaration : <br/>
<img src="https://i.imgur.com/PZIu9xg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
void setup()  <br/>
<img src="https://i.imgur.com/LpcGoYk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Robot Movement Algorithms with Obstacle Avoidance:  <br/>
<img src="https://i.imgur.com/vO9yD9V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/N8Fb9LO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Handles incoming UI commands from the RemoteXY app interface & Start Command Trigger from App &  Reset Button State  <br/>
  <br/>
<img src="https://i.imgur.com/Di0R06x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Line Following and Obstacle Detection  <br/>
<img src="https://i.imgur.com/xt4UNQb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Line Following and Obstacle Detection  <br/>
<img src="https://i.imgur.com/C5lKYmj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Stop Robot if Not Running  <br/>
<img src="https://i.imgur.com/FcOUGwc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  

<h2>Arm-Program walk-through:</h2>
<p align="center">
🔧 Servo and Sensor Setup <br/>
<img src="https://i.imgur.com/OKzV7YU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
🚀 Initialization <br/>
<img src="https://i.imgur.com/e1oaDBs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
🔁 Main Loop - Object Detection and Response <br/>
<img src="https://i.imgur.com/ENcLSZO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h2>Arm-Wiring-Diagram:</h2>
<p align="center">
 <br/>
<img src="https://i.imgur.com/zVgTVbZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Robot-Wiring-Diagram:</h2>
<p align="center">
 <br/>
<img src="https://i.imgur.com/FDXksz2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Demo : </h2>
https://github.com/user-attachments/assets/fd009389-f377-4bf2-8537-3bc98de77d0d

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
