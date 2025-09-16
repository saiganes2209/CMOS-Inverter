# CMOS-Inverter
1.Inverter Schematic
2.Test Schematic
3.Transient Analysis
4.DC Analysis: VTC Curve
5.Swap NMOS and PMOS: Transient Analysis, VTC

1. A simple inverter inverts the logically high input to low output and vice versa.
 It is of immense significance in clock generation, generation of delays,
 memories to store the data, improving the circuit's noise immunity, and much more.
   It is a simple two transistor device. For input 0, PMOS turns ON, and NMOS stays OFF.
This charges the output capacitance, thus making output logic HIGH. Whereas for input 1, PMOS is OFF, and NMOS is ON.
The charged capacitance now discharges, making output logic LOW. On a periodic application of pulse,
  an inverted pulse is obtained at the output. The in-depth analysis of the output on logic 0 to 1 at the
  input is summed up by its Voltage Transfer Characteristics (VTC).
Schematic

<img width="653" height="703" alt="image" src="https://github.com/user-attachments/assets/3a857f3a-2b4a-44fa-a9bb-0c32fd52058e" /> 


2. Test Schematic

   <img width="1447" height="668" alt="image" src="https://github.com/user-attachments/assets/77c7f692-a545-4f62-a140-076eee346788" />

3.Transient Analysis

<img width="1647" height="764" alt="image" src="https://github.com/user-attachments/assets/12f998a3-7b35-44f4-b615-734eb4052046" />

4.VTC curve

<img width="1519" height="672" alt="image" src="https://github.com/user-attachments/assets/c9812bb0-f2a9-42f8-9c65-57ca983e4ded" />

5. Swap of NMOS and PMOS

   <img width="1636" height="708" alt="image" src="https://github.com/user-attachments/assets/1d9beff6-f9f2-47d3-90c7-0f8871c62643" />
