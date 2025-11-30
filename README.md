# Dipole-Antenna-4NEC2
Dipole Antenna simulation in Free Space using 4NEC2
## Dipole Antenna Project in Free Space

This file (`Example1.nec`) is a simulation of a **basic antenna** called a Half-wave Dipole ($\lambda/2$). We used the **4NEC2** software to run the test.

This project shows my understanding of basic antenna science (theory) and how to set up simulations correctly.

---

## 1. Goal of the Test

* **Antenna Type:** Half-wave Dipole ($\lambda/2$).
* **Test Frequency:** **300 MHz**.
* **Main Goal:** To prove that the antenna's **Input Resistance ($R$)** is close to **73 Ohms** and that the antenna is perfectly **in tune (resonant)**.

---

## 2. Test Results (Simulation Data)

The test was done in **Free Space** (no ground effects). The results are:

| Measurement | Theoretical Goal | **Actual Result** | What We Learned |
| :--- | :--- | :--- | :--- |
| **Input Impedance ($Z_{in}$)** | $73 + j0 \ \Omega$ | **$72.08 - j0.0017 \ \Omega$** | **Perfectly Tuned:** The result is very close to the $73 \ \Omega$ theory, showing excellent resonance. |
| **VSWR (Ref. $50 \ \Omega$ cable)** | Around $1.46:1$ | **$1.44:1$** | This is a **very good match** to a $50 \ \Omega$ cable. |
| **Peak Gain** | Around $2.15 \ \text{dBi}$ | **$2.15 \ \text{dBi}$** | The gain is exactly as expected for a standard dipole in free space. |

**Conclusion:** The simulation confirms that the $\lambda/2$ dipole design works exactly as the theory predicts. This shows that the simulation setup was correct and reliable.


