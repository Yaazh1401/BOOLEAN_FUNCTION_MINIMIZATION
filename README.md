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
```
1)
module logic_function(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a&b&d)|(a&b&~c));
endmodule
```
```
2)
module EXP2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:YAAZHINI .S
RegisterNumber:212224230308

**TRUTH TABLE**
![EXP2(1)](https://github.com/user-attachments/assets/cd2eafbd-9d6a-4cdd-9fbd-28162fa961d1)
![EXP2(2)](https://github.com/user-attachments/assets/837d0156-7551-47b8-aace-967457fbc8f8)

**RTL realization**
![EXP2(1)](https://github.com/user-attachments/assets/c924e5c4-2a5a-436e-8395-bfdeda5a7b19)
![EXP2(2)](https://github.com/user-attachments/assets/6d4beac0-6cf4-4778-9254-35f64943f952)


**RTL**
![EXP2(1)](https://github.com/user-attachments/assets/089c217e-b6f9-4783-b988-3da445383a2b)
![EXP2(2)](https://github.com/user-attachments/assets/0f956811-da98-43f1-aeea-9a58eea683db)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

