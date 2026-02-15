# PBL-Research
Smart Traffic Light System Using Real-Time Traffic Density

📌 Problem Statement

Traditional traffic light systems operate on fixed timers and fail to adapt to real-time traffic flow, leading to congestion, fuel wastage, and increased pollution.

This project aims to design an intelligent traffic signal system that dynamically adjusts signal timings based on real-time vehicle density.

⸻

💡 Project Overview

The Smart Traffic Light System replaces conventional fixed-timer signals with a density-based adaptive control system.

The system:
	•	Detects vehicle presence using sensors
	•	Calculates traffic density in each lane
	•	Dynamically allocates green signal time
	•	Reduces waiting time at signals
	•	Optimizes traffic flow efficiently

⸻

🛠️ Technologies Used
	•	Arduino Uno
	•	IR Sensors
	•	Embedded C Programming
	•	LEDs (Traffic Signal Simulation)
	•	Breadboard Circuit Setup

⸻

⚙️ Working Principle
	1.	IR sensors are placed on each lane to detect vehicle presence.
	2.	The Arduino reads sensor inputs continuously.
	3.	The system compares traffic density between lanes.
	4.	The lane with higher density is given longer green signal duration.
	5.	After completion of the cycle, the process repeats.

⸻

🧠 Algorithm

Start
↓
Read sensor values from all lanes
↓
Count number of vehicles detected
↓
Compare lane densities
↓
Assign green signal to highest density lane
↓
Set green time proportional to traffic density
↓
Switch to next lane
↓
Repeat continuously

⸻

📊 Features
	•	Dynamic signal timing
	•	Real-time traffic density detection
	•	Reduced congestion
	•	Fuel saving
	•	Lower carbon emissions
	•	Cost-effective and scalable system

⸻

🚀 Future Enhancements
	•	AI-based traffic prediction using cameras
	•	Emergency vehicle priority detection
	•	IoT integration for Smart City systems
	•	Cloud-based monitoring dashboard

⸻

📁 Project Structure

Smart-Traffic-Light-System/
│
├── code/
│   └── smart_traffic_light.ino
│
├── circuit/
│   └── circuit_diagram.png
│
└── README.md

👨‍💻 Developed By

Kanav Vij
Bachelor of Engineering (CSE)
Project Based Learning (PBL)
under the guidance of Dr.Lav Upadhyay
