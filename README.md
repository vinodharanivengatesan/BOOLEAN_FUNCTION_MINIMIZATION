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


**Program:

module DAY5(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
assign f2=((~y & z)|( w & y )|(x & y));
endmodule



**RTL realization**

**Output:**

**RTL**


![WhatsApp Image 2025-11-17 at 15 03 31_21c9b2fa](https://github.com/user-attachments/assets/19661a2a-cbbb-4730-bb87-098983049dd9)


**Timing Diagram**


![WhatsApp Image 2025-11-17 at 15 03 13_e72f01ca](https://github.com/user-attachments/assets/18ae557a-779c-422f-8dcf-d700b3710439)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

