# Day 1 — Basic N-MOSFET Circuit Simulation using SPICE

## 🔹 Overview
This experiment focuses on simulating the basic characteristics of an N-MOSFET using SPICE.  
The objective is to observe the I–V characteristics and analyze the transistor behavior at various gate voltages.

---

## 🧩 SPICE Simulation Code
![SPICE Code Screenshot](https://github.com/user-attachments/assets/394f1d5e-6640-41d2-adb3-70197f1deea1)

---

## 📈 SPICE Outputs

### I–V Characteristics
![I–V Characteristics](https://github.com/user-attachments/assets/a5ed481c-d86f-4c3f-b87e-f8c275b5dd17)

---

### For V<sub>GS</sub> = 0.6 V
![Vgs = 0.6V](https://github.com/user-attachments/assets/51af25bf-7e15-4bc6-b088-b3a66a9c3098)

---

### Drain Current at V<sub>DS</sub> = 1.3 V
The drain current (I<sub>D</sub>) corresponding to V<sub>DS</sub> = 1.3 V is shown below:
![ID at Vds = 1.3V](https://github.com/user-attachments/assets/67b342fa-0f89-44a5-b8e1-60856af9d462)

---

## 🧠 Observation
- The output characteristics show that I<sub>D</sub> increases with V<sub>GS</sub>, as expected.  
- The device transitions from the linear to the saturation region as V<sub>DS</sub> increases.  
- The SPICE results closely match theoretical predictions for an enhancement-type NMOS transistor.  
- The cutoff region occurs when V<sub>GS</sub> &lt; V<sub>T</sub>, where no conduction takes place.

---

## 🧾 Key Takeaways
- SPICE effectively models MOSFET behavior across different operating regions.  
- Increasing V<sub>GS</sub> enhances channel formation, leading to higher I<sub>D</sub>.  
- The results validate the quadratic relationship between I<sub>D</sub> and V<sub>GS</sub> in long-channel NMOS devices.
