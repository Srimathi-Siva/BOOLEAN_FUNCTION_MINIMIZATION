# BOOLEAN_FUNCTION_MINIMIZATION

## AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

## Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

## Software – Quartus prime

## Theory

## Logic Diagram

## Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## Program:

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
### module funct1(a,b,c,d,f1);
### input a,b,c,d;
### output f1;
### assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
### endmodule

### module funct2(w,x,y,z,f2);
### input w,x,y,z;
### output f2;
### assign f2=((~y&z)|(w&y)|(x&y));
### endmodule

Developed by:SRI MATHI S

RegisterNumber:24004689


## RTL realization

## Output:

![image](https://github.com/user-attachments/assets/4e782bc0-8398-4ffe-97e1-6e0c22a892c2)

![image](https://github.com/user-attachments/assets/f5b4d100-a5d8-4756-bfeb-f04a73f88039)



## RTL

## Timing Diagram

![image](https://github.com/user-attachments/assets/ca1c5e89-e93f-4e71-83d5-808c13e091b5)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

