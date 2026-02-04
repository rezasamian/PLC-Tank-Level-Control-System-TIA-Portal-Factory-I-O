# PLC-Tank-Level-Control-System-TIA-Portal-Factory-I-O
This project demonstrates an automated tank level control system developed using Siemens TIA Portal and simulated with Factory I/O. The system controls water filling and discharging operations while implementing industrial safety and level monitoring logic.
he goal of the project is to simulate a real industrial process where a PLC maintains tank levels using analog control, limit sensors, and safety interlocks.

## 🎬 System Demonstration
![Tank Demo](Tank.gif)

⚙️ System Features

✅ Start / Stop Control

Push-button logic to start and stop the tank operation cycle

🚨 Emergency Stop (E-Stop)

Immediately disables all outputs

System requires safe reset before restarting

Tank Filling Control

Filling valve controlled using an analog setpoint (circular potentiometer)

Adjustable inflow rate

 Tank Discharge Control

Discharge valve controlled using a second analog setpoint

Adjustable outflow rate

Level Monitoring Sensors

Low-Level Sensor – Prevents tank from running dry

High-Level Sensor – Prevents overflow

📊 Tank Volume Indication

Digital output representation of tank volume status

Provides visual feedback of the water level inside the tank


## 💻 PLC Program Screenshots

You can view the full ladder logic screenshots here:  
📁 [PLC_code Screenshots (Word File)](plc-code/Ladder Code.docx)
