# RLC-Series-Circuit-Analyzer-MATLAB-GUI-Simulink

This project implements an **interactive MATLAB application and Simulink model** for analyzing an **RLC series circuit**.  
The user can input custom values for **resistance (R)**, **inductance (L)**, and **capacitance (C)** through a GUI, and the program calculates and displays the **current** and **voltage** across each component in both time and frequency domains.

---

## 🧩 Project Overview

An **RLC series circuit** consists of a resistor, inductor, and capacitor connected in series to an AC voltage source.  
The MATLAB GUI provides an easy way for users to:
- Input circuit parameters  
- Compute total impedance  
- Determine the current amplitude and phase  
- Calculate voltage drops across R, L, and C  
- Visualize results and verify them using Simulink simulation  

The accompanying **Simulink model** (`Tysier_Zidan_Final_MATLAB_Project_211611181.slx`) demonstrates the same system behavior dynamically.

---

## ⚙️ Features

- 🧮 Calculates:
  - Impedance \( Z = \sqrt{R^2 + (ωL - 1/ωC)^2} \)
  - Current amplitude and phase  
  - Voltage across R, L, and C  
- 🖥️ Interactive **MATLAB App Designer GUI**  
- ⚡ Real-time simulation using **Simulink**  
- 📊 Visual representation of results (plots or displays)  
- 🧱 Modular design — MATLAB function + GUI + Simulink model  

---

## 🧠 File Descriptions

| File | Description |
|:--|:--|
| `main.m` | Main script that launches the GUI and runs the project. |
| `RLC_series_circuit.mlapp` | App Designer GUI for inputting R, L, C and displaying results. |
| `Tysier_Zidan_Final_MATLAB_Project_211611181.slx` | Simulink model representing the RLC circuit. |
| `acp154.jpg` | Circuit diagram used for visualization. |
| `run_RLC.asv` | Auto-saved backup of the MATLAB function. |

---

## 🧪 How to Run

1. **Download** the repository or clone it.  
2. Open **MATLAB R2022a or later**.  
3. Make sure all project files are in the same directory.  
4. Run the following command in the MATLAB Command Window:
   ```matlab
   RLC_series_circuit();
