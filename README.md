# Lab 01: Add Two Lab

Practice using MASM instructions to move data, perform arithmetic, and inspect register values with the debugger.

## Student Task

Write a program that calculates:

```math
(20 + 6) - (9 + 1)
```

Instead of placing the final answer directly into a register, perform each step below in order.

| Step | Required Action |
| :---: | --- |
| 1 | Move `20` into `EAX`. |
| 2 | Move `6` into `EBX`. |
| 3 | Add `EBX` to `EAX`. |
| 4 | Move `9` into `ECX`. |
| 5 | Increment `ECX` by one. |
| 6 | Subtract `ECX` from `EAX`. |
| 7 | Copy the final result from `EAX` into `EDX`. |

### Program Requirements

- Use the instructions `MOV`, `ADD`, `SUB`, and `INC`.
- Perform the calculation using the required steps.
- Include a comment explaining each instruction.
- Leave the final result in both `EAX` and `EDX`.

## Predict, Then Verify

1. **Predict:** Before running your program, complete the **Predicted Value** column.
2. **Execute:** Use the debugger to execute one instruction at a time.
3. **Inspect:** After each instruction executes, check the register listed below.
4. **Record:** Enter its value in the **Actual Value** column.
5. **Compare:** If a prediction differs from the actual value, explain why beneath your table.

| After This Step | Register to Inspect | Predicted Value | Actual Value |
| --- | :---: | :---: | :---: |
| Move `20` into `EAX` | `EAX` | | |
| Move `6` into `EBX` | `EBX` | | |
| Add `EBX` to `EAX` | `EAX` | | |
| Move `9` into `ECX` | `ECX` | | |
| Increment `ECX` | `ECX` | | |
| Subtract `ECX` from `EAX` | `EAX` | | |
| Copy `EAX` into `EDX` | `EDX` | | |

> **Debugger Note**
>
> Registers may appear in hexadecimal. For example, decimal `20` appears as hexadecimal `00000014`.
>
> **Record all answers in the table in decimal.**

## Completion Checklist

-  My program performs all seven steps in order.
-  Each instruction includes an explanatory comment.
-  I recorded my predictions before running the program.
-  I used the debugger to verify each register value.
-  I completed the table using decimal values. (Completed on a document and submitted with project.)  
-  I explained any differences between my predicted and actual values.


  
