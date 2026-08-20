# VLSI-Internship-Task-4-Maincrafts-Technology

## RTL Design of Finite State Machines (FSM) and Control Units

This repository contains my work for **Task 4 of the VLSI Design Internship**, focused on the **RTL design and verification of Finite State Machines (FSMs) using Verilog HDL**.

## Author

**Name:** Ankit Kumar
**Roll Number:** 24ECE006
**College:** Ganga Institute of Technology and Management, Haryana

## Objective

The objective of this task is to understand and implement Finite State Machines using RTL design techniques and Verilog HDL.

The task covers:
* FSM fundamentals
* State diagrams
* State transition tables
* State encoding
* State equations / next-state logic
* Moore FSM
* Mealy FSM
* Verilog RTL implementation
* Testbench development
* Simulation and waveform analysis

## FSM Designs Implemented

### 1. Four-State FSM

A simple FSM that continuously cycles through four states.

### 2. Mealy FSM

An FSM where the output becomes `1` when:
Present State = S1
Input X = 1
Otherwise, the output remains `0`.

### 3. Traffic Light Controller

A three-state traffic light controller consisting of:

S0 → RED
S1 → GREEN
S2 → YELLOW

The input `X` controls state transitions:

X = 1 → Move to next state
X = 0 → Remain in present state

### 4. 1011 Sequence Detector

A **Mealy FSM** designed to detect the input sequence: 1011
The output becomes `1` when the sequence `1011` is detected.

## Tools Used

* **EDA Playground**
* **Icarus Verilog**
* **GTKWave** for waveform analysis
* **LOGISIM** for circuit design

## Verification

Each FSM includes a corresponding **testbench** for simulation and verification.

The testbenches generate:

* Clock signal
* Reset signal
* Required input sequences
* Simulation output
* VCD waveform files

The generated waveforms were analyzed to verify the expected FSM behaviour.

## 📄 Report

The complete internship task report is available in document file. 

The report contains the state diagrams, state tables, K-map simplifications, Verilog programs, testbenches, and simulation waveforms.

##  Learning Outcomes

Through this task, I gained practical understanding of:

* Designing FSMs from problem statements
* Converting state diagrams into state tables
* State encoding
* Deriving next-state equations
* Implementing Moore and Mealy machines
* Writing synthesizable Verilog RTL
* Creating Verilog testbenches
* Verifying designs using simulation waveforms


## Internship by Maincrafts Technology

**VLSI Design Internship – Task 4**

Focus: **RTL Design of Finite State Machines (FSM) and Control Units**

## Thanks to Maincrafts Technology to provide me this internship. 

