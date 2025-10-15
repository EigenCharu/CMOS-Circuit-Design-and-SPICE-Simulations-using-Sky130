# 🧩 Day-5: CMOS Inverter — Response to Power Supply and Device Variations

## 📘 Objective
To analyze how **power supply variations** affect the operation and voltage transfer characteristics (VTC) of a CMOS inverter.  
We also observe how the **gain** of the inverter changes as the supply voltage (**V<sub>DD</sub>**) is varied.

---

## ⚙️ 1. Power Supply Variations

### 🔧 SPICE Setup
The CMOS inverter was simulated in SPICE with varying **V<sub>DD</sub>** values ranging from **1.8 V** to **0.8 V**.

**Circuit Schematic:**

![SPICE Setup](https://github.com/user-attachments/assets/9555125d-2c50-4aaa-ba13-7248f55c7174)

---

### 📈 SPICE Simulation Output

**Voltage Transfer Characteristics (VTC):**

![SPICE Plot](https://github.com/user-attachments/assets/2886ccdd-9276-44a0-80fc-479de49acab5)

**Observation:**  
The CMOS inverter continues to operate correctly across the tested supply voltage range.

---

## 🧮 2. Gain Calculation at Different Supply Voltages

| **V<sub>DD</sub> (V)** | **VTC Curve** | **|Gain|** |
|:----------------------:|:--------------:|:---------:|
| 1.8 V | ![1.8V](https://github.com/user-attachments/assets/b74cd434-b7f2-412a-acf4-32d5b3cf2bf5) | 7.147 |
| 1.6 V | ![1.6V](https://github.com/user-attachments/assets/cbe92ad6-0930-4489-af51-23416f0321e4) | 8.524 |
| 1.4 V | ![1.4V](https://github.com/user-attachments/assets/84f1c586-199f-49e8-99b6-99722e01852b) | 9.183 |
| 1.2 V | ![1.2V](https://github.com/user-attachments/assets/153cac96-4886-476c-9f3b-64fd2487faae) | 10.074 |
| 1.0 V | ![1.0V](https://github.com/user-attachments/assets/2f49df1c-0d2d-4d2a-b47c-48d346cc1566) | 9.997 |
| 0.8 V | ![0.8V](https://github.com/user-attachments/assets/7c149531-c7d5-4148-bb24-e0570357d59b) | 8.693 |

---

## 📊 3. Observations and Analysis

- The **gain** of the CMOS inverter **increases** as **V<sub>DD</sub> decreases** from 1.8 V to 1.2 V.  
- Beyond this point (below 1.0 V), the **gain starts to drop** because the **supply voltage is insufficient** for strong switching.  
- Despite variations, the inverter **maintains correct logic operation** across all voltage levels tested.

---

## 🧠 4. Conclusion

- CMOS inverters are **robust** against moderate power supply variations.  
- **Lower V<sub>DD</sub>** reduces noise margin and output swing, eventually degrading performance.  



