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

Hello
  ↓
ASCII
  ↓
72  101  108  108  111
  ↓
8-bit binary
  ↓
01001000 01100101 01101100 01101100 01101111
  ↓
join
  ↓
0100100001100101011011000110110001101111
  ↓
groups of 6
  ↓
010010 000110 010101 101100 011011 000110 111100
  ↓
decimal
  ↓
18  6  21  44  27  6  60
  ↓
Base64 table
  ↓
S   G   V   s   b   G   8
  ↓
padding
  ↓
SGVsbG8=
