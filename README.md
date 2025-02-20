# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure:
1. Using truth table construct the Half Subtractor and Full Subtractor.
2. Find Rtl logic and timing diagram for all flipflops.
3. End the program.




## Program:!

/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by: NIRAUNJANA GAYATHRI G R
RegisterNumber:  22008369

![image](https://user-images.githubusercontent.com/119395610/213846232-c30bb7ef-5510-4475-8aa7-7db68a8b2db6.png)

*/

## Output:
![image](https://user-images.githubusercontent.com/119395610/212460096-c81c845f-82ac-461f-abc9-c7fe3ad8bbd2.png)
![image](https://user-images.githubusercontent.com/119395610/212460108-e43c844a-ad62-450b-be3b-f3940444246c.png)





## Truthtable:
![image](https://user-images.githubusercontent.com/119395610/213479866-f5c7425e-02db-485b-be6d-6d0a6d70d906.png)
![image](https://user-images.githubusercontent.com/119395610/213479931-ce6358e7-9578-4ffa-af17-81464e770ac3.png)




##  RTL realization:
![image](https://user-images.githubusercontent.com/119395610/212460123-b9e2b571-62bf-4b7e-afd5-52ae2dae018b.png)![image](https://user-images.githubusercontent.com/119395610/212460143-f963e93d-229d-4486-9e86-37cbe4a74c05.png)






## Timing diagram :
![image](https://user-images.githubusercontent.com/119395610/212460157-bc71a553-85ba-4b8f-a094-faf4baf74a4c.png)
![image](https://user-images.githubusercontent.com/119395610/212460176-ec7c2def-a59e-423e-aa12-5ec3d52a26a7.png)




## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
