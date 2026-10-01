# Bases
Cylab CTF Bases

Q: What does this bDNhcm5fdGgzX3IwcDM1 mean? I think it has something to do with bases.

Hint: Submit your answer in our flag format. For example, if your answer was 'hello', you would submit 'academy{hello}' as the flag.

Step1: Open https://gchq.github.io/CyberChef/

Step 2: Put bDNhcm5fdGgzX3IwcDM1 in input

Step3: Put FromBase64 in receip

<img width="1585" height="781" alt="image" src="https://github.com/user-attachments/assets/9d2bcdd9-7810-4bf9-a289-bdc8b5847de0" />

Step4: Final answer: academy{l3arn_th3_r0p35}


How toBase64 works:

Hello <br>
  ↓ <br>
ASCII <br>
  ↓ <br>
72  101  108  108  111 <br>
  ↓ <br>
8-bit binary <br>
  ↓ <br>
01001000 01100101 01101100 01101100 01101111 <br>
  ↓ <br>
join <br>
  ↓ <br>
0100100001100101011011000110110001101111 <br>
  ↓ <br>
groups of 6 <br>
  ↓ <br>
010010 000110 010101 101100 011011 000110 111100 <br>
  ↓ <br>
decimal <br>
  ↓ <br>
18  6  21  44  27  6  60 <br>
  ↓ <br>
Base64 table <br>
  ↓ <br>
S   G   V   s   b   G   8 <br>
  ↓ <br>
padding <br>
  ↓ <br>
SGVsbG8= <br>

Reference:
For ASCII TABLE: https://www.ascii-code.com/

For Base64 table

<img width="623" height="457" alt="base64-encoding-and-decoding" src="https://github.com/user-attachments/assets/e83401d8-69f7-4c8d-b7a2-61b4047cf892" />

