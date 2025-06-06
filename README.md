# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools
## BADIMALA GURUCHARAN (212223060026)
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
### Circuit Diagram:
![WhatsApp Image 2025-03-23 at 10 20 34_0b3eecd0](https://github.com/user-attachments/assets/b4dc1f4a-426b-4376-a047-3a968de8f6eb)

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
![Screenshot 2025-03-23 095030](https://github.com/user-attachments/assets/93955fce-7780-4d71-a75c-6f151c52ee29)

#### 2. Transient Response Setup:
![Screenshot 2025-03-23 094726](https://github.com/user-attachments/assets/d3ff1ad3-8053-44a9-976d-63c2ce80d4e7)

#### 3. Voltage Transfer Characteristic (VTC)  Setup:
![Screenshot 2025-03-23 101254](https://github.com/user-attachments/assets/cf2f0874-265c-4866-9a73-43d3d1beb3d7)


## Output
#### 1.Transient Analysis Output
![Screenshot 2025-03-23 095000](https://github.com/user-attachments/assets/6d9becf2-1f23-45b0-9cd8-0ba06e32db60)

#### 2.DC Analysis Output

![Screenshot 2025-03-23 101324](https://github.com/user-attachments/assets/04c262b9-6874-4305-a065-736c6a83431f)


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











