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
---
```
![ubuntu Installed](https://github.com/bdivya-9125/soc-odyssey-week0-lab-setup/blob/main/Week0/Task0/Images/ubuntu_install.jpg?raw=true)

# TOOL CHECK
## 2. Yosys

```bash
$ sudo apt update
$ sudo apt install build-essential clang bison flex git -y
$ git clone https://github.com/YosysHQ/yosys
$ cd yosys
$ make
$ sudo make install
```
![Yosys Installed](https://github.com/bdivya-9125/soc-odyssey-week0-lab-setup/blob/main/Week0/Task0/Images/yosys.jpg?raw=true)

## 3.Icarus Verilog
```bash
$ sudo apt install iverilog -y
$ iverilog -v
```
![iverilog Installed](https://github.com/bdivya-9125/soc-odyssey-week0-lab-setup/blob/main/Week0/Task0/Images/iverilog.jpg?raw=true)

## 4.GTKWave
```bash
$ sudo apt install gtkwave -y
$ gtkwave --version
```
![iverilog Installed](https://github.com/bdivya-9125/soc-odyssey-week0-lab-setup/blob/main/Week0/Task0/Images/gtkwave.jpg?raw=true)

## 5. Magic
```bash
$ sudo apt install magic -y
$ magic -noconsole -dnull
```
![iverilog Installed]()

## 6. Ngspice
```bash
$ sudo apt install ngspice -y
$ ngspice -v
```
![iverilog Installed]()



