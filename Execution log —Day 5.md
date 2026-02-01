# Day 5 | Jan 31, 2026

## What I did
- Learned why state machines are safer than if-else logic
- Understood what bugs states prevent (race conditions, invalid flags, edge cases)
- Studied light controller example (off → dim → bright)

## Time spent
~30 min

## What I learned
**State machines = explicit context**
- System is in ONE state at a time
- Each state defines what's allowed
- Transitions are explicit and controlled

**Bugs prevented:**
1. Race conditions (can't dim while turning on)
2. Invalid flag combinations (can't have door_open AND motor_running)
3. Forgotten edge cases (corrupted state → default case catches it)

**Key insight:**
If-else asks "what should I do NOW?"
State machine asks "what state am I in, and what's allowed FROM HERE?"

**Real example:**
Light controller with fading — state machine prevents button spam during transitions.

