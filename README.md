# EX.-NO-2-D-IMPLEMENTATION-OF-MD5

## AIM:
  To write a program to implement the MD5 hashing technique.
## ALGORITHM:
  
  STEP-1: Read the 128-bit plain text.
  
  STEP-2: Divide into four blocks of 32-bits named as A, B, C and D.
  
  STEP-3: Compute the functions f, g, h and i with operations such as, rotations, permutations, etc,.
  
  STEP-4: The output of these functions are combined together as F and performed circular shifting and then given to key round.
  
  STEP-5: Finally, right shift of ‘s’ times are performed and the results are combined together to produce the final output.
  
## PROGRAM:
```
#Code to demonstrate the MD5

import hashlib

# function 
result = hashlib.md5(b'GeeksforGeeks')

# printing the equivalent byte value.
print("The byte equivalent of hash is : ", end ="")
print(result.digest())

```
## OUTPUT:
![image](https://github.com/Chandramouli1402/EX.-NO-2-D-IMPLEMENTATION-OF-MD5/assets/113716783/f7198acc-662a-4f35-9d38-2c1cd401cbac)


## RESULT:
  Thus the implementation of MD5 hashing algorithm had been implemented successfully using C.
