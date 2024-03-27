# Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah

Course -  [Advanced Physical Design Using OpenLANE/SKY130 offered by VSDIAT](https://vsdsquadron.vlsisystemdesign.com/digital-vlsi-soc-design-and-planning/)

Author - Ojasvi Shah

Contents -:
* [SKY130 Day 1: Inception of OpenSource EDA, OpenLANE and SKY130 PDK](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md)
    - [How to Talk to Computers](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#how-to-talk-to-computers)
        + [Introduction to QFN - 48 package, chip, pads, core, die and IPs](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#introduction-to-qfn---48-package-chip-pads-core-die-and-ips)
        + [Introduction to RISC V](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#introduction-to-risc-v)
        + [From Software Applications to Hardware](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#from-software-applications-to-hardware)
    - [SoC Design and OpenLANE](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#soc-design-and-openlane)
        + [Introduction to Components of Opensource Digital ASIC Design](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#introduction-to-components-of-opensource-digital-asic-design)
        + [Simplified RTL to GDS flow](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#simplified-rtl-to-gds-flow)
        + [Introduction to OpenLANE and Strive Chipsets](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#introduction-to-openlane-and-strive-chipsets)
        + [Introduction to OpenLANE detailed ASIC Design Flow](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#introduction-to-openlane-detailed-asic-design-flow)
    - [Get Familiar to Opensource EDA tools](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#get-familiar-to-opensource-eda-tools)
        + [OpenLANE Directory Structure in Detail](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#openlane-directory-structure-in-detail)
        + [Design Preparation Step](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#design-preparation-step)
        + [Review Files After Design Prep and Run Synthesis](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#review-files-after-design-prep-and-run-synthesis)
        + [Steps to Characterise Synthesis Results](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%201.md#steps-to-charecterise-synthesis-results)        
* [SKY130 Day 2: Good vs Bad Floorplan and Introduction to Library Cells](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#sky130-day-2-good-vs-bad-floorplan-and-introduction-to-library-cells)
    - [Chip Floor Planning Considerations](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#chip-floor-planning-considerations)
        + [Utilisation Factor and Aspect Ratio](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#utilisation-factor-and-aspect-ratio)
        + [Concept of Pre-Placed Cells](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#concept-of-pre-placed-cells)
        + [De-Coupling Capacitors](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#de-coupling-capacitors)
        + [Power Planning](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#power-planning)
        + [Pin Placement and Logical Cell Placement Blockage](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#pin-placement-and-logical-cell-placement-blockage)
        + [Steps to Run Floorplan Using OpenLANE](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#steps-to-run-floorplan-using-openlane)
        + [Review Floorplan Files and Steps to Review Floorplan](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#review-floorplan-files-and-steps-to-review-floorplan)
        + [Review Floorplan Layout in Magic](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#review-floorplan-layout-in-magic)
     - [Library Binding and Placement](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#library-binding-and-placement)
        + [Netlist Binding and Initial Place Design](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#netlist-binding-and-initial-place-design)
        + [Optimise Placement Using Estimated Wire-Length and Capacitance](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#optimise-placement-using-estimated-wire-length-and-capacitance)
        + [Final Placement Optimization](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#final-placement-optimization)
        + [Need for Libraries and Characterisation](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#need-for-libraries-and-characterisation)
        + [Congestion Aware Placement Using RePLACE](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#congestion-aware-placement-using-replace)
    - [Cell Design and Characterisation Flows](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#cell-design-and-characterisation-flows)
        + [Inputs for Cell Design Flow](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#inputs-for-cell-design-flow-and-circuit-and-layout-design-step)
        + [Circuit Design Step](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#inputs-for-cell-design-flow-and-circuit-and-layout-design-step)
        + [Layout Design Step](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#inputs-for-cell-design-flow-and-circuit-and-layout-design-step)
        + [Typical Characterisation Flow](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#typical-characterisation-flow)
     - [General Timing Characterisation Parameters](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#general-timing-characterisation-parameters)
        + [Timing Threshhold Definitions](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#timing-threshhold-definitions)
        + [Propogation Delay and Transition Time](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%202.md#propogation-delay-and-transition-time)     
* [SKY130 DAY 3: Design Library Cell Using Magic Layout and NGSPICE characterisation](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#sky130-day-3-design-library-cell-using-magic-layout-and-ngspice-characterisation)
     - [Labs for CMOS Inverter NGSPICE Simulations](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#labs-for-cmos-inverter-ngspice-simulations)
        + [IO Placer Revision](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#io-placer-revision)
        + [SPICE Deck Creation For CMOS Inverter](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#spice-deck-creation-for-cmos-inverter)
        + [SPICE Simulation Lab for CMOS Inverter](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#spice-simulation-lab-for-cmos-inverter)
        + [Switching Threshhold Vm](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#switching-threshhold-vm)
        + [Static and Dynamic Simulation of CMOS Inverter](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#static-and-dynamic-simulation-of-cmos-inverter)
        + [Lab Steps to GitClone VSDSTD Cell Design](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-steps-to-gitclone-vsdstd-cell-design)
     - [Inception of Layout Â CMOS Fabrication Process](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#inception-of-layout-%C3%A2-cmos-fabrication-process)
        + [Create Active Regions](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#create-active-regions)
        + [Formation of N and P well](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#formation-of-n-and-p-well)
        + [Formation of Gate Terminal](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#formation-of-gate-terminal)
        + [Lightly Doped Drain [LDD] Formation](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lightly-doped-drain-ldd-formation)
        + [Source Â Drain Formation](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#source-%C3%A2-drain-formation)
        + [Local Interconnect Formation](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#local-interconnect-formation)
        + [Higher Level Metal Formation](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#higher-level-metal-formation)
        + [Lab Introduction to SKY130 Basic Layers Layout and LEF using Inverter](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-introduction-to-sky130-basic-layers-layout-and-lef-using-inverter)
        + [Lab Steps to Create STD Cell Layout and Extract SPICE Netlist](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-steps-to-create-std-cell-layout-and-extract-spice-netlist)
     - [SKY130 Tech File Labs](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#sky130-tech-file-labs)
        + [Lab Steps To Create Final SPICE deck using SKY130 tech](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-steps-to-create-final-spice-deak-using-sky130-tech)
        + [Lab Steps to Characterise Inverter using SKY130 Model Files](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-steps-to-characterise-inverter-using-sky130-model-files)
        + [Lab Introduction to SKY130 PDKs And Steps to Download Labs](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-introduction-to-sky130-pdks-and-steps-to-download-labs)
        + [Lab Introduction to Magic Tool Options and DRC Rules](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-introduction-to-magic-tool-options-and-drc-rules)
        + [Lab Introduction to Magic and Steps to Load SKY130 Tech Rules](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-introduction-to-magic-and-steps-to-load-sky130-tech-rules)
        + [Lab Excercise to Fix **poly.9** error in SKY130 Tech-File](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-excercise-to-fix-poly9-error-in-sky130-tech-file)
        + [Lab Excercise to Implement Poly-Resistor Spacing to Diff and Tap](https://github.com/ojasvi-shah/Advanced-Physical-Design-Using-OpenLANE--Ojasvi-Shah/blob/main/DAY%203.md#lab-excercise-to-implement-poly-resistor-spacing-to-diff-and-tap)
* SKY130 DAY 4 : Pre-Layout Timing Analysis and Importance of Good Clock Tree
     - Timing Modelling Using Delay Tables
        + Lab Steps To Convert Grid Information Into Track Information
        + Lab Steps to Convert Magic Layout to STD Cell LEF
        + Introduction of Timing **libs** and Steps To Include New Cell in Synthesis
        + Delay Table Usage
        + Lab Steps To Configure Synthesis Settings to Fix Slack and Include VSDINV
     - Timing Analysis With Ideal Clocks Using Open STA
        + Setup Timing Analysis And Introduction to Flip-Flop Setup Time
        + Introduction to Clock Jitter and Uncertainty
        + Lab Steps to Configure OpenSTA for Post-Synth Timings Analysis
        + Lab Steps to Optimize Synthesis to Reduce Setup Violations
        + Lab Steps to do Basic Timing ECO
     - Clock Tree Synthesis TritonCTS and Signal Integrity
        + Clock Tree Routing and Buffering Using H-Tree Algorithm
        + Crosswalk and Clock Net Shielding
        + Lab Steps to run CTS using TritonCTS
        + Lab Steps to Verify CTS Runs
     - Timing Analysis  With Real Clocks Using Open STA
        + Setup Timing Analysis Using Real Clocks
        + Lab Steps to Analyse Timing With Real Clocks Using OpenSTA
        + Lab Steps to Excecute OpenSTA With Right Timing Libraries and CTS Assignment
        + Lab Steps to Observe Impact of Bigger CTS Buffers On Setup And Hold Timing
