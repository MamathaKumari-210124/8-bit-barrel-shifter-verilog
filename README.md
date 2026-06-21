# 8-bit Barrel Shifter using Verilog HDL

## Overview

This project implements an 8-bit Barrel Shifter using Verilog HDL. A barrel shifter is a high-speed combinational circuit that can shift data by multiple bit positions in a single operation. It is widely used in processors, ALUs, and digital signal processing systems where fast data manipulation is required.

## Objective

To design and simulate an 8-bit barrel shifter capable of performing logical left and right shift operations based on user-defined control inputs.

## Features

* 8-bit data shifting
* Logical left shift operation
* Logical right shift operation
* Shift range from 0 to 7 bits
* High-speed combinational design
* Verilog HDL implementation
* Simulation and RTL verification

## Inputs and Outputs

### Inputs

* **A[7:0]** – 8-bit input data
* **S[2:0]** – Shift amount
* **dir** – Direction control signal

### Output

* **Y[7:0]** – Shifted output data

## Working Principle

The barrel shifter performs shifting operations in a single cycle. The direction control signal determines whether the data is shifted left or right, while the shift amount input specifies the number of bit positions. This enables efficient and fast data manipulation with minimal delay.

## Simulation Results

The design was successfully simulated using a Verilog testbench. The output correctly performs logical left and right shifts for different shift values and control inputs.

## Advantages

* High-speed operation
* Single-cycle shifting
* Efficient hardware implementation
* Reduced processing delay
* Improved system performance

## Applications

* Arithmetic Logic Units (ALUs)
* Microprocessors
* Digital Signal Processing (DSP)
* Data Manipulation Circuits
* FPGA-Based Systems

## Tools Used

* Verilog HDL
* Xilinx Vivado

## Team Members

* Mamatha Kumari
* Y Jyothi
* K Akshaya
* K Lakshmi Sree

## Institution

BVRIT HYDERABAD College of Engineering for Women

Department of Electronics and Communication Engineering
