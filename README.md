# EXPERIMENT--01-ALP-FOR-8086
Name : B.BARKAVI



Roll no 212224110011



Date of experiment : 04.02.2026






## Aim: 


To Write and execute ALP on fundamental arithmetic and logical operations


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
org 100h
MOV AL, 25H
MOV BL, 15H
ADD AL, BL
MOV [5000H], AL
HLT
```

## Output  

<img width="1915" height="1135" alt="Screenshot 2026-02-04 211115" src="https://github.com/user-attachments/assets/bba89e9d-add2-4e1d-be63-3f0b3034a349" />

 
## Subtraction   of 8 bit numbers  ALP 
```
 org 100h
MOV AL, 40H
MOV BL, 18H
SUB AL, BL
MOV [5001H], AL
HLT
```
## Output  
<img width="1913" height="1171" alt="Screenshot 2026-02-04 211242" src="https://github.com/user-attachments/assets/f4b3ad3f-a077-4715-8a7e-b4122d3d63c5" />


## Multiplication alp 
```

org 100h
MOV AL, 06H
MOV BL, 04H
MUL BL
MOV [5002H], AX
HLT
```

 ## Output  

<img width="1898" height="1128" alt="Screenshot 2026-02-04 211446" src="https://github.com/user-attachments/assets/23880353-5727-4458-9988-9de026899a55" />


## Division alp 
```
org 100h
MOV AX, 0024H
MOV BL, 06H
DIV BL
MOV [5004H], AL
MOV [5005H], AH
HLT
```

## Output  
<img width="1892" height="1116" alt="Screenshot 2026-02-04 211554" src="https://github.com/user-attachments/assets/543b0340-ad5e-433b-9c04-4fc59686f0aa" />

# AND ap
```
org 100h

MOV AL, 5AH
MOV BL, 3CH
AND AL, BL
MOV [5000H], AL

HLT
```
## Output
<img width="1910" height="1148" alt="Screenshot 2026-02-04 211703" src="https://github.com/user-attachments/assets/274016ab-9c3c-4e78-80fb-0229d34284b2" />

# OR ap
```

org 100h
MOV AL, 5AH
MOV BL, 3CH
OR AL, BL
MOV [5001H], AH
HLT

```

## Output
<img width="1890" height="1176" alt="Screenshot 2026-02-04 211846" src="https://github.com/user-attachments/assets/8034c4a1-2603-47f7-9168-fa963280fe81" />


# XOR ap
```
org 100h
MOV AL, 5AH
MOV BL, 3CH
XOR AL, BL
MOV [5002H], AL
HLT

```
## Output
<img width="1919" height="1094" alt="Screenshot 2026-02-04 211930" src="https://github.com/user-attachments/assets/1215d750-5e5f-459f-b0dc-2d8021e09b3a" />


# NOT ap
```
org 100h
MOV AL, 5AH
NOT AL
MOV [5003H], AL
HLT
```
## Output

<img width="1900" height="1183" alt="Screenshot 2026-02-04 212020" src="https://github.com/user-attachments/assets/f1e305fa-c468-46fc-8272-2e1ba9d856c3" />


## Result :
 

Thus the execution for ALP on fundamental arithmetic and logical operations in done on 8086 microprocessor.






