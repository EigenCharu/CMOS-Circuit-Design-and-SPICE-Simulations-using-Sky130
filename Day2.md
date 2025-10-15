# Day 2 - Lower Nodes of Operation in N-MOSFET

## 🔹 Objective
To plot and analyze the I–V characteristics and transfer characteristics (I<sub>D</sub> vs V<sub>GS</sub>) of an NMOS transistor for lower modes, using SPICE simulation.

---

## ⚙️ 1. Plotting I–V Characteristics for Lower Nodes

### 🧩 SPICE Simulation Code
![SPICE Code](https://github.com/user-attachments/assets/3a5c8d8b-741a-4987-aa01-c15512ee3b2f)

---

### 📈 SPICE Output Plot
![I–V Characteristics](https://github.com/user-attachments/assets/60eee104-2b2e-4c28-8348-fd1fd3e129e8)

---

### 🔺 Peak Current Value
![Peak Current](https://github.com/user-attachments/assets/d54d0c7f-56f5-4c3b-8911-8080b697ed5d)

**Observation:**  
- The I–V plot shows the quadrature dependence of I<sub>D</sub> with V<sub>GS</sub> for lower values of V<sub>GS</sub>
- Linear Dependence at of I<sub>D</sub> on V<sub>GS</sub> at higher V<sub>GS</sub> levels.

---

## ⚙️ 2. Plotting I<sub>D</sub>–V<sub>GS</sub> Curve for Lower Nodes

### 🧩 SPICE Simulation Code
![SPICE Code](https://github.com/user-attachments/assets/c24053a8-3e19-41b5-a342-fd9ab43b4195)

---

### 📈 SPICE Output Plot
![ID vs VGS Plot](https://github.com/user-attachments/assets/8309409e-f600-4489-98a7-9bfb0034a664)

---

### ⚡ Threshold Voltage (V<sub>T</sub>) Extraction
![Threshold Voltage](https://github.com/user-attachments/assets/776e4d57-c0b0-49a6-9cde-32a652e0ab8c)

**V<sub>t</sub> = 0.846V**

**Observation:**  
- The transfer characteristics (I<sub>D</sub>–V<sub>GS</sub>) plot indicates the quadrature and linear dependence of I<sub>D</sub>on V<sub>GS</sub> for lower nodes.
- For Lower nodes, there exists an additional mode of operation called **Velocity Saturation Mode**
