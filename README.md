# css422-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CSS422 Homework 4 Solved](https://www.ankitcodinghub.com/product/css422-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119945&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSS422 Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Q1. (5 pts)

Consider the following IT (IF-THEN) block-based ARM assembly program.

CMP R0, R1

ITTEE GE

SUBSGE R3, R0, R2

MOVGE R0, #25

SUBSLT R4, R2, R0

MOVLT R0, #15

1. (3pts) Write the equivalent C or C++ program. The C or C++ program variable names must be the same as the register labels. You code must be executable, i.e., I expect to run “./a.out” after compiling your code through command “g++ testq1.cpp”. You should simply include your code in the pdf file that you show your answers to Q1 and Q2.

2. (1pt) For the initial values of R0 = 20, R1 = 10, and R2 = 5, what will be the final value of R0 after the execution of the above program?

Q2. (7 pts)

Assume that src1 DCD 0xFF00FF00 and src2 DCD 0x00AA00AA are located consecutively in the READONLY area of memory (see the code below). Also, assume that src1 starts at address 0x00000008 and SP = 0x20000400.

1. For each of the following instructions, calculate the values of registers involved. Write the values in the comment spaces of the following code as instructed . For example, “R0 =”means you need to fille out like R0 = 0x00000008; “SP =  ” means you need to show the transition of SP contents like SP = 0x20000400  0x20003FC.

THUMB

StackSize EQU 0x00000400

AREA STACK, NOINIT, READWRITE, ALIGN=3

MyStackMem SPACE StackSize

AREA RESET, READONLY

__Vectors EXPORT __Vectors

DCD MyStackMem + StackSize

DCD Reset_Handler

AREA MYDATA, DATA, READWRITE

AREA MYDCODE, CODE, READONLY

src1 DCD 0xFF00FF00

src2 DCD

ALIGN

ENTRY 0x00AA00AA

Reset_Handler EXPORT Reset_Handler

; WHAT ARE THE CONTENTS OF EACH REGISTER BELOW? Please fill in as comments

HW4_2 LDR R0, =src1 ; R0 = 0x00000008

ADD R0, R0, #1 ; R0 = 0x00000009 LDRB R1, [R0] ; R1 = 0x000000FF

draw_mem1 PUSH {R1} ; SP = 0x200003FC -&gt; 0x0000001A

ADD R0, #4 ; R0 = 0x0000000D

LDRSB R2, [R0] ; R2 = 0x00000000

draw_mem2 PUSH {R2} ; SP = 0x200003F8 -&gt; 0x00000024

MOV R3, SP ; R3 = 0x200003F8 ADD R3, #3 ; R3 = 0x200003FB LDR R4, [R3] ; R4 = 0x0000FF00

SUB R4, #0x004C004C; R4 = 0xFFB4FEB4

draw_mem3 STRB R4, [R3] ; R3 = 0x0000FF00

POP {R2} ; SP = 0x200003F8 -&gt;, 0x00000034 R2 = 0xB4000000

POP {R1} ; SP = 0x200003FC -&gt;, 0x00000034 R1 = 0x000000FF

2. Stack memory: fill out blanks upon the completion of each event: draw_mem1, draw_mem2, and draw_mem3. Each cell should store only one byte.

Address draw_mem1 draw_mem2 draw_mem3

PUSH {R1} PUSH {R2} STR R4, [R3]

0x200003F8 R4=0xFF00

0x200003F9 LR2=address(MOV, R3, SP) LR2=address(MOV, R3, SP)

0x200003FA R2=)x00 R2=)x00

0x200003FB R0=0x0D R3=0xFB

0x200003FC LR=address(ADD R0, #4) LR=address(Add R0, #4) LR=address(Add R0, #4)

0x200003FD R1=0xFF R1=0xFF R1=0xFF

0x200003FE R0=0x09 R0=0x08 R0=0x08

0x200003FF R1=src1 R1=src1 R1=src1

0x20000400

Q3. (8 pts) Parity-Bit Adding Program

1. To run Keil uVersion,

a. Create the HW4 folder on your Windows desktop, start uVersion, choose “new uVersion projection”.

b. Select this HW4 folder.

c. Use HW4 for HW4.uvproj/.uvprojx file names.

d. Choose Texas Instruments/Tiva C Series/TM4C123x Series/TM4C1233H6PM (the same platform as in lab1b).

e. Create main.s under Project HW4/Target 1/Source Group1/.

2. Simply comment out line 236 of startup_TM4C123.s: 236 ; BLX R0 so that startup_TM4C123.s skips calling SystemInit and directly invokes __main at line 238. (This is only a modification you need to do in startup_TM4C123.s. )

3. In your main.s, get started with the following code snippet:

AREA MyData, DATA, READWRITE dst SPACE 200

AREA |.text|, CODE, READONLY

EXPORT __main [WEAK]

ENTRY

__main

LDR R0, =src ; src address

LDR R1, =dst ; dst address

; R2 = the current ASCCI Char

; R3 = counter from 7 to 0

; R4 = #ones

4. Use R0, R1, R2, R3, and R4 as specified in the above code snipped:

a. To read a new ASCII character from src, you should use: LDRB R2, [R0], #1

b. To write an ASCII character with an odd parity to dst, use: STRB R2, [R1], #1

5. If you use parity.s from Canvas, make sure:

a. R0 should be R2 in HW4.

b. R1 should be R4 in HW4.

c. R2 should be R3 in HW4.

6. To check if R4 is odd, use: LSRS R4, #1 If a carry is set, R4 was odd, in which case don’t add a parity bit at bit 7 of R2. Otherwise it must have been even, and thus you need to set bit 7 of R2.

7. Unlike VisUAL, a real ARM processor does not stop with END. The very last statement in main.s should be an infinite loop like: end_of_main B end_of_main

8. Run your program, capture snapshots of src and dst memory contents, and verify if your dst memory contents got correct odd parities. The following is the key answer’s results. Don’t copy them. You need to generate those with your own program.

For this question, you need to submit the followings:

1. The source file: main.s. (If no source file, then you got zero point for this question)

2. The screenshots of memory view (src and dst contents) to support your correct results. Please include these screenshots in the same pdf file that you show your answers to Q1 and Q2.

3. After the screenshots, copy the code in main.s into the same pdf file that you show your answers to Q1 and Q2.
