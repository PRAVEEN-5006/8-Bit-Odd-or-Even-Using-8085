# 8-Bit-Odd-or-Even-Using-8085
# Name: PRAVEEN P B
# Register No: 212224050032

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
```
LDA 4200H
ANI 01H
JZ L1
MVI A,01H
JMP L2
L1:MVI A,02H
L2:STA 4201H
HLT
```


## Output:
# ODD: <BR>
<img width="1847" height="1003" alt="Screenshot 2026-02-06 084441" src="https://github.com/user-attachments/assets/d85c251a-cccd-499a-a520-35a26c77678d" />

# EVEN: <BR>
<img width="1845" height="1007" alt="Screenshot 2026-02-06 084507" src="https://github.com/user-attachments/assets/d55c23e7-0ffb-4aa8-9007-88c2526eac6c" />

# STEPS: <BR>

<img width="1080" height="1567" alt="image" src="https://github.com/user-attachments/assets/325d84c9-c110-4251-84db-7e223adfa58b" />

<img width="1080" height="1588" alt="image" src="https://github.com/user-attachments/assets/96f57da3-2b8a-4ee1-9c4d-1dcc8a265f3e" />

<img width="1075" height="1600" alt="image" src="https://github.com/user-attachments/assets/37a7e1d2-b80b-4706-bc4d-c4f4f7811951" />

## Result:
The 8085 microprocessor successfully checks whether a given number is odd or even and stores the result in memory.



