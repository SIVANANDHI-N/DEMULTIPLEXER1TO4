# DEMULTIPLEXER1TO4
# Aim

To simulate and synthesis demultiplexer using vivado.

# Apparatus Required

vivado 2023.2 software.

# Procedure

STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

# Program
module demux(s,I,y );

input I;

input [1:0]s;

output [3:0]y;

assign y[0] = ~s[1]&~s[0]&I;

assign y[1] = ~s[1]&s[0]&I;

assign y[2] = s[1]&~s[0]&I;

assign y[3] = s[1]&s[0]&I;

endmodule

![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/b6d81e6c-81ec-4f91-ae42-832a68f8facc)
# Truth Table
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/bb0a83c7-b4f3-463b-b422-f2ff65b1a0ee)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/dcd56444-97dd-454b-bddf-c7472c4af1de)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/03fbbbdf-8ae3-4653-8047-7d4cbf555ccb)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/f48cc07d-c76f-4d1c-8907-11e99711b751)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/a3075cf9-55ba-4478-b20c-c7128badef04)
![image](https://github.com/RESMIRNAIR/DEMULTIPLEXER1TO4/assets/154305926/e07386db-69b3-4a5f-945f-b38929b801ea)
# Output
![image](https://github.com/SIVANANDHI-N/DEMULTIPLEXER1TO4/assets/162731951/e969b7c3-532c-4e22-b0e7-ec8611a69749)
# Result
Thus the simulate and synthesis of DEMULTIPLEXER 1 TO 4 is verified successfully by using Vivado software.



