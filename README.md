# 🚀 Elevator Controller Verification using UVM

## 📌 Overview
This project implements and verifies a Finite State Machine (FSM)-based elevator controller using SystemVerilog and UVM. The elevator operates between floors 0 to 3, handling user requests and emergency conditions.

A structured UVM testbench is used to drive inputs, monitor outputs, and validate the design with clean, event-driven logs.

---

## 🧠 Features
- Supports 4 floors (0–3)
- Automatic up/down movement
- Door opens at destination floor
- Emergency mode support
- Directed test sequence
- Clean and readable simulation output

---

## ⚙️ FSM States
- IDLE  
- MOVE_UP  
- MOVE_DOWN  
- DOOR_OPEN  
- EMERGENCY  

---

## 🧪 UVM Components
- Sequence  
- Driver  
- Monitor  
- Agent  
- Environment  
- Test  

---

## 📟 Sample Output

[DRIVER] REQ=3 EMERGENCY=0
[MON] Floor=1 Door=0 Up=1 Down=0
[MON] Floor=2 Door=0 Up=1 Down=0
[MON] Floor=3 Door=1 Up=0 Down=0


---

## 🛠️ Tools Used
- SystemVerilog  
- UVM  
- Xilinx Vivado Simulator  

---

## 🎯 Learning Outcomes
- FSM design  
- UVM architecture  
- Transaction-based verification  
- Debugging and clean logging  

---

## 👨‍💻 Author
Dhanush S Poojary
Dhanya 
Dhanush GS
