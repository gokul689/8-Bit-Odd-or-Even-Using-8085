# 8-Bit-Odd-or-Even-Using-8085
# Name: GOKUL PRASAD H 
# Register No: 212224050011

## Aim:
To write an 8085 microprocessor program to check whether a given 8-bit number is odd or even.

## Apparatus Required:
•	Laptop with an internet connection

## Algorithm:
1.	Load the number from a specified memory location into register A.
2.	Perform an AND operation with 01H to check the least significant bit (LSB).
3.	If the result is 0, the number is even; otherwise, it is odd.
4.	Store the result in a specific memory location (odd or even flag).


## Program:
LDA 4200H
ANI 01H
JZ L1
MVI A,01H
JMP L2
L1:MVI A,02H
L2:STA 4201H
HLT


## Output:
# ODD: <BR>
<img width="1847" height="1003" alt="Screenshot 2026-02-06 084441" src="https://github.com/user-attachments/assets/d85c251a-cccd-499a-a520-35a26c77678d" />

# EVEN: <BR>
<img width="1845" height="1007" alt="Screenshot 2026-02-06 084507" src="https://github.com/user-attachments/assets/d55c23e7-0ffb-4aa8-9007-88c2526eac6c" />

# STEPS: <BR>

# ODD:<BR>
![WhatsApp Image 2026-02-06 at 9 39 05 AM](https://github.com/user-attachments/assets/76aa0659-74e1-4c5c-bf17-a35cde42ed3a) <BR>

![WhatsApp Image 2026-02-06 at 9 39 14 AM](https://github.com/user-attachments/assets/61fe1ee8-af66-4108-a400-7eb184ceb394) <BR>

# EVEN:<BR>
![WhatsApp Image 2026-02-06 at 9 39 21 AM](https://github.com/user-attachments/assets/0e54ab83-2c27-4d31-9922-0670012b83f2) <BR>


![WhatsApp Image 2026-02-06 at 9 38 34 AM](https://github.com/user-attachments/assets/414730e1-7d07-4d39-a2f3-cfdf27c10e7a) <BR>


## Result:
The 8085 microprocessor successfully checks whether a given number is odd or even and stores the result in memory.

