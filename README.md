# BOOLEAN_FUNCTION_MINIMIZATION
### AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

### Theory

### Logic Diagram

### Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### Program:
### Developed by: VINISHRAJ R
###  Registered number : 212223230243
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 


```
module ex02(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d) | (a & b & ~c) | (~a & b & d));
endmodule
```
```
module ex02m1(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2= ((~y&z)|(w&y)|(x&y));
endmodule
```
### Logic Symbol & Truth Table 


![image](https://github.com/user-attachments/assets/7df010aa-4cf8-438a-bd30-5b79a220de04)


*F2*

![image](https://github.com/user-attachments/assets/2c174f66-6675-48ce-83c3-1e00840dcee1)





### RTL realization

*F1*
![image](https://github.com/user-attachments/assets/60325e75-36ff-4f90-a0d8-84bcd0e409ef)

*F2*
![image](https://github.com/user-attachments/assets/7bab203b-9fb1-4f25-8e13-e8bc0793c480)



### Output:
*F1*
![image](https://github.com/user-attachments/assets/eece18e2-aa74-489b-be5f-127fbe70b123)
)
*F2*
![image](https://github.com/user-attachments/assets/5e0e38d2-6393-45ff-9769-aef0cd01f068)


### Result:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

