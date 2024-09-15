# Goertzel Filter Implementation
This [repository](https://github.com/Hadian1989/goertzel-filter-microelectrinic) contains the VHDL implementation of a Goertzel Filter, designed for detecting specific frequency components in a signal. The project was developed as part of the Microelectronics & HW/SW-Co-Design course at Fachhochschule Dortmund.

## Project Overview
The Goertzel Algorithm is an efficient DSP technique, especially useful for identifying particular frequencies in real-time. This project implements the algorithm using synthesizable VHDL code to detect a 150 kHz signal from a 4 MHz sample frequency.

## Features
- VHDL implementation of the Goertzel Filter
- Testbench with various waveforms (sine, square, triangle)
- FPGA and ASIC design considerations
- Results comparison between MATLAB and VHDL implementations
## Repository Structure
- /src: VHDL source files for the Goertzel filter.
- /testbench: VHDL testbench files for verification with different waveforms.
- /MATLAB: MATLAB scripts for generating signal stimuli.
- /docs: Report and documentation of the project.
## How to Use
1- Clone this repository.
2- Run the testbench with your preferred simulator (e.g., ModelSim, Vivado).
3- Use the provided MATLAB scripts to generate signal inputs for testing.
## Results
The performance of the filter was verified against various waveforms and frequencies. Detailed results are included in the report, with comparisons between MATLAB and VHDL outputs.

For more details on the design, implementation, and results, refer to the project report included in the repository.