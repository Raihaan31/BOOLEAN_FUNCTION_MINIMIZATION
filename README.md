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
~~~
**Program:**
EXPERIMENT 2:
i)
module EXPERIMENT2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module EXP2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: R Raihaan ahmed
RegisterNumber:24010543
~~~

**RTL realization**
![Screenshot 2024-12-02 212131](https://github.com/user-attachments/assets/d6adaf36-45cc-4c25-acd4-fcc3bd9641b5)
![Screenshot 2024-12-02 212819](https://github.com/user-attachments/assets/3c44c29e-dd65-4489-b96f-07b780deefb3)
**WAVEFORM**
![Screenshot 2024-12-02 212329](https://github.com/user-attachments/assets/da2c9c17-de69-4cad-800e-244cad229cca)
![Screenshot 2024-12-02 213238](https://github.com/user-attachments/assets/00df5822-85ab-484a-ace3-4024e0240122)
**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
