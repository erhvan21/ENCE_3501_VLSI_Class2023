# <div align="center"> Lab 5 - Full Adder </div>
## Objective
  Using Electric VLSI, design the schematic and layout for a full-adder
## Logic Gate Schematic and Layout Development
Drafting the Schematics, layouts, and symbols for 2-input NAND and XOR logic gates, using 6u/2u MOSFETS to be used when designing the Full Adder

### NAND Gate
<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/NAND_draft.png/>
</p>

*<div align = "center">Figure 1 - NAND Gate Draft</div>*
 Figure 1 depicts the draft created for designing the NAND gate. The sybmol used for NAND gate in schematics, the boolean algebra used for designing the MOSFET schematic, as well as the Euler's path diagram used for designing the layout can be found.

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/NAND_schem.png/>
</p>

*<div align = "center"> Figure 2 - NAND MOSFET schematic in Electric VLSI</div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/NAND_layout.png/>
</p>

*<div align = "center"> Figure 3 - NAND MOSFET Layout in Electric VLSI </div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/NAND_sim_3.png>
</p?

*<div align = "center"> Figure 4 - NAND Schematic Simulation using LTSpice</div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/NAND_sim_4.png>
</p?

*<div align = "center"> Figure 5 - NAND Layout Simulation using LTSpice</div>*


### XOR Gate
<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/XOR_draft.png/>
</p>

*<div align = "center">Figure 6 - XOR Gate Draft</div>*
 Figure 6 depicts the draft created for designing the XOR gate. The sybmol used for NAND gate in schematics, the boolean algebra used for designing the MOSFET schematic, as well as the Euler's path diagram and Stick Diagram used for designing the layout can be found.

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/XOR_schem.png/>
</p>

*<div align = "center"> Figure 7 - XOR MOSFET schematic in Electric VLSI</div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/XOR_layout.png/>
</p>

*<div align = "center"> Figure 8 - XOR MOSFET Layout in Electric VLSI </div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/XOR_sim_3.png>
</p?

*<div align = "center"> Figure 9 - XOR Schematic Simulation using LTSpice</div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/XOR_sim_4.png>
</p?

*<div align = "center"> Figure 10 - XOR Layout Simulation using LTSpice</div>*

While the simulation differenes between the schematic and layout for the NAND gate are minimal, the respective differences for the XOR gate are more noticeable. The output voltage possesses a more gradual curve as it approaches 5V, which is due to the layout simulations accounting for delays, whereas the schematic simulations assume minimal delays. Since the XOR gate involves much more wires and FET's than the NAND gate, the delay seen by the output voltage is much more as well. These increased delays can cause glitches and produce unexpected results.

### Full Adder

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/FA_schem.png/>
</p>

*<div align = "center"> Figure 11 - Full Adder Schematic in Electric VLSI</div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/FA_layout.png/>
</p>

*<div align = "center"> Figure 11 - Full Adder Layout in Electric VLSI</div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/FA_sim_1.png/>
</p>

*<div align = "center"> Figure 12 - Full Adder Schematic Simulation in Electric VLSI</div>*

<p align = "center">
  <img src=https://github.com/erhvan21/ENCE_3501_VLSI_Class2023/blob/main/Lab%205/images/FA_sim_2.png/>
</p>

*<div align = "center"> Figure 13 - Full Adder Layout Simulation in Electric VLSI</div>*






