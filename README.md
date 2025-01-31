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
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)|(a&b&~c) );
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: KIRTHICK SHA R RegisterNumber: 24900676


**RTL realization**
![exp_2](https://github.com/user-attachments/assets/1a605983-3054-4163-84c4-bd5106cf219d)

**Timing Diagram**
![Screenshot 2024-10-29 113728](https://github.com/user-attachments/assets/20d0bb71-fc21-4f6e-b36c-a87fb6ce59f6)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

