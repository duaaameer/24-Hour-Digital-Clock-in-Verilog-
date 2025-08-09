# 24-Hour-Digital-Clock-in-Verilog-
This project implements a 24-hour digital clock using Verilog HDL, designed to run on an FPGA board. The clock displays hours (00-23), minutes (00-59), and seconds (00-59) on a 7-segment display or via a serial monitor. It includes features like:

* Timekeeping with 1Hz precision

* Reset functionality to set time manually

* FPGA-compatible 
Key Features
* 24-hour format (HH:MM:SS)
* Synchronous design (no glitches)
* Configurable clock source (internal oscillator or external input)
* Reset & Time-Setting Capability (optional push-button control)
* 7-Segment Display or UART Output (configurable)

* Development Tools
HDL: Verilog

* FPGA Boards: Xilinx Nexys 4DDR

* Simulation: Vivado

* Synthesis & Implementation: Xilinx Vivado 

* Testing: Verilog testbench with simulated clock
  # Note
  The repository contains seperate file for all the modules sevenseg_driver, Digitalclock, debounce and finallt Top Module. You may copy the code to run see the functionality. 
