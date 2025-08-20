# EXPERIMENT--01-ALP-FOR-8086
Name :KISHORE K
Roll no 212223040101
Date of experiment : 20.08.2025





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
MOV AL, 53H;
MOV BL, 24H;
ADD AL,BL;
HLT
```
## Output  
 <img width="1920" height="1080" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/0f914f61-5620-45c6-8d0b-2ae305f368e5" />

## Subtraction   of 8 bit numbers  ALP 
```
 MOV AL, 53H;
MOV BL, 24H;
SUB AL,BL;
HLT
```
## Output  
<img width="1920" height="1080" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/110b8661-ebf2-4a7f-98a5-3acfa78aef48" />

## Multiplication alp 
```MOV AL, 53H;
MOV BL, 24H;
MUL BL;
HLT
```
 ## Output  
<img width="1920" height="1080" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/475bfb5f-7961-42f5-b453-5bc2614dfc20" />


## Division alp 
```
MOV AL, 53H;
MOV BL, 24H;
DIV BL;
HLT
```
## Output  

<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/49f2e839-6ab5-4a23-939d-710b96c73f70" />

## Programs for logical operations
## AND
```
 MOV AL, 53H
 MOV BL, 24H
 AND AL,BL
 HLT
 ```
## Output  
<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/b7ca0702-75af-4afd-a36e-fe11f4ba16df" />
## OR
```
MOV AL, 53H
 MOV BL, 24H
 OR AL,BL
 HLT
```
## Output
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/82802ae9-0446-4e62-855b-815c9255a2b0" />
## EX-OR
```
 MOV AL, 53H
 MOV BL, 24H
 XOR AL,BL
 HLT
```
## Output
<img width="1920" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/f83692aa-7537-43e8-91bb-133f7854b16d" />

## NOT
```
 MOV AL, 53H
 MOV BL, 24H
 NOT AL
 HLT
```
## Output

<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/017ac395-00be-4ecf-af5c-cdda604443ba" />


## Result :
 
Thus a program on ALP for the fundamental arithmetic and logical operations is done successful.









