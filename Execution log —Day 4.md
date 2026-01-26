# Day 4 | Jan 8, 2025

## What I did
- Learned functions as subsystems in a system
- Understood why we use functions (modularity, readability, reusability)
- Saw how data flows in (parameters) and out (return values)
- Understood main() as the system controller

## Time spent
~25 min

## What I learned
**Functions = Subsystems**
- Each function has one clear job
- Inputs (parameters) → Processing → Output (return)
- main() coordinates subsystems like a master controller

**Why functions matter:**
1. Break complex systems into testable pieces
2. Make code readable (like a block diagram)
3. Reuse code across projects

**Key insight:**
Good code reads like a block diagram. Each function is a labeled box with clear inputs/outputs.

## Examples understood
- add() — simple data flow
- read_temperature() — realistic sensor reading
- LED blink system — hardware control with subsystems


---

## **Summary for my Notes**

**Day 4 | Functions as Subsystems**

**Core idea:**
Functions = subsystems in a machine. Each has a job, inputs, outputs, and can be tested independently.

**Why use functions:**
1. Modularity (break complexity)
2. Readability (code as block diagram)
3. Reusability (write once, use everywhere)

**Data flow:**
```
Input (parameters) → [Function body] → Output (return value)