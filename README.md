# OpenRAM generated SRAM-based TCAM Compiler
![MERL image](https://github.com/merledu/SRAM_based_TCAM/blob/main/images/merl-logo.png)
<img src="https://github.com/merledu/SRAM_based_TCAM/blob/main/images/vlsi_logo_official_colors.png" />

This initiative is a collaboration between MERL laboratory at Usman Institute of Technology and VLSIDA laboratory at University of Califronia, Santa Cruz.

Currently at IEEE SSCS Pico Design Contest, we are looking for utilizing 1KB SRAM macros (OPENRAM) for generating 32 x 8 bit TCAM blocks at single cycle search operation. This project will evolve for other SRAM macros as well.

This project can be tied as an accelerator (in user project area) to the management SoC  of caravel (harness). It mimic the functionality of TCAM using SRAM. We will utilize OpenRAM to generate SRAM-based TCAM. Different sizes and configuration of SRAMs can be generated thorough OpenRAM compiler for sky 130 nm technology, these compiled SRAMs will then be used to mimic the functionality of Classical TCAM. 

This is the high level view of the SRAM- based TCAM memory architecture, which was proved previously using blockRAMs and distributed RAMs of Xilinx Kintex-7 FPGAs and also validated the search operation functionality in-line with classical Netlogic TCAM IC. Here , we are trying to prove same using OpenRAM compiled SRAMs.

 


![SRAM based TCAM image](https://github.com/merledu/SRAM_based_TCAM/blob/main/images/SRAM-Based%20TCAM.png)

