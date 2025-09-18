RISC-V SoC Tapeout Odyssey

This repository documents my work in the VSD RISC-V Reference SoC Tapeout Program (Phase-2).
It presents a structured exploration of the open-source ASIC design flow — progressing from RTL to GDSII — utilizing the SKY130 process design kit (PDK) and a suite of open-source EDA tools.

📌 Program Overview

The VSD Tapeout Program is an industry-oriented initiative designed to provide end-to-end exposure to the ASIC design ecosystem. The program emphasizes:

RISC-V based SoC architecture design and integration

RTL-to-GDSII implementation using OpenLane

Timing closure, power analysis, floorplanning, placement, and routing

Tapeout readiness using the open-source SKY130 PDK

📖 For additional context, refer to the official announcement:
🔗 Silicon Sovereignty – Why It Matters (Phase-2 Launch)

📂 Repository Organization

docs/ → Technical documentation, design notes, and reports

src/ → RTL source files and verification testbenches

scripts/ → OpenLane automation and supporting scripts

results/ → Generated layouts, timing/power reports, and logs

images/ → Architecture diagrams, flowcharts, and visualizations

🛠️ Tools & Technologies

OpenLane – Automated RTL-to-GDSII flow

Yosys – Logic synthesis framework

OpenROAD – Floorplanning, placement, clock tree synthesis, and routing

Magic VLSI – Physical verification (DRC/LVS) and layout inspection

ngspice – Circuit simulation and analysis

SKY130 PDK – Open-source technology node for fabrication

🎯 Key Learning Outcomes

Comprehensive understanding of the end-to-end ASIC design flow

Practical experience with tapeout-ready SoC implementation

Enhanced knowledge of RISC-V architecture and open-source EDA tools

Familiarity with industry-aligned design methodologies for silicon fabrication
