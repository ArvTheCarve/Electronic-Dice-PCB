# 🎲 Electronic Dice

A single-die electronic dice roller built with a 555 timer and CD4017 decade counter. Hold the button to spin through faces 1–6, release to land on a number.
How it works
- 555 Timer (astable): generates a clock pulse. The potentiometer (RP1) sets the roll speed.
- CD4017 Decade Counter: advances one LED (1–6) per clock pulse.
- SW1 (Push Button): gates the clock into the counter. Hold to spin, release to stop. Ensure the LEDs cycle fast enough that release timing is effectively random, this can be done using the potentiometer.

Each LED footprint is labeled with its corresponding die-face pattern.


Circuit was built on a breadboard to ensure it works. <img width="852" height="332" alt="breadboardDICE" src="https://github.com/user-attachments/assets/bd6ac8c9-8575-4389-8410-62d3fa2262b2" />

Schematic: <img width="1132" height="690" alt="SCH_Dice" src="https://github.com/user-attachments/assets/681a126c-afb3-4cef-9941-4203685c3c4c" />

PCB Design: <img width="1032" height="630" alt="PCB_Dice" src="https://github.com/user-attachments/assets/a7805ac4-f51c-4894-8861-cdd7d76c54cc" />

All files are attached to the repository. 
