## Aim:
To write an 8085 microprocessor program to check whether a given 8-bit number is odd or even.
## Apparatus Required:
Laptop with an internet connection
## Algorithm:
1.	Load the number from a specified memory location into register A.
2.	Perform an AND operation with 01H to check the least significant bit (LSB).
3.	If the result is 0, the number is even; otherwise, it is odd.
4.	Store the result in a specific memory location (odd or even flag).
## Program:
IN 00H<br>
ANI 01H<br>
JZ EVEN<br>
MVI A,01H<br>
OUT 01H<br>
HLT<br>
EVEN: MVI A,00H<br>
OUT 01H<br>
HLT
## Output:
<img width="1823" height="804" alt="image" src="https://github.com/user-attachments/assets/c6025b0a-8105-4716-be80-ea15013c42b9" />

## Result:
The 8085 microprocessor successfully checks whether a given number is odd or even and stores the result in memory.


