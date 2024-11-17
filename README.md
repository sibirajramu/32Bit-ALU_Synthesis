# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :

![WhatsApp Image 2024-11-17 at 11 59 05_3fea45a9](https://github.com/user-attachments/assets/5fa319de-532e-4b49-914d-fcd7d437d716)

#### Area report:

![WhatsApp Image 2024-11-17 at 11 59 12_37a68fe1](https://github.com/user-attachments/assets/3a8dbb0f-7c26-408e-92da-23547eba4d7c)

<br>
<br>
<br>
<br>

#### Power Report:

![WhatsApp Image 2024-11-17 at 11 59 17_1e5f27e0](https://github.com/user-attachments/assets/36119170-3f85-4ea9-89d6-35cfb9793679)

<br>
<br>

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
