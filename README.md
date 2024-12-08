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

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:RAMASRI K

RegisterNumber:24007403


module digital2(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

module digital22(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule




**RTL realization**

![Screenshot 2024-12-08 185856](https://github.com/user-attachments/assets/92dabbcb-b475-40d8-a73f-53b542570a7a)

![Screenshot 2024-12-08 185906](https://github.com/user-attachments/assets/582b971e-3196-45fd-8629-e6797fcb4e12)


**Output:**

**RTL**

![Screenshot 2024-12-08 185917](https://github.com/user-attachments/assets/a1f362bc-2321-46f9-921e-33ad083f0894)

![Screenshot 2024-12-08 185926](https://github.com/user-attachments/assets/a9afb24c-eb3b-4d74-8c47-8525406c993a)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

