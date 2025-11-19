# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean function minimization is the process of simplifying complex Boolean expressions to their most efficient form while preserving their logical function. The goal is to reduce the number of logic gates, literals, and wiring needed for implementation in digital circuits, leading to lower costs, improved speed, and reduced power consumption.

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule 

Developed by: Vinodharani RegisterNumber:25015399


**RTL realization**


**Output:**


**RTL**
![WhatsApp Image 2025-11-17 at 15 03 31_d7e9f368](https://github.com/user-attachments/assets/b1ae28c6-8b8b-4f27-8cf5-3e5fa00a4632)



**Timing Diagram**

![WhatsApp Image 2025-11-17 at 15 03 13_8ee8dea3](https://github.com/user-attachments/assets/44db2f2a-e9d6-469a-8a29-2fcdc2ba8ce8)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

