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

Developed by: JAYANTH S S

RegisterNumber: 212224050014

*2a*
~~~
module ex2a(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~a&b&d)|(~b&~d)|(a&b&~c));
endmodule
~~~

*2b*

~~~
module ex2b(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
~~~

**Output:**

*2a*

![430845399-afb62b53-039a-4224-a156-5eb6b1e97b16](https://github.com/user-attachments/assets/2b3736a4-d1d8-4672-9a08-01d2f413b0e1)

*2b*

![430845402-c4c0e693-103f-4f3c-a8d9-c1890fe268b0](https://github.com/user-attachments/assets/525d0d7e-fff1-4826-a0e9-341ac251c548)

**RTL realization**

*2a*

![430838687-dc7c5eb9-90c5-48f2-93bb-f6f47d1f1d3d](https://github.com/user-attachments/assets/38a89994-b6e6-4c0f-9010-2caad4679577)

*2b*

![430838888-549837b3-336d-4aca-ba44-2d531db537c8](https://github.com/user-attachments/assets/81641181-f94f-4483-827f-3da3ba21d060)

**RTL**

*2a*

![430839242-bcf8bc32-2423-4b37-9d47-86e01d398fcb](https://github.com/user-attachments/assets/abb4592d-0c72-4887-aff1-47dfa056878d)

*2b*

![430839449-e5cf7e3b-0189-4aaf-8b16-1bd6f151e7c1](https://github.com/user-attachments/assets/aa9d9b21-b298-4809-813e-c960dca016a0)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

