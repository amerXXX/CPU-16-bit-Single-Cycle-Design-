# CPU-16-bit-Single-Cycle-Design-
Design and implementation of a 16-bit single-cycle RISC CPU in Logisim-Evolution. It supports arithmetic, logic, memory, branch, and bit-reversal instructions. A five-stage pipeline with forwarding and hazard detection ensures correct execution. Test programs validate loops, branches, and procedure calls. Future work explores multi-cycle designs.
<img width="759" height="723" alt="image" src="https://github.com/user-attachments/assets/c1066f44-f35b-49e6-bdd5-ab724530cce7" />

A Logisim-Evolution implementation of a 16-bit single-cycle RISC CPU featuring a five-stage pipeline with hazard detection and forwarding.

## Features
- **Instruction Set:** Arithmetic (ADD, SUB), logic (AND, OR, NOT), memory (LW, SW), branch (BEQ, BNE), and bit-reversal
- **Pipeline:** IF → ID → EX → MEM → WB with data-forwarding and stall logic
- **Hazard Detection:** Automatic stall insertion on load‐use and branch hazards
- **Test Programs:** Loop handling, procedure calls, and BIST patterns

## Getting Started

### Prerequisites
- Java 8+ (for Logisim-Evolution)
- Logisim-Evolution v3.8.0 or later

### Installation
1. Clone the repo:  
   ```bash
   git clone https://github.com/yourusername/risc16-cpu.git
   cd risc16-cpu
