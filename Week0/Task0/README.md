# RISC‑V Reference SoC Tapeout Program VSD  
## Week 0 - Tools Installation

This document shows the installation and verification of all required tools for Week 0.

---

## System Requirements

- 6 GB RAM  
- 50 GB HDD  
- Ubuntu 22.04 LTS or higher  
- 4 vCPU  

---

## 1. Ubuntu / WSL

Installed Ubuntu 22.04 LTS via WSL2.

```bash
$ lsb_release -a
Distributor ID: Ubuntu
Description:    Ubuntu 22.04 LTS
Release:        22.04
Codename:       jammy

## Yosys

$ sudo apt update
$ sudo apt install build-essential clang bison flex git -y
$ git clone https://github.com/YosysHQ/yosys
$ cd yosys
$ make
$ sudo make install


# Icarus Verilog
$ sudo apt install iverilog -y
$ iverilog -v

# GTKWave
$ sudo apt install gtkwave -y
$ gtkwave --version

# Magic VLSI
$ sudo apt install magic -y
$ magic -noconsole -dnull

# Ngspice
$ sudo apt install ngspice -y
$ ngspice -v



