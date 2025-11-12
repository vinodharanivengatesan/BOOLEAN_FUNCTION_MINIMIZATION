# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

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
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/d46749a9-3b00-4cb4-8e89-3d4313e65439" />


**Output:**
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/8bfae320-dd44-4b58-84ff-a548d1d68448" />


**RTL**
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/0cc889cd-4051-4023-a872-30eb52255c57" />


**Timing Diagram**
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/10f0bc9c-e3df-46f8-b811-9e59a72c7f43" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

