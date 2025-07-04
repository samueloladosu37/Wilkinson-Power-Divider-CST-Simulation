# 🔀 Wilkinson Power Divider – CST Simulation

CST simulation result of a **Wilkinson Power Divider (PD)**, a widely used passive microwave component for equal power splitting with excellent port matching and output isolation.

---

## 📘 About Power Dividers

Power dividers and directional couplers are essential components in RF/microwave systems. They allow signal power to be:
- Divided equally (or unequally) between ports
- Combined from multiple sources
- Matched at all ports in well-designed configurations

### Key Types of Power Dividers:
- **T-Junction**: Simple, lossless, but no isolation
- **Resistive Divider**: Matched ports but lossy and low isolation
- **Wilkinson Divider**: Matched, isolated, and lossless when output ports are matched — ideal for practical systems

---

## 🧠 Why the Wilkinson Divider?

The **Wilkinson power divider** is unique because it:
- Provides **equal (3 dB) power split**
- Maintains **perfect matching** at all ports
- Ensures **high isolation** between output ports
- Appears **lossless** when outputs are terminated in matched loads

It accomplishes this by using:
- Quarter-wave transmission lines
- A resistor between output ports to absorb reflected power

---

## 🛠️ Simulation Overview
-Material- Gold-Lossy material
-Substrate-Rogers RO3006
-Resistor-100 ohms
-All dimensions are in mm


![Parameter](https://github.com/samueloladosu37/Wilkinson-Power-Divider-CST-Simulation/blob/main/Parameter%20List.png)
- **Tool Used**: CST Studio Suite
- **Simulation Type**: S-Parameter analysis
- **Frequency Range**: [75GHz - 110GHz]
- **Target**: 3 dB equal power split with high output isolation

> 📌 Design
![S-Parameters](https://github.com/samueloladosu37/Wilkinson-Power-Divider-CST-Simulation/blob/main/Wilkinson%20PD.png)
![Design](https://github.com/samueloladosu37/Wilkinson-Power-Divider-CST-Simulation/blob/main/PD%20Design.png)

---

## 📈 CST Simulation Results
![Design](https://github.com/samueloladosu37/Wilkinson-Power-Divider-CST-Simulation/blob/main/Wilkinson%20PD_20.gif)
![S-Parameters](https://github.com/samueloladosu37/Wilkinson-Power-Divider-CST-Simulation/blob/main/S11.png)
![S-Parameters](https://github.com/samueloladosu37/Wilkinson-Power-Divider-CST-Simulation/blob/main/S21%2C%20S31.png)
![S-Parameters](https://github.com/samueloladosu37/Wilkinson-Power-Divider-CST-Simulation/blob/main/s23.png)

**Figure:** S-parameter magnitude plot of the Wilkinson Power Divider from 75–110 GHz

### ✅ Key Results:
Bandwidth: 93–100 GHz (optimal performance)
- **Return Loss (S11):**  
  Drops below **–30 dB** near 95 GHz → ✅ **Excellent match**

- **Transmission (S21/S31):**  
  Balanced around **–3 to –6 dB** → ✅ Maintains ideal 50/50 power split

- **Isolation (S23):**  
  reaches **below –35 dB** at 100GHz → ✅ Strong isolation

These results confirm that the divider meets its target functionality within the mmWave band. The simulation shows strong performance in matching, isolation, and transmission symmetry — all key for a well-designed Wilkinson Power Divider.

### ✅ Reference
The design principles were taken from:

D. M. Pozar, Microwave Engineering, 4th ed. John Wiley & Sons, Inc., 2011.
