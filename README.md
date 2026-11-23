# Magwinya Oil Temperature Monitor

## Overview
This repository contains a C++ console program for checking cooking-oil temperature before frying Magwinyas. The program asks for two initial temperature readings, compares the change, and then checks a third reading against the range of 150–190 degrees.

## Included source
- `oil_temperature_monitor.cpp` — the C++ source code currently available in this repository.

## How the program works
1. Enter the first and second temperature readings.
2. The program calculates the difference between the readings.
3. If the difference is greater than 50, it advises reducing the fryer heat.
4. If the difference is less than 10, it advises increasing the fryer heat.
5. Enter the third reading. The program says frying may start only when this reading is between 150 and 190 inclusive.

## Compile and run
Using a C++ compiler such as g++:

```bash
g++ oil_temperature_monitor.cpp -o oil_temperature_monitor
./oil_temperature_monitor
```

On Windows, run the compiled `oil_temperature_monitor.exe` from Command Prompt or your IDE.

## Important notes
- The program uses integer temperature inputs.
- It checks the third reading against the stated 150–190 range.
- The program does not control a physical fryer or read a temperature sensor automatically.
- A number-converter program is mentioned in the old commit notes, but its source code is not currently present in this repository.

## Author
Thabiso Ndlovu
