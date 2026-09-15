# add-two-lab
Beginner MASM lab covering registers and arithmetic instructions

Write a program that calculates:

$$ (20 + 6) - (9 + 1) $$

Instead of placing the final answer directly into a register, your program must perform these steps:

Move 20 into EAX.
Move 6 into EBX.
Add EBX to EAX.
Move 9 into ECX.
Increment ECX by one.
Subtract ECX from EAX.
Copy the final result from EAX into EDX.

Use the instructions MOV, ADD, SUB, and INC. Include a comment explaining each instruction.

Predict, then verify

Before running the program, complete the predicted value column. Then use the debugger to execute one instruction at a time and record the actual value.

After this step	Register to inspect	Predicted value	Actual value
Move 20 into EAX	EAX		
Move 6 into EBX	EBX		
Add EBX to EAX	EAX		
Move 9 into ECX	ECX		
Increment ECX	ECX		
Subtract ECX from EAX	EAX		
Copy EAX into EDX	EDX		

Debugger note: Registers may appear in hexadecimal. For example, decimal 20 appears as hexadecimal 00000014. Record your answers in decimal.

What to submit:
1) Your commented .asm file.
2) The completed prediction table.
3) A screenshot of the registers after both calculations, taken before the program’s exit code executes.


