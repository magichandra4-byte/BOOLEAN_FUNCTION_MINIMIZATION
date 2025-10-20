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

Developed by:vedha.M
RegisterNumber:*/25012201
MINIMIZATION OF BOOLEAN FUNCTION
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b &d)|(a &b & ~c));
endmodule


ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|(w & y)|(x & y));
endmodule

**RTL realization**
![WhatsApp Image 2025-10-10 at 10 44 06_27c9e0d8](https://github.com/user-attachments/assets/c727f02a-9ce7-49cc-8307-9c16a9ccbdba)
![WhatsApp Image 2025-10-10 at 10 44 01_723b0337](https://github.com/user-attachments/assets/62580343-d918-433b-99d7-f2f0b7fa40bc)

**Output:**

**RTL**

**Timing Diagram**
![WhatsApp Image 2025-10-10 at 10 44 03_64be3cce](https://github.com/user-attachments/assets/44dfbd5a-1f2a-4fb4-8459-b411e2269064)
![WhatsApp Image 2025-10-10 at 10 44 07_535db388](https://github.com/user-attachments/assets/1cd83fd2-0642-471d-85a9-ad20e25a8eee)

**Result:**
Thus the given logic functions are implemented using and their operations are verified using verilog programming.



