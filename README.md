register no : 212224040289

name :  sanjeevpriya k
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
![Screenshot 2025-04-15 113650](https://github.com/user-attachments/assets/8a6ad51b-ba4e-4508-90c9-4c6879ba291f)

![Screenshot 2025-04-15 113707](https://github.com/user-attachments/assets/0469bf3d-8dcc-4b7e-9686-2475703b53a4)


**Program:**

![Screenshot 2025-04-15 110446](https://github.com/user-attachments/assets/6cc705c0-9912-4c6b-8b6e-671b3027b443)



**RTL Schematic**

![Screenshot 2025-04-15 110031](https://github.com/user-attachments/assets/686000aa-cef7-4727-8515-bc07fe368871)


**Output Timing Waveform**

![Screenshot 2025-04-15 111144](https://github.com/user-attachments/assets/ce93fc86-4fe9-4683-b557-73a184ae70ee)


**Result:**

Thus the Full Adder and Full Subtractor circuits and the truth tables is verified using Quartus software.



