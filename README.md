# 4bit-ALU-Simulation-with-Arduino-using-TINKERCAD

This project implements a 4-bit Arithmetic Logic Unit (ALU) using an Arduino Uno.
The ALU performs five operations:
- ADD (opcode 0)
- SUB (opcode 1)
- AND (opcode 2)
- OR  (opcode 3)
- XOR (opcode 4)

The circuit is built entirely in **Tinkercad Circuits**, using:
- 4 LEDs to display the 4-bit result
- 1 LED to display the carry-out
- 5 resistors (one for each LED)
- Arduino Uno for computation and control
  .
 Features
  .
- Fully functional 4-bit ALU
- Binary output displayed on physical LEDs
- Carry flag LED
- Serial input interface
- Clean code with bitwise operations and masking
- 100% hardware-accurate simulation

## ALU Operation Table

| Opcode | Operation | Description        |
|--------|------------|--------------------|
|   0    | ADD        | A + B              |
|   1    | SUB        | A - B (4-bit wrap) |
|   2    | AND        | Bitwise AND        |
|   3    | OR         | Bitwise OR         |
|   4    | XOR        | Bitwise XOR        |

## 🔌 Wiring Summary
Each LED:
Arduino Pin → LED (anode) → LED (cathode) → 220Ω → GND

Pin mapping:
- Result bit 0 → pin 4  
- Result bit 1 → pin 5  
- Result bit 2 → pin 6  
- Result bit 3 → pin 7  
- Carry       → pin 8  

##  How to Use
1. Open Tinkercad → Circuits → Start Simulation  
2. Open the Serial Monitor (9600 baud)  
3. Enter: A B Opcode (exactly in this format with spaces in between)

##DEMO EXAMPLE (for input 15 12 2)
<img width="1335" height="814" alt="image" src="https://github.com/user-attachments/assets/15d40509-7f74-435f-92e1-70dd9317eb6b" />

##Link to project:
https://www.tinkercad.com/things/090CcpHiG6k/editel?sharecode=ebS35rnggtsrK1tRjXi-nFmAVOl_ZQzVzY3Af2YppIo



