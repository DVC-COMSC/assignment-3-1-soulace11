[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-f4981d0f882b2a3f0472912d15f9806d57e124e0fc890972558857b51b24a6f9.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=10512821)
<!--
[Link to Chap 5 Lab18](https://docs.google.com/presentation/d/1r3h2R9JwK9HK_U2Ia-zncL0BSjHV6Giu6ugNJ6yZpgc/edit#slide=id.g1715447b552_0_27)

![Lab 16](https://nimbus-screenshots.s3.amazonaws.com/s/e634571b38c8923031df60fc7fc2fe3f.png)
-->

## Complete the "main.py"
num1 = int(input('Enter first number: '))
num2 = int(input('Enter second number: '))
num3 = int(input('Enter third number: '))

if(num1>num2) and (num1>num3):
  smallest = num1

elif (num2>num1) and (num2>num3):
  smallest = num1 

else:
  smallest = num1

  print("smallest number is", smallest)