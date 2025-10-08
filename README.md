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
module boolean_function (
   input wire A,
	input wire B,
	input wire C,
	input wire D,
	output wire F
);

  assign F=(~A & B)|(C & D)|(A & ~D);
  
endmodule
	

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**

**Output:**
<img width="1533" height="831" alt="Screenshot 2025-10-06 113527" src="https://github.com/user-attachments/assets/75aea768-a94e-444e-aae5-2f4909ba176e" />


**RTL**

**Timing Diagram**

**Result:**
<img width="1157" height="279" alt="Screenshot 2025-10-06 114933" src="https://github.com/user-attachments/assets/40d1f166-7f7f-44ef-965a-2f4321bc307a" />


Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

