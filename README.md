# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![Screenshot 2025-05-10 160454](https://github.com/user-attachments/assets/7a700f59-c4b4-4006-b791-0a4edf7d1e57)

![Screenshot 2025-05-10 160505](https://github.com/user-attachments/assets/4031c7a7-7c0f-4397-a936-ac4f90c4f402)

### Schematicand Symbol of 2-Input EX-OR Gate:

![Screenshot 2025-05-10 160515](https://github.com/user-attachments/assets/880ad1be-e8b3-4111-b2ea-2b2c7eb1fd14)

![Screenshot 2025-05-10 160523](https://github.com/user-attachments/assets/4230854b-5f8e-43d0-9875-258b457660e3)

### Schematicand Symbol of Half Adder:
![Screenshot 2025-05-10 160535](https://github.com/user-attachments/assets/5d98f983-d6b7-42b9-8f16-17407b2010b2)

![Screenshot 2025-05-10 161100](https://github.com/user-attachments/assets/bfaa7af0-6785-46e4-b434-87d677af5807)

### Schematic of 2-Bit Multiplier:
<img width="1919" height="1079" alt="Screenshot 2025-10-08 094538" src="https://github.com/user-attachments/assets/d218d74f-6a7f-4fba-8545-43ec45c2d07a" />


## Output
### Transient Analysis Output:
<img width="867" height="687" alt="Screenshot 2025-10-08 094523" src="https://github.com/user-attachments/assets/934d0bf3-ee4e-45d4-87f4-3b7b32ef70b4" />


<img width="515" height="663" alt="Screenshot 2025-10-08 094355" src="https://github.com/user-attachments/assets/949281ed-7076-49c1-b614-53f4d22f7eff" />



<img width="1917" height="1077" alt="Screenshot 2025-10-08 095030" src="https://github.com/user-attachments/assets/10896eb9-ad56-4b4a-b1d2-2c18902c1cb9" />


Run Time : 400ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
