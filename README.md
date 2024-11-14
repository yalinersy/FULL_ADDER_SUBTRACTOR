### NAME : SRIYALINE R
### REGNO : 24006194
# EXPERIMENT 4 : FULL ADDER AND SUBTRACTOR

# AIM

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENT REQIURED

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# FULL ADDER AND SUBTRACTOR 

# FULL ADDER

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

# FULL SUBTRACTOR

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# TRUTHTABLE
![WhatsApp Image 2024-11-14 at 1 59 31 PM](https://github.com/user-attachments/assets/cbae836e-9d64-4cb8-ba09-5047f2a87c91)

# PROCEDURE

 1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram.

# PROGRAM
![Screenshot 2024-11-14 134242](https://github.com/user-attachments/assets/921895f2-ddd0-48f3-a168-1ff698e8c058)

# RTL OUTPUT
![Screenshot 2024-11-14 134259](https://github.com/user-attachments/assets/d5b3d4cc-be73-483d-a234-f9f3f2dfa8f6)

# OUTPUT WAVEFORM
![Screenshot 2024-11-14 135116](https://github.com/user-attachments/assets/9f4c23f1-58d2-4ef0-9ebd-29a9af1cf351)

# RESULT

Half adder and subtractor circuit is studied and its truth table is verified in Quartus using Verilog programming.


