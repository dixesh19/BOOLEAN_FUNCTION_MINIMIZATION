# DINESH R

# 212224240037

# EXP.NO:2 IMPLEMENTATION OF BOOLEAN FUNCTION





**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
A Boolean function consists of a number of Boolean variables joined by the Boolean connectives AND and OR. 

For example. f ( A , B , C , D ) = A B C ¯ + C D + B ¯ or g ( A , B , C , D ) = ( A + B + C ) ( C ¯ + D ¯ ) ( A + B )

The implementation of Boolean functions by using logic gates involves connecting output of one logic gate to the input of another gate. 
Commonly used Logic Gates are: AND, OR, NAND and NOR gates.





**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
![Screenshot 2025-03-20 105528](https://github.com/user-attachments/assets/9c34e67b-1915-4e7e-b72b-d537223dd60a)



**Truth table**

![rsz_11whatsapp_image_2025-03-20_at_112003_a23787ed](https://github.com/user-attachments/assets/8497b0db-0a93-4cb3-aa45-c2d21e97025d)

![rsz_1whatsapp_image_2025-03-20_at_112003_a23787ed](https://github.com/user-attachments/assets/a7616bf1-25ab-4471-bce5-5c16620ad0fe)





**RTL realization**

![Screenshot 2025-03-20 105552](https://github.com/user-attachments/assets/4b4e48b5-7732-42f6-b0aa-3c36fe31c14d)


**Timing diagram**

![Screenshot 2025-03-20 110545](https://github.com/user-attachments/assets/7a25096a-8fa6-42ab-9071-395efcd94db8)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

