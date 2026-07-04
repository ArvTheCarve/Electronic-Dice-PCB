# 🎲 Electronic Dice

A single-die electronic dice roller built with a 555 timer and CD4017 decade counter. Hold the button to spin through faces 1–6, release to land on a number.
How it works
- 555 Timer (astable): generates a clock pulse. The potentiometer (RP1) sets the roll speed.
- CD4017 Decade Counter: advances one LED (1–6) per clock pulse.
- SW1 (Push Button): gates the clock into the counter. Hold to spin, release to stop. Ensure the LEDs cycle fast enough that release timing is effectively random, this can be done using the potentiometer.

Each LED footprint is labeled with its corresponding die-face pattern.

## 🧪 1. Breadboard Testing 
The circuit was initially built and tested on a breadboard to ensure it functions before moving to software design.

<img width="852" height="332" alt="breadboardDICE" src="https://github.com/user-attachments/assets/bd6ac8c9-8575-4389-8410-62d3fa2262b2" />

## 📐 2. EasyEDA Schematic
Once verified, all component connections were accurately mapped out inside the **EasyEDA Schematic Builder**. 

<img width="1132" height="690" alt="SCH_Dice" src="https://github.com/user-attachments/assets/681a126c-afb3-4cef-9941-4203685c3c4c" />

## 💻 3. PCB Design Layout
Using the **EasyEDA PCB Designer**, the board outline was defined, traces were routed, and design rules were checked for accuracy. 

<img width="1032" height="630" alt="PCB_Dice" src="https://github.com/user-attachments/assets/a7805ac4-f51c-4894-8861-cdd7d76c54cc" />

## ⚡ 4. Hand-Soldered Board
The custom boards were ordered, manufactured, and fully assembled and soldered by hand.

<img width="2781" height="2781" alt="IMG_3701" src="https://github.com/user-attachments/assets/f53599c5-ca94-4df8-adc3-42fde7c2d971" />
*Note: All source files, schematics, and design assets are fully available inside this repository.*

## 📜 License & Attribution

This project is licensed under the **MIT License** : see the [LICENSE](LICENSE) file for details. 

### How to Credit This Project
If you use, modify, or distribute these EasyEDA files, you must retain the original copyright notice. If you manufacture physical boards based on this design, please maintain the attribution text on the PCB silkscreen or credit this repository in your project documentation:

> **Designed by: Arveer Dhillon**  
> Source: [Link to this GitHub Repository](https://github.com/ArvTheCarve/Electronic-Dice-PCB)

## 🛠️ Getting Started

1. Download or clone this repository.
2. Open [EasyEDA](https://easyeda.com) (Standard or Pro edition).
3. Go to **File > Open > EasyEDA...** and import the design files.
