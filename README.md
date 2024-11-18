# EXPERIMENT--01-ALP-FOR-8086

Name : Vasanth Kumar V

Roll no : 2305002027

Date of experiment : 21.10.2024





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

## program for arithmetric operation:

## Addition of 8 bit ALP
```
org 100h

mov al, 15h
mov bl, 22h
add al, bl
mov [5454h], al

ret
```
## output
![362342974-ebc6d969-f133-4830-b0db-0358bae7a528](https://github.com/user-attachments/assets/d795444c-94c2-4de0-8085-6efd3d67a0c6)

## Subtraction of 8 bit numbers ALP
```
org 100h

mov al, 55h
mov bl, 21h
sub al, bl
mov [3254h], al

ret
```
## output
![362343292-9261f88a-91b4-4d5c-b3ca-083265a08eee](https://github.com/user-attachments/assets/b5ecc660-4794-48cd-a80b-a9c7ebdbf88a)

## Multiplication alp
```
org 100h

mov al, 17h
mov bl, 4h
mul bl
mov [1234h], al

ret
```
## output
![362343442-7740141c-4139-4da9-8400-6e2225da7256](https://github.com/user-attachments/assets/9ab5d269-40a5-4947-a819-93e1dd78bbb8)


## Division alp
```

mov al, 72h
mov bl, 4h
div bl
mov [5151h], al

ret
```

## Output  
![Screenshot 2024-10-14 143247](https://github.com/user-attachments/assets/b107da71-4fcb-48af-8cb0-aebdde04eae8)


## AND of 8 bit ALP
```
org 100h

mov al, 07h
mov bl, 05h
and al, bl
mov [5000h], al

ret
```

## Output
![Screenshot 2024-10-14 143501](https://github.com/user-attachments/assets/c24bc536-cd65-4310-9c79-1b266589c4ff)

## OR of 8 bit ALP
```
org 100h

mov al, 15h
mov bl, 22h
or al, bl
mov [5454h], al

ret
```
## Output
![Screenshot 2024-10-14 143656](https://github.com/user-attachments/assets/fa440da3-976e-46c5-ae24-55d92c59d19d)

## NOT of 8 bit ALP
```
org 100h

mov ax, 0F5Bh
not ax
mov [6666h], ax

ret
```
## Output
![Screenshot 2024-10-14 164534](https://github.com/user-attachments/assets/3e62ab9d-6594-442c-b87f-d9dfa4d57cda)

## XOR of 8 bit ALP
```
org 100h

mov ax, 0A32h
mov bx, 05B7h
xor ax, bx
mov [5050h], ax

ret
```
## Output
![Screenshot 2024-10-14 144007](https://github.com/user-attachments/assets/a78ea66f-5f12-4eeb-bfe5-5e79ed788018)

## Result :
Thus to Write and execute ALP on fundamental arithmetic and logical operations are verified
successfully.









