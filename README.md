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

- **Tool Used**: CST Studio Suite
- **Simulation Type**: S-Parameter analysis
- **Frequency Range**: [75GHz - 110GHz]
- **Target**: 3 dB equal power split with high output isolation

> 📌 Design
![S-Parameters](./6bb71a1f-a488-45df-a6e6-9efbbdc6f85a.png)
![S-Parameters](./6bb71a1f-a488-45df-a6e6-9efbbdc6f85a.png)
---

## 📈 CST Simulation Results

![S-Parameters](./6bb71a1f-a488-45df-a6e6-9efbbdc6f85a.png)
![S-Parameters](./6bb71a1f-a488-45df-a6e6-9efbbdc6f85a.png)
![S-Parameters](./6bb71a1f-a488-45df-a6e6-9efbbdc6f85a.png)

**Figure:** S-parameter magnitude plot of the Wilkinson Power Divider from 75–110 GHz

### ✅ Key Results:

- **Return Loss (S11):**  
  < -15 dB near 95–100 GHz → well-matched input

- **Equal Power Split (S21 ≈ S31):**  
  Close to -3 dB → confirms ideal 50/50 power division

- **Isolation (S23):**  
  Better than -20 dB → excellent isolation between output ports

These results confirm that the divider meets its target functionality within the mmWave band. The simulation shows strong performance in matching, isolation, and transmission symmetry — all key for a well-designed Wilkinson Power Divider.


