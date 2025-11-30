# CMOS-Inverter
1.Inverter Schematic
2.Test Schematic
3.Transient Analysis
4.DC Analysis: VTC Curve
5.Swap NMOS and PMOS: Transient Analysis, VTC
6.Layout

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
      Inverter with stronger PMOS (Wp=8um; Wn=2um)
      
  <img width="1517" height="681" alt="image" src="https://github.com/user-attachments/assets/0e397bf3-5609-4dfd-871f-857efcbb4de9" />


4.VTC curve  
Electrically symmetric inverter (Wp=4um; Wn=2um)

<img width="1519" height="672" alt="image" src="https://github.com/user-attachments/assets/c9812bb0-f2a9-42f8-9c65-57ca983e4ded" />


5. Swap of NMOS and PMOS : Transient analysis

   <img width="1636" height="708" alt="image" src="https://github.com/user-attachments/assets/1d9beff6-f9f2-47d3-90c7-0f8871c62643" />

6. Layout

   <img width="679" height="494" alt="image" src="https://github.com/user-attachments/assets/cceb2476-9b7d-468e-84fc-3bf2a254b6ac" />

Layout vs Schematic

<img width="906" height="414" alt="image" src="https://github.com/user-attachments/assets/8615a68e-51ef-4513-9d66-15d961816fd8" />


