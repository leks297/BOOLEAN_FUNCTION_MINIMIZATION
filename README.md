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
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule

Developed by: RegisterNumber:*/


**RTL realization**

**Output:**
<img width="1417" height="789" alt="Screenshot 2025-10-08 195351" src="https://github.com/user-attachments/assets/18ea5a15-5b9b-4b53-9cc9-685ba2955f1b" />

**RTL**

**Timing Diagram**

**Result:**
<img width="1297" height="866" alt="image" src="https://github.com/user-attachments/assets/97a1c590-4bdd-418f-a719-0a4c619dd7b2" />

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

