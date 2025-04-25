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

![Screenshot 2025-04-25 110212](https://github.com/user-attachments/assets/e5479117-0c6e-4815-8c62-5e0a3f6db987)



#### 2. Schematic of CMOS Inverter:

  ![Screenshot 2025-04-25 110239](https://github.com/user-attachments/assets/f7c84759-c014-4511-8e3d-eabf482cf529)


#### 3. Transient Response Setup:


![Screenshot 2025-04-25 110347](https://github.com/user-attachments/assets/63c3a4c8-56ef-4b77-9190-02e3f7039f02)



![Screenshot 2025-04-25 110413](https://github.com/user-attachments/assets/c831864a-021b-43ee-b17d-ab468f53fe26)



## Output
#### 1.Transient Analysis Output

  ![Screenshot 2025-04-25 110554](https://github.com/user-attachments/assets/bfb0bd4a-dee0-4990-be5a-d60a60a28fcb)



## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











