## What Is Icarus Verilog?
_Icarus Verilog_ is a Verilog simulation and synthesis tool. It operates as a compiler, compiling source code written in Verilog (IEEE-1364) into some target format. For batch simulation, the compiler can generate an intermediate form called _vvp assembly_. This intermediate form is executed by the ``vvp'' command. For synthesis, the compiler generates netlists in the desired format. (Source: [iverilog](http://iverilog.icarus.com/))

## Installation
 1. Download iverilog for windows [here](https://bleyer.org/icarus/) 
 
 ### Linux
 Compile from source [here](https://iverilog.fandom.com/wiki/Installation_Guide)
 
**Ubuntu based system**

**$** sudo apt-get install verilog

**$** sudo apt-get install gtkwave

## Run

 1. **$** iverilog [file1.vl	file2.vl ...]	testbench.vl
 2. **$** vvp [filename.out]
 3. Use [GTKWave](http://gtkwave.sourceforge.net/) tool to visualise the  **.vcd** file

**Note**: *(**replace [ ] with the filename(s)**)*
