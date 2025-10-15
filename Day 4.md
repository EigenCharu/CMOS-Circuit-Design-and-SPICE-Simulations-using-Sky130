# Day 4 — Noise Margin Calculation for a CMOS Inverter

## 🔹 SPICE Setup
![SPICE Setup](https://github.com/user-attachments/assets/07dba942-9a94-421b-9672-7b4ce77dfcd6)

---

## 📈 SPICE VTC Curve
![VTC Curve](https://github.com/user-attachments/assets/3531cb9c-7e63-4fec-8baa-9ff618ba06bc)

---

## 📊 Noise Levels: <code>V<sub>IH</sub></code>, <code>V<sub>OH</sub></code>, <code>V<sub>IL</sub></code>, <code>V<sub>OL</sub></code>
![Noise Levels](https://github.com/user-attachments/assets/8af9db24-9d3d-41f2-97d0-94e467c5b781)

<table>
  <thead>
    <tr>
      <th>Parameter</th>
      <th>Value (V)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>V<sub>IH</sub></code></td>
      <td>0.984</td>
    </tr>
    <tr>
      <td><code>V<sub>OH</sub></code></td>
      <td>1.714</td>
    </tr>
    <tr>
      <td><code>V<sub>IL</sub></code></td>
      <td>0.767</td>
    </tr>
    <tr>
      <td><code>V<sub>OL</sub></code></td>
      <td>0.0976</td>
    </tr>
  </tbody>
</table>

### Noise Margins

<table>
  <thead>
    <tr>
      <th>Margin</th>
      <th>Value (V)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>NM<sub>L</sub></code> (Low noise margin)</td>
      <td>0.67</td>
    </tr>
    <tr>
      <td><code>NM<sub>H</sub></code> (High noise margin)</td>
      <td>0.73</td>
    </tr>
  </tbody>
</table>

---

## 🧠 Key Insights
<ul>
  <li>Noise margins quantify how much noise the inverter can tolerate before flipping its logic state.</li>
  <li>The relatively large values of <code>NM<sub>L</sub> = 0.67 V</code> and <code>NM<sub>H</sub> = 0.73 V</code> indicate robust operation.</li>
  <li>This robustness is one reason CMOS technology is highly reliable in digital circuits, even in noisy environments.</li>
</ul>
