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

module exp2(a,b,c,d,w,x,y,z,f1,f2);

input a,b,c,d,w,x,y,z;

output f1,f2;

assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));

assign f2=((~y&z)|(x&y)|(w&y));

endmodule

Developed by:supriya S J 
RegisterNumber:*/ 24001109


**RTL realization**
![WhatsApp Image 2024-12-08 at 4 46 17 PM (1)](https://github.com/user-attachments/assets/ccee97b3-43bd-4154-a3ab-962f572e1f40)

**Output:**

**RTL**

**Timing Diagram**
![WhatsApp Image 2024-12-08 at 4 46 17 PM](https://github.com/user-attachments/assets/fae2cf77-d6f8-4e79-bef4-85ae015445a3)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

