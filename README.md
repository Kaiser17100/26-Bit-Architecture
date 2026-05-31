# 26-bit MIPS Processor
## Description
A Logisim-based project featuring both **Single-Cycle** and **Multi-Cycle** implementations of a custom 26-bit processor based on the __MIPS architecture__. This project contains the circuit designs and documentation for a custom 26-bit CPU. Unlike standard 32-bit MIPS, this project uses a adjusted 26-bit datapath and instruction set architecture built entirely in Logisim.

## Features
- **Single-Cycle Datapath:** Executes each instruction in one long clock cycle. Great for understanding the baseline data flow and combinational control logic.
- **Multi-Cycle Datapath:** Breaks instruction execution into distinct, shorter clock cycles (Fetch, Decode, Execute, Memory, Write-Back). Utilizes a Finite State Machine (FSM) for control.
- **Custom 26-bit Architecture:** Modified instruction formats and datapath components to support 26-bit words.
  
## Rulebook
Has the necessary information on how instructions work and how to convert instructions to hexadecimal

## Datapaths
### Single-Cycle
<img width="1427" height="769" alt="image" src="https://github.com/user-attachments/assets/4ac5faae-79ad-4c87-9649-7bf1effb76c7" />

### Multi-Cycle
<img width="1427" height="769" alt="image" src="https://github.com/user-attachments/assets/97374195-fa3b-4c50-b7e0-623780562378" />

## Prerequisite(s)
To open and simulate these processors, you will need **Logisim**. 
- Download Logisim (v2.7.1 recommended): [Logisim Download](https://sourceforge.net/projects/circuit/)

## License
This project is open-source and free to use. Feel free to modify and expand it!
