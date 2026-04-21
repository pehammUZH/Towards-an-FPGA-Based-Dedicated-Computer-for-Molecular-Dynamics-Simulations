# Towards-an-FPGA-Based-Dedicated-Computer-for-Molecular-Dynamics-Simulations

Version 2.0

Code for an FPGA based dedicated computer for molecular dynamics simulations. 
For a detailed description, see TechnicalNotesV2.pdf.

FPGA.zip: Vivado project MD1.xpr as well as all Verilog files. Runs in Vivado

HostComputer.zip: Visual Studio C++ project of two program running on the host
computer that control the FPGA cluster. It also contains the parameter and 
topology files for the villin headpiece demonstration project.

villin.mp4: Movie of a short MD trajectory of villin headpiece, generated on the 
FPGA cluster 

PCB.zip: Printed Circuit Board used to set the IP of a node with the the help of 
a DIP switch, as well as to connect all nodes for synchronisation. Open in Eagle.

For technical questions (which I'm sure will appear), please contact the author 
(peter.hamm@chem.uzh.ch) 
