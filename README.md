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
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule
```

Developed by:BHARGAVI S
RegisterNumber:25018916

**RTL realization**
<img width="503" height="489" alt="Screenshot 2026-05-11 114042" src="https://github.com/user-attachments/assets/d065b5e3-d3a9-4f9e-837e-e65cca8cf209" />

**Output:**

**RTL**
<img width="1306" height="643" alt="Screenshot 2026-05-11 125724" src="https://github.com/user-attachments/assets/a0f2f357-92cd-4109-897c-b410a71cf616" />



**Result:**
Thus, the given logic functions are implemented using and their operations are verified.
