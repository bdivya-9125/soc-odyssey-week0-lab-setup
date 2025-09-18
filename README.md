RISC-V SoC Tapeout Odyssey

This repository captures my journey through the VSD RISC-V Reference SoC Tapeout Program (Phase-2). It provides a structured walkthrough of the open-source ASIC design flow — from RTL to GDSII — using the SKY130 process design kit (PDK) alongside a suite of open-source EDA tools.

📌 Program Overview

The VSD Tapeout Program is an industry-focused initiative aimed at giving participants end-to-end exposure to the ASIC design lifecycle. The program emphasizes:

Designing and integrating RISC-V based SoC architectures

Implementing RTL-to-GDSII flows with OpenLane

Achieving timing closure, performing power analysis, and handling floorplanning, placement, and routing

Preparing tapeout-ready designs using the open-source SKY130 PDK

For further context, see the official announcement: 🔗 Silicon Sovereignty – Why It Matters (Phase-2 Launch)

📂 Repository Structure

docs/ → Technical documentation, design notes, and reports

src/ → RTL source files and verification testbenches

scripts/ → OpenLane automation scripts and supporting utilities

results/ → Generated layouts, timing & power reports, and logs

images/ → Architecture diagrams, flowcharts, and visualizations

🛠️ Tools & Technologies

OpenLane – Automated RTL-to-GDSII flow

Yosys – Logic synthesis framework

OpenROAD – Floorplanning, placement, clock tree synthesis, and routing

Magic VLSI – Physical verification (DRC/LVS) and layout inspection

ngspice – Circuit simulation and analysis

SKY130 PDK – Open-source technology node for fabrication

🎯 Key Takeaways

Hands-on understanding of the complete ASIC design flow

Practical experience in implementing tapeout-ready SoCs

Deeper knowledge of RISC-V architecture and open-source EDA tools

Familiarity with industry-standard methodologies for silicon fabrication
