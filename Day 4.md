# Day 4 — Noise Margin Calculation for a CMOS Inverter

## 🔹 SPICE Setup  
![SPICE Setup](https://github.com/user-attachments/assets/07dba942-9a94-421b-9672-7b4ce77dfcd6)

---

## 📈 SPICE VTC Curve  
![VTC Curve](https://github.com/user-attachments/assets/3531cb9c-7e63-4fec-8baa-9ff618ba06bc)

---

## 📊 Plotting \(V_{IH}\), \(V_{OH}\), \(V_{IL}\), \(V_{OL}\)  
![Noise Levels](https://github.com/user-attachments/assets/8af9db24-9d3d-41f2-97d0-94e467c5b781)

Measured values:

- \(V_{IH} = 0.984 \, \text{V}\)  
- \(V_{OH} = 1.714 \, \text{V}\)  
- \(V_{IL} = 0.767 \, \text{V}\)  
- \(V_{OL} = 0.0976 \, \text{V}\)

Using these, the noise margins are:

- \(NM_L\) (Low noise margin) = 0.67  
- \(NM_H\) (High noise margin) = 0.73  

---

## 🧠 Key Insights  
- The noise margins quantify how much noise the inverter can tolerate before flipping its logic state.  
- The values of \(NM_L\) and \(NM_H\) being relatively large (0.67 V and 0.73 V) indicate that the inverter is robust against voltage glitches.  
- This robustness is central to why CMOS technology is reliable for digital logic circuits even in the presence of noise.
