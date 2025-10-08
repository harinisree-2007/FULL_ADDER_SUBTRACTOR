# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**

**Output Timing Waveform**

**Result:**


logic diagram for full adder :
<img width="646" height="311" alt="Screenshot 2025-10-08 132448" src="https://github.com/user-attachments/assets/e5597b91-4a63-4246-9b0a-b758a8e5fbb5" />



state diagram for full adder:


<img width="1918" height="252" alt="Screenshot 2025-10-08 132655" src="https://github.com/user-attachments/assets/510bcd8d-d74c-446f-8498-31866b2d30be" />


logic diagram for full subtractor:

<img width="862" height="383" alt="Screenshot 2025-10-08 134214" src="https://github.com/user-attachments/assets/076c02e2-7b81-4168-8c77-c4aa9967db64" />



State diagram for full subtractor :


<img width="1911" height="242" alt="Screenshot 2025-10-08 134400" src="https://github.com/user-attachments/assets/c50a1c6d-eab9-46f2-8f48-1504d2056faf" />


Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



