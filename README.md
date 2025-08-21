# EXPERIMENT-01 ALP for Fundamental arithmetic and logical operations using 8086 
Name : Zafreen J

Roll no : 212223040252

Date : 21/08/25

## Aim:
To Write and execute ALP for fundamental arithmetic and logical operations using 8086.
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

```
org 100h

mov ax,2525h
mov bx,0005h
div bx
mov [2006h],ax

mov ax,4325h
mov bx,2233h 
add ax,bx
mov [2000h],ax

mov ax,4325h
sub ax,bx
mov [2002h],ax

mov ax,4325h
mov cx,2525h
mul cx
mov [2004h],ax

ret

```

## Output : 

 <img width="1752" height="707" alt="image" src="https://github.com/user-attachments/assets/a72cd5be-0a95-4727-90fa-5290cf061bc2" />

## Programs for logical Operations :

```
org 100h


mov ax,[4000h]
mov bx,[4002h]
and ax,bx
mov [4010h],ax
 
mov ax,[4000h]
mov bx,[4002h] 
or ax,bx
mov [4012h],ax
 
mov ax,[4000h]
mov bx,[4002h]
not ax
mov [4014h],ax

mov ax,[4000h]
mov bx,[4002h]
xor ax,bx
mov [4016h],ax

ret

```

## Output : 
<img width="1644" height="765" alt="image" src="https://github.com/user-attachments/assets/b0022830-15af-41fe-ae02-126625f14b31" />


## Result :
 
The ALP on fundamental arithmetic and logical operations using 8086 is executed successfully.







