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

<img width="369" height="167" alt="Screenshot 2025-11-21 225155" src="https://github.com/user-attachments/assets/ae2e1f32-f6b9-4bbf-b7f6-3c362bd75da5" />

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 <img width="396" height="133" alt="Screenshot 2025-11-21 225751" src="https://github.com/user-attachments/assets/dbb56332-b20c-42b3-adda-a66001a56ca9" />

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Half adder


<img width="635" height="172" alt="Screenshot 2025-11-22 192013" src="https://github.com/user-attachments/assets/b4ebac6c-2b31-4170-a503-a0593f623249" />


Half subracter


<img width="639" height="177" alt="Screenshot 2025-11-22 192118" src="https://github.com/user-attachments/assets/25cc74b6-0b8e-451d-9e97-edd9e9c87534" />


/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/

**RTL Schematic**

**Output/TIMING Waveform**

**Result:**

Half adder

<img width="1919" height="1020" alt="Screenshot 2025-11-21 225403" src="https://github.com/user-attachments/assets/b2fe53f0-39f3-4557-b52a-b5eb82ea30d5" />


Half subracter

<img width="1915" height="1019" alt="Screenshot 2025-11-21 225934" src="https://github.com/user-attachments/assets/857752fe-5649-4272-87f3-3fa0f0b8c947" />





