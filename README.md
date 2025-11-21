# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
<img width="1069" height="583" alt="Screenshot 2025-11-21 181521" src="https://github.com/user-attachments/assets/94a65921-fa95-45c0-8cc6-186d5fbfa49f" />
<img width="1067" height="583" alt="Screenshot 2025-11-21 182857" src="https://github.com/user-attachments/assets/d35d07f0-c78e-4ac3-9f06-57f734ce9fd9" />



Developed by:Piruthiviraj.G RegisterNumber:25016420

**RTL Schematic**
<img width="1599" height="818" alt="Screenshot 2025-11-21 181458" src="https://github.com/user-attachments/assets/31b1e62a-09cc-4433-96b2-df712f5dbb69" />


<img width="1604" height="831" alt="Screenshot 2025-11-21 182834" src="https://github.com/user-attachments/assets/7c0fc7b3-dc07-4611-bfa8-065f43941a56" />



**Output/TIMING Waveform**

<img width="1148" height="882" alt="Screenshot 2025-11-21 182501" src="https://github.com/user-attachments/assets/28ff8cd7-3d5b-4c70-beb3-ca6a51f03ab7" />
<img width="1144" height="763" alt="Screenshot 2025-11-21 183849" src="https://github.com/user-attachments/assets/1c62ab37-cd4d-455e-95b6-b82613c9f9cb" />



**Result:**
Thus we obtain Half_Adder and Half_Subractor.
