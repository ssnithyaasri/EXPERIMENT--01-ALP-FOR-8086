# EXPERIMENT--01-ALP-FOR-8086


Name :NITHYAA SRI S S

Roll no :212222230100

Date of experiment :13/08/2024





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
```
MOV AX,78H;
MOV BX,69H;
ADD AX,BX
HLT
```
## Output  

![ex1 1](https://github.com/user-attachments/assets/b455a786-410f-4d00-b8b3-aca976e6936e)
![ex1 2](https://github.com/user-attachments/assets/0ed9fccb-35c6-47db-92bf-50731e0551f3)
![ex1 3](https://github.com/user-attachments/assets/ea9e2edf-8cd4-4a10-98c5-88d40330cb11)



 
## Subtraction   of 8 bit numbers  ALP 
```
MOV AL,68H;
MOV BL,33H;
SUB AL,BL
HLT

```
 
## Output 
![ex1 4](https://github.com/user-attachments/assets/66c41003-389a-4e92-a287-cf6d0fbf449e)
![ex1 5](https://github.com/user-attachments/assets/c6a1acfe-4e86-4253-b142-f97fd5ef2604)
![ex1 6](https://github.com/user-attachments/assets/1b5afe0f-c578-42e4-afb2-5ad1771791f2)



## Multiplication alp 
```
MOV AL,75H;
MOVE BL,12H;
MUL BL
HLT
```
 ## Output
![EX1 7](https://github.com/user-attachments/assets/9c31162d-d00e-4b5b-9b9c-0a0b0034c617)
![ex1 8](https://github.com/user-attachments/assets/38fae50b-307b-473d-8444-67409787dcf1)
![ex1 9](https://github.com/user-attachments/assets/b720225f-7d76-47f3-894d-8a4ea06309bc)



## Division alp 
```
MOV AL,65H;
MOV BL,15H;
DIV BL
HLT
```

## Output  
![ex 1 10](https://github.com/user-attachments/assets/5e8adbfc-2993-4f83-a47a-217c04e0a443)
![ex1 11](https://github.com/user-attachments/assets/5558e91a-9075-4b6e-8a44-04bc3dd0157c)

![ex1 12](https://github.com/user-attachments/assets/c0e3f7ec-d8c6-4169-abea-a0d3eef1c4ba)



## Result :
Thus the ALP on fundamental arithmetic and logical operations is written and executed successfully.
 








