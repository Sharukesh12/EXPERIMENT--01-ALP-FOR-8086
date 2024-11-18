# EXPERIMENT--01-ALP-FOR-8086
Name : SHARUKESH T
Roll no : 2305002022
Date of experiment : 





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
MOV AL,2H
MOV BL,26H
ADD AL,BL
HLT


## Output  
 ![add](https://github.com/user-attachments/assets/b2ea83e3-c5a7-4bea-8fab-d2922be7e50d)

## Subtraction   of 8 bit numbers  ALP 
MOV AL,2H
MOV BL,26H
SUB AL,BL
HLT
## Output
![sub](https://github.com/user-attachments/assets/41e1964c-c0a4-439d-a2d2-0e6ed6cc4fc2)

## Multiplication alp
MOV AL,75H
MOV BL,32H
MUL BL
HLT
 ## Output  
![mul](https://github.com/user-attachments/assets/adc370f2-4221-40c0-b6fa-3ac4adbaf0e0)


## Division alp 
MOV AL,68H
MOV BL,18H
DIV BL
HLT
## Output  
![DIV](https://github.com/user-attachments/assets/3cda3475-fa98-45c0-98a6-3db725dc06b2)

## AND alp
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
## Output
![AND](https://github.com/user-attachments/assets/2d106ae5-b6ce-4d91-bd47-dcdcda5fbc7c)

## OR alp
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT

## output 
![OR](https://github.com/user-attachments/assets/45239d5c-265a-40ff-beea-e85abb91375a)

## NOT alp
MOV AL,65H
NOT AL
HLT

## output
![NOT](https://github.com/user-attachments/assets/f64bd068-e36c-4619-a7ad-a818049ce29c)
## XOR alp
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT

## output

![xor](https://github.com/user-attachments/assets/4257b4c0-de27-40d2-a11c-aaf7f90d1939)

## Result :
Thus to Write and execute ALP on fundamental arithmetic and logical operations are verified
successfully.

 








