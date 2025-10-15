# Day 3 — Plotting the Voltage Transfer Characteristics and Transient Response of a CMOS Inverter

## 🔹 Objective
To analyze the **Voltage Transfer Characteristics (VTC)** and **Transient Response** of a CMOS inverter using SPICE simulation, and to determine the **switching threshold**, **rise delay**, and **fall delay** times.

---

## ⚙️ 1. Voltage Transfer Characteristics (VTC)

### 🧩 SPICE Simulation Code
![SPICE Code](https://github.com/user-attachments/assets/a32b6cfd-51f1-495d-bbd8-557f20bc74d4)

---

### 📈 SPICE Output Plot
![VTC Output](https://github.com/user-attachments/assets/0cf7bc11-4ca0-492f-8bc5-9320ce2a741d)

---

### ⚡ Calculating Switching Threshold (V<sub>M</sub>)
The switching threshold voltage is determined from the VTC curve at the point where **V<sub>IN</sub> = V<sub>OUT</sub>**.

![Finding Vm 1](https://github.com/user-attachments/assets/db556a2a-c62f-4af7-8ecd-89c192de7673)
![Finding Vm 2](https://github.com/user-attachments/assets/b75633ce-e0a1-4213-815d-b34c9a1f1e05)

**Switching Threshold (V<sub>M</sub>) ≈ 0.87 V**

**Observation:**  
- The VTC shows a sharp transition region, indicating proper inverter operation.  
- The switching threshold defines the balance point between the NMOS and PMOS transistors.

---

## ⚙️ 2. Transient Characteristics

### 🧩 SPICE Simulation Code
![Transient SPICE Code](https://github.com/user-attachments/assets/22387e1e-0217-4cf9-9cc4-b08dcb875f84)

---

### 📈 SPICE Output Plot
![Transient Output](https://github.com/user-attachments/assets/c4a2fb04-8992-44cd-8633-1f67f7a2b291)

---

### ⏱ Calculating Rise Delay Time
At **V = 0.9 V**, note the time difference between the input signal and the output response.

![Rise Time Measurement](https://github.com/user-attachments/assets/58c45bf7-1a24-4225-83a6-3b05af55cb0b)

**Rise Delay Time ≈ 0.3297 ns**

---

### ⏱ Calculating Fall Delay Time
The fall delay is calculated similarly to the rise delay, by noting the time difference at **V = 0.9 V** during the falling edge.

![Fall Time Measurement](https://github.com/user-attachments/assets/346c3fe0-ae84-4d20-90f5-05dcc9c9d563)

**Fall Delay Time ≈ 0.284 ns**

---

## 🧠 Key Insights
- The **switching threshold** (V<sub>M</sub>) marks the point where both NMOS and PMOS transistors operate simultaneously.  
- **Rise time** and **fall time** depend on transistor sizing and capacitive loading.  
- Balanced rise and fall delays indicate symmetric inverter design and strong CMOS performance.

---

