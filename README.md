#Binhexa Challenge Writeup
- This challenge helps us understand how to use binary calculations.
- It comprises of the following operations: '+', '*', 'AND', 'OR', 'left shift <<', 'right shift >>'
---




#Challenge Description
- How well can you perfom basic binary operations? Additional details will be available after launching your challenge instance.
---



#Environment
- Host Machine: Windows 10 with Oracle VirtualBox
- Guest: Ubuntu 20.04 LTS (CLI-based)
- Access: SSH via PuTTY
---



#Steps Taken
- Logged into the picoctf game server
- Performed the six binary operations in the game.
- Converted the last result from binary to hex and found the flag.
---



#Lessons learned
- left shift (<<) by 1bit -- Only added 0 to the right

- right shift (<<) by 1bit--  Removed rightmost bit and added 0 to the left

- AND (&) -- Returns 1 only if BOTH corresponding bits are 1. Otherwise return 0

- OR (|) -- Returns one if at least ONE of the corresponding bits is 1. Otherwise return 0

- Multiplication -- multiply the top bits with each bottom bit one by one. After multiplying, left shift the numbers then add.
 
- Addition (+) -- adds corresponding bits from right to left. Bits higher than 1 are carried over to the next bit column
--- 




#Why binary operations?
- Computers use binary operations to process information (in 1s and 0s)
- Knowing binary operations helps us understand the decision making process of a computer.
- It is a crucial skill that can enforce data safety and threat detection.
---



#Flag
- picoCTF{[REDACTED]}



---
