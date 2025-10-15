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

<h2>🧮 2. Gain Calculation at Different Supply Voltages</h2>

<table style="border-collapse:collapse;width:100%;max-width:800px;">
  <thead>
    <tr>
      <th style="border:1px solid #e1e4e8;padding:8px 10px;background:#f6f8fa;">V<sub>DD</sub> (V)</th>
      <th style="border:1px solid #e1e4e8;padding:8px 10px;background:#f6f8fa;">VTC Curve</th>
      <th style="border:1px solid #e1e4e8;padding:8px 10px;background:#f6f8fa;">|Gain|</th>
    </tr>
  </thead>
  <tbody style="text-align:center;vertical-align:middle;">
    <tr>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>1.8 V</strong></td>
      <td style="border:1px solid #e1e4e8;padding:8px;">
        <img src="https://github.com/user-attachments/assets/b74cd434-b7f2-412a-acf4-32d5b3cf2bf5" alt="VTC at 1.8V" style="max-width:180px;border-radius:6px;">
        <div style="font-size:0.85rem;color:#555;">VTC @ 1.8 V</div>
      </td>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>7.147</strong></td>
    </tr>
    <tr>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>1.6 V</strong></td>
      <td style="border:1px solid #e1e4e8;padding:8px;">
        <img src="https://github.com/user-attachments/assets/cbe92ad6-0930-4489-af51-23416f0321e4" alt="VTC at 1.6V" style="max-width:180px;border-radius:6px;">
        <div style="font-size:0.85rem;color:#555;">VTC @ 1.6 V</div>
      </td>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>8.524</strong></td>
    </tr>
    <tr>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>1.4 V</strong></td>
      <td style="border:1px solid #e1e4e8;padding:8px;">
        <img src="https://github.com/user-attachments/assets/84f1c586-199f-49e8-99b6-99722e01852b" alt="VTC at 1.4V" style="max-width:180px;border-radius:6px;">
        <div style="font-size:0.85rem;color:#555;">VTC @ 1.4 V</div>
      </td>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>9.183</strong></td>
    </tr>
    <tr>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>1.2 V</strong></td>
      <td style="border:1px solid #e1e4e8;padding:8px;">
        <img src="https://github.com/user-attachments/assets/153cac96-4886-476c-9f3b-64fd2487faae" alt="VTC at 1.2V" style="max-width:180px;border-radius:6px;">
        <div style="font-size:0.85rem;color:#555;">VTC @ 1.2 V</div>
      </td>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>10.074</strong></td>
    </tr>
    <tr>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>1.0 V</strong></td>
      <td style="border:1px solid #e1e4e8;padding:8px;">
        <img src="https://github.com/user-attachments/assets/2f49df1c-0d2d-4d2a-b47c-48d346cc1566" alt="VTC at 1.0V" style="max-width:180px;border-radius:6px;">
        <div style="font-size:0.85rem;color:#555;">VTC @ 1.0 V</div>
      </td>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>9.997</strong></td>
    </tr>
    <tr>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>0.8 V</strong></td>
      <td style="border:1px solid #e1e4e8;padding:8px;">
        <img src="https://github.com/user-attachments/assets/7c149531-c7d5-4148-bb24-e0570357d59b" alt="VTC at 0.8V" style="max-width:180px;border-radius:6px;">
        <div style="font-size:0.85rem;color:#555;">VTC @ 0.8 V</div>
      </td>
      <td style="border:1px solid #e1e4e8;padding:8px;"><strong>8.693</strong></td>
    </tr>
  </tbody>
</table>


---

## 📊 3. Observations and Analysis

- The **gain** of the CMOS inverter **increases** as **V<sub>DD</sub> decreases** from 1.8 V to 1.2 V.  
- Beyond this point (below 1.0 V), the **gain starts to drop** because the **supply voltage is insufficient** for strong switching.  
- Despite variations, the inverter **maintains correct logic operation** across all voltage levels tested.

---

## 🧠 4. Conclusion

- CMOS inverters are **robust** against moderate power supply variations.  
- **Lower V<sub>DD</sub>** reduces noise margin and output swing, eventually degrading performance.  



