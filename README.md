# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![theory](https://github.com/user-attachments/assets/30556257-00f1-4661-a317-3b36c74d40bd)

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
Developed by: S KANUSHA SREE 
RegisterNumber:24001268
```
```
module exp2f1(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
*/


**RTL realization**


**Output:**

**RTL**
![exp2f1](https://github.com/user-attachments/assets/f891db0a-0b96-49d1-9b8e-3812808e78b1)


**Timing Diagram**
![Screenshot 2024-11-29 103644](https://github.com/user-attachments/assets/37c248a8-dd0d-4390-8b52-495ac953cf08)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

