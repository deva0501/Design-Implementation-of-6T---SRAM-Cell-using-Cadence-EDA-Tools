# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![Screenshot 2025-03-24 122239](https://github.com/user-attachments/assets/c22930fc-f396-4787-807d-51088ad7959e)


## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram:

 #### 1. Schematic of 6T SRAM Cell:

![WhatsApp Image 2025-03-28 at 14 09 27_0ec1d3ef](https://github.com/user-attachments/assets/b2038023-2cc2-43cb-92e0-20b3ba4be323)

 #### 2. transient response setup:
 
 ![WhatsApp Image 2025-03-28 at 14 13 16_bc3cd615](https://github.com/user-attachments/assets/18d91171-f3be-442b-a00f-287bcad8eeef)

 #### 3. Transient Analysis Output:
 
![WhatsApp Image 2025-03-28 at 14 09 26_ba2a120c](https://github.com/user-attachments/assets/97b2c8cf-ede0-47c3-a5c9-b9482b967a28)

#### 4. output:

![WhatsApp Image 2025-03-28 at 14 13 40_4acc119e](https://github.com/user-attachments/assets/ba1da4b5-db49-48ab-a86b-e7c3a44c0e85)

## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


