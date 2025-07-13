# PIPELINE-PROCESSOR-DESIGN

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: DARAPU TEJESWARA RAO

*INTERN ID*: CT08DF1688

*DOMAIN*: VLSI

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

##As part of my VLSI internship at CODTECH IT SOLUTIONS PVT. LTD., I designed and simulated a 4-stage pipelined processor using Verilog HDL. This task focused on implementing a basic processor architecture that uses pipelining to execute instructions in an overlapped manner, thereby improving instruction throughput and efficiency.

The processor was divided into four stages:

Instruction Fetch (IF): Fetches the instruction from memory based on the program counter.

Instruction Decode (ID): Decodes the instruction and reads the necessary operands.

Execution (EX): Performs the required arithmetic or logical operation.

Write Back (WB): Writes the result back to the register file.

The instruction set supported three simple operations: ADD, SUB, and LOAD, encoded as 8-bit opcodes stored in a small instruction memory. At each clock cycle, instructions advanced through the pipeline stages, allowing multiple instructions to execute simultaneously at different stages.

A Verilog testbench was developed to simulate the processor, providing clock and reset signals and observing the progress of instructions through the pipeline. The simulation results showed correct instruction sequencing and overlapping, with each instruction advancing one stage per cycle as expected.

This task deepened my understanding of pipelined processor design, instruction flow, and Verilog-based modeling, reinforcing the importance of pipelining in high-performance digital systems.

##OUTPUT

![Image](https://github.com/user-attachments/assets/4ae94725-660b-4e87-9021-450bfed40dd9)



