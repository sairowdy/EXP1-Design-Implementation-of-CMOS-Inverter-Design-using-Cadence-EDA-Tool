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
#### 1. Schematic of CMOS Inverter:

![IMG-20250228-WA0007](https://github.com/user-attachments/assets/25eaf7de-b414-4b44-92b6-c4f48d81f91e)

#### 2. Transient Response Setup:

    ![IMG-20250228-WA0005](https://github.com/user-attachments/assets/8a3ae524-c8f8-4602-aae5-5fd72e0aa829)

#### 3. Voltage Transfer Characteristic (VTC)  Setup:

   ![IMG-20250228-WA0005](https://github.com/user-attachments/assets/a898113d-7e6a-4e0a-bcef-36049df2df97)

## Output
#### 1.Transient Analysis Output

  ![IMG-20250228-WA0006](https://github.com/user-attachments/assets/2d0e030e-ae37-4603-bc79-7ee76772bff6)

#### 2.DC Analysis Output

![IMG-20250228-WA0008](https://github.com/user-attachments/assets/b2b643ca-eca4-4e7a-b438-a6f56197af0f)


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











