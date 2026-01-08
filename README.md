# Node-RED Joint Status Dashboard

## 📌 Project Overview
This project demonstrates a Node-RED based dashboard for **monitoring robot joint status**.  
The dashboard provides real-time visualization of joint parameters such as position, angle, and operational state in a clean and user-friendly HMI.

The project focuses purely on **status monitoring** and does not include robot selection or multi-robot switching logic.

---

## 🎯 Objectives
- Visualize joint-wise status of a robot
- Provide clear feedback for each joint
- Design an industrial-style HMI using Node-RED
- Ensure easy extensibility for future control features

---

## 🚀 Features
- Real-time joint status display
- Individual joint monitoring panels
- Clean and responsive dashboard UI
- Status indicators for robot operation
- Scalable design for additional joints

---

## 🧰 Technologies Used
- Node-RED
- node-red-dashboard
- JavaScript (Function nodes)

---

## ⚙️ How to Run the Project
1. Install Node-RED
2. Install dashboard nodes: npm install node-red-dashboard
3. Import `flows.json` into Node-RED
4. Deploy the flow
5. Open the dashboard at: http://localhost:1880/ui

---

## 🧠 System Description
Each robot joint is represented as a separate dashboard section.  
Joint data is processed using Node-RED function nodes and displayed using dashboard widgets such as text, gauges, and indicators.

The dashboard acts as a **monitoring HMI**, providing clear and structured feedback of joint status to the user.

---

## 📷 Screenshots
<img width="1835" height="1136" alt="Screenshot from 2026-01-08 12-21-42" src="https://github.com/user-attachments/assets/cf3b8db6-c6e5-4be7-b1e7-0961c6bce713" />

---

## 🔮 Future Improvements
- Add joint limit warnings
- Add historical data visualization
- Integrate real robot feedback (Modbus / TCP / ROS)
- Extend to joint control functionality
- Add coordinates status
- Integrate with more robots on same dashboard
  
---

## 👤 Author
Shrikant Phonde

