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
FULL ADDER :

![image](https://github.com/swathisiva212/FULL_ADDER_SUBTRACTOR/assets/155249892/f00971bd-64e8-42a8-9695-47ce0062c858)

FULL SUBTRACTOR :

![image](https://github.com/swathisiva212/FULL_ADDER_SUBTRACTOR/assets/155249892/b7349761-eb26-465b-8b7c-c11548e93e47)

**Procedure**


**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: swathi.s RegisterNumber:212223040219
*/

## Full_adder

![image](https://github.com/swathisiva212/FULL_ADDER_SUBTRACTOR/assets/155249892/3f08402f-4914-46fd-8389-1bee6c532743)

 FULL SUBTACTOR:

![image](https://github.com/swathisiva212/FULL_ADDER_SUBTRACTOR/assets/155249892/b758b1b1-839d-4a11-a4ce-80b4138e8343)


**RTL Schematic**
 FULL ADDER:

![image](https://github.com/swathisiva212/FULL_ADDER_SUBTRACTOR/assets/155249892/3d47a91c-ed04-44d4-a785-f09eeb8ca50e)

FULL SUBTRACTOR:

![image](https://github.com/swathisiva212/FULL_ADDER_SUBTRACTOR/assets/155249892/e40e8c59-f972-4202-ac06-cae6b2018738)


**Output Timing Waveform**

![image](https://github.com/swathisiva212/FULL_ADDER_SUBTRACTOR/assets/155249892/58810d63-f307-435c-a069-f2a0361018de)

![image](https://github.com/swathisiva212/FULL_ADDER_SUBTRACTOR/assets/155249892/784ada33-1cfd-4d3e-8205-43f644df99af)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



