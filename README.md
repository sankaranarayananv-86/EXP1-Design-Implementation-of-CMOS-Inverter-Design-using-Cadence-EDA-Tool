# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. CMOS Inverter:

![image<img width="1920" height="1080" alt="Screenshot 2025-09-25 140632" src="https://github.com/user-attachments/assets/336e602a-d54e-4c59-a320-720548e7922c" />




#### 4. Transient Response Setup:

<img width="1244" height="588" alt="Screenshot 2025-09-26 141441" src="https://github.com/user-attachments/assets/173e8e30-5427-40df-bcf7-62873414bc73" />





## Output
#### 1.Transient Analysis Output
<img width="1920" height="1080" alt="Screenshot 2025-09-25 140725" src="https://github.com/user-attachments/assets/41bd52d8-1851-4f71-b647-0a3ae8e68da6" />



<img width="1920" height="1080" alt="Screenshot 2025-09-25 140959" src="https://github.com/user-attachments/assets/596ba586-7091-40b4-b5fb-ec6655ef1829" />


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











