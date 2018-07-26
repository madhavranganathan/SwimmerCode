# SwimmerCode
C programs for amoeboid swimming
This repository consists of the program for running the swimmer codes. 

Important files:
1. vesicle3D.c : This is the main program. The rest of the files contain routines that are called during execution of this program. 

2. Makefile : This is the file that compiles and links the programs when the command "make" is used. 

3. param.h : This contains the parameters for running the program. Most of the parameters are explained. 

Procedure for execution:
1. Edit param.h for the required simulation conditions.
2. Compile the program using "make"
3. In case an input file is needed, you need to make sure it is in the directory of the executable "vescile3D". 
4. Execute using "vesicle3D".
5. Output files are directed to .vtk files which can be directly read using paraview. "vm.dat" contains average position and velocity of the swimmer as a function of time. 


For any queries, contact Madhav Ranganathan (madhavr@iitk.ac.in) or Alexander Farutin (alexandr.farutin@univ-grenoble-alpes.fr).
