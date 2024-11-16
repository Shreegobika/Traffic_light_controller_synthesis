# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

## Synthesis RTL Schematic :
![image](https://github.com/user-attachments/assets/1fa294ca-1cfd-4263-9b4b-c01837ce3296)

## Area report:
![image](https://github.com/user-attachments/assets/43326795-2219-46cb-b7ee-9674addd4f8b)


## Power Report:
![image](https://github.com/user-attachments/assets/12956e37-f2a6-4a07-bd05-2a42631fd619)


## Result:
The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
