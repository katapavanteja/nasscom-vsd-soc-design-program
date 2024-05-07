# nasscom-vsd-soc-design-program
# Contents
1) Day-1: [Inception of open-source EDA, OpenLANE and Sky130 PDK](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#inception-of-open-source-eda-openlane-and-sky130-pdk)
    - [How to talk to computers](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#how-to-talk-to-computers)
       - [Introduction to QFN-48 Package, chip, pads, core, die and IPs](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#introduction-to-qfn-48-package-chip-pads-core-die-and-ips)
       - [Introduction to RISC-V](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#introduction-to-risc-v)
       - [From Software Applications to Hardware](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#from-software-applications-to-hardware)
    - [SOC Design and OpenLane](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#soc-design-and-openlane)
       - [Introduction to all components of open-source digital asic design](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#introduction-to-all-components-of-open-source-digital-asic-design)
       - [Simplified RTL2GDS Flow](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#simplified-rtl2gds-flow)
       - [Introduction to OpenLANE and Strive chipsets](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#introduction-to-openlane-and-strive-chipsets)
       - [Introduction to OpenLANE detailed ASIC design flow](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#introduction-to-openlane-detailed-asic-design-flow)
    - [Get familiar to open-source EDA tools](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#get-familiar-to-open-source-eda-tools)
       - [OpenLane Directory Structure](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#openlane-directory-structure)
       - [Design Preparation Setup](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#design-preparation-setup)
       - [Review files after design prep and run synthesis](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#review-files-after-design-prep-and-run-synthesis)
       - [Steps to charactirise Synthesis results](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#steps-to-charactirise-synthesis-results)
2) Day-2: [Good FloorPlan Vs Bad FloorPlan and Introduction to Library Cells](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#good-floorplan-vs-bad-floorplan-and-introduction-to-library-cells)
    - [Chip FloorPlanning Considerations](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#chip-floorplanning-considerations)
       - [Utilization Factor and Aspect Ratio](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#utilization-factor-and-aspect-ratio)
       - [Concept of pre-placed cells](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#concept-of-pre-placed-cells)
       - [De-coupling Capacitors](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#de-coupling-capacitors)
       - [Power Planning](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#power-planning)
       - [Pin placement and logical cell placement blockage](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#pin-placement-and-logical-cell-placement-blockage)
       - [Steps to run floorplan using OpenLANE](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#steps-to-run-floorplan-using-openlane)
       - [Review Floorplan files and steps to view floorplan](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#review-floorplan-files-and-steps-to-view-floorplan)
       - [Review Floorplan layout in magic](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#review-floorplan-layout-in-magic)
    - [Library Binding and Placement](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#library-bindidng-and-placement)
       - [Netlist binding and initial place design](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#netlist-binding-and-initial-place-design)
       - [Optimize placement using estimated wire-length and capacitance](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#optimize-placement-using-estimated-wire-length-and-capacitance)
       - [Congestion aware placement using replace](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#congestion-aware-placement-using-replace)
3) Day-3: [Design library cell using Magic Layout and ngspice characterization](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#design-library-cell-using-magic-layout-and-ngspice-characterization)
   - [Inception of Layout and CMOS fabrication process](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#inception-of-layout-and-cmos-fabrication-process)
      - [Lab steps to create std cell layout and extract spice netlist](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-create-std-cell-layout-and-extract-spice-netlist)
   - [Sky130 Tech File Labs](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#sky130-tech-file-labs)
      - [Lab Steps to create final SPICE deck using Sky130tech](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-create-final-spice-deck-using-sky130tech)
      - [Lab Steps to characterize the Inverter using sky130 model files](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-characterize-the-inverter-using-sky130-model-files)
      - [Lab Introduction to Sky130 pdk's and steps to download labs](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-introduction-to-sky130-pdks-and-steps-to-download-labs)
      - [Lab Introduction to Magic and steps to load Sky130 tech-rules](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-introduction-to-magic-and-steps-to-load-sky130-tech-rules)
      - [Lab exercise to fix Poly-9 error in Sky130 tech file](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-exercise-to-fix-poly-9-error-in-sky130-tech-file)
      - [Lab challenge exercise to describe DRC error as geometrical construct](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-challenge-exercise-to-describe-drc-error-as-geometrical-construct)
      - [Lab challenge to find missing or Incorrect rules and fix them](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-challenge-to-find-missing-or-incorrect-rules-and-fix-them)
4) Day-4: [Pre-layout timing analysis and importance of good clock tree](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#pre-layout-timing-analysis-and-importance-of-good-clock-tree)
   - [Timing modelling using delay tables](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#timing-modelling-using-delay-tables)
      - [Lab steps to convert grid info to track info](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-convert-grid-info-to-track-info)
      - [Lab steps to convert magic layout to standard cell LEF](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-convert-magic-layout-to-standard-cell-lef)
      - [Introduction to timing libs and steps to include new cell in synthesis](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#introduction-to-timing-libs-and-steps-to-include-new-cell-in-synthesis)
      - [Lab steps to configure synthesis settings to fix slack and include vsdinv](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-configure-synthesis-settings-to-fix-slack-and-include-vsdinv)
   - [Timing analysis with ideal clocks using openSTA](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#timing-analysis-with-ideal-clocks-using-opensta)
      - [Lab steps to configure OpenSTA for post-synth timing analysis](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-configure-opensta-for-post-synth-timing-analysis)
   - [Clock tree synthesis TritonCTS and signal integrity](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#clock-tree-synthesis-tritoncts-and-signal-integrity)
      - [Lab steps to run CTS using TritonCTS](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-run-cts-using-tritoncts)
   - [Timing analysis with real clocks using openSTA](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#timing-analysis-with-real-clocks-using-opensta)
      - [Lab steps to analyze timing with real clocks using OpenSTA](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-analyze-timing-with-real-clocks-using-opensta)
      - [Lab steps to execute OpenSTA with right timing libraries and CTS assignment](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-execute-opensta-with-right-timing-libraries-and-cts-assignment)
      - [Lab steps to observe impact of bigger CTS buffers on setup and hold timing](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-observe-impact-of-bigger-cts-buffers-on-setup-and-hold-timing)
5) Day-5: [Final steps for RTL2GDS using tritonRoute and openSTA](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#final-steps-for-rtl2gds-using-tritonroute-and-opensta)
   - [Power Distribution Network and routing](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#power-distribution-network-and-routing)
      - [Lab steps to build power distribution network](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-to-build-power-distribution-network)
      - [Lab steps from power straps to std cell power](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#lab-steps-from-power-straps-to-std-cell-power)
      - [Basics of global and detail routing and configure TritonRoute](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#basics-of-global-and-detail-routing-and-configure-tritonroute)
* [References](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/blob/main/README.md#references)

 

# Inception of open-source EDA, OpenLANE and Sky130 PDK
##  How to talk to computers
###   Introduction to QFN-48 Package, chip, pads, core, die and IPs

**Aurdino Board**: The image below is an Aurdino Microcontroller Board. Here we focus more on the encircled area, which contains the 'Microprocessor',that we will be designing from abstract level till fabrication level by using RTL to GDS flow

![Screenshot 2024-04-27 184745](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/76f788e6-5e83-410c-becc-cf496a400188)

While we cosider the chip, there are 3 main components:

(1) Pads : Through these pads signals can travel into the chip from external sources and viceversa.

(2) Die : It is the whole area of the chip that will be manufactured on the silicon wafer.

(3) Core : It is the area where our entire logic will be implemented.

![Screenshot 2024-04-25 121626](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/deb72a9c-1f29-4774-9462-1a9475746c8f)

The above mentioned MicroProcessor in an aurdino board is a package that consists of MicroProcessor chip and some other Foundry IP's(Intellectual Property). All of these combined called as a package.

For example, let's consider a package that consists of RISC V SOC and some other IP's such as SRAM , ADC , DAC , PLL etc..

![Screenshot 2024-04-25 122115](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/3685aa0c-5234-45d8-b8fc-f36cbbdc1dcc)


###  Introduction to RISC-V

**ISA**: ISA is known as "Instruction Set Architecture". It is nothing but a way of communicating with the computer.
In general we write codes that need to be executed by the system, using coding languages like C , Java etc. , but machine can't understand those languages. It is where ISA comes into picture. By using ISA the codes that were written wil be converted into assembly language and from there to binary i.e Machine understandable language. This is the purpose of the ISA, and the RISC V ISA is the latest ISA released.

![Screenshot 2024-04-25 125225](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/5c651754-2931-4f70-9c35-5b9ef0b5f841)


### From Software Applications to Hardware

In real life we generally deal with Application Softwares(Apps) in order to communicate with the Hardware.But how it's done exactly?
In between Application software and Hardware, there will be a software called System Software. The Applications enter into the System Software and will be converted into the Hardware understandable language i.e Binary Language.

The System Software consists of different layers:

(1) **O.S** : Other than the general operations like Handling I.O operations, Allocating Memory, Low level System Functions the O.S converts the Application software to respected C,C++,Java etc.. codes.

(2) **Compiler** : The compiler takes output of O.S as input and converts the codes in C,C++,Java etc.. into Instruction set(.exe files). These instructions will be dependent on type of hardware used.

(3) **Assembler** : Assembler converts the .exe files into binary language and provides it to the hardware, and hardware performs the respective operations.


![Screenshot 2024-04-25 150500](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/3997bfe1-9b4a-4824-9377-2f0af6141092)


## SOC Design and OpenLane

###  Introduction to all components of open-source digital asic design

In order to design a Open Source Digital ASIC, we primarily need some components. Such as

(1) RTL Designs

(2) EDA Tools

(3) PDK Data

There are some open sources to get these required components. 

For example, In case of RTL Designs we have librecores.org , opencores.org , github.com etc...

In case of EDA Tools we have Qflow , OpenRoad , OpenLane  etc...

In case of PDK Data, Recently in 2020 Google collabarated with SkyWater Technology and made **FOSS 130nm Production PDK** OpenSource.

![Screenshot 2024-04-26 120941](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/7f646e7f-6c14-4b9b-9952-057bd5b9f100)

What are RTL Designs?

RTL(Register-Transfer-Level) design is a crucial step in the VLSI design flow, which involves the creation of electronic circuits using integrated circuits (ICs). It involves the specification of a digital circuit in terms of the flow of digital signals between hardware registers, and the logical operations performed on those signals.

What are EDA Tools?

EDA(Electronic Design Automation) Tools are used to design and verify the functionality of an Integrated Circuit to ensure it deliver's the required performance and density.

What is PDK Data?

PDK(Process Design Kit) is a collection of files used to model a fabrication process for EDA Tools used in the design of an IC.The collection consists of

- Process Design Rules : DRC , LVS , PEX
- Device Models
- Digital Standard Cell Libraries
- I/O Libraries etc....


### Simplified RTL2GDS Flow

The simplified RTL to GDS Flow starts with an RTL file. After going through some set of stages we will get the output as a GDS file, which can be readily sent to foundry for fabrication. The steps involved in the RTL2GDS Flow is of following:

![Screenshot 2024-04-26 083825](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/7b2892cd-4de4-4453-b012-96f7bb6d6830)

(1) **synthesis** : 
- In synthesis stage RTL file will be converted into a circuit by using the components from the Standard Cell Library.
- The cells in the Standard Cell Library are called Standard Cells and they have the regular layout of same height but different widths.
- Each cell has different models based on Electrical,HDL,Spice,Layout(Abstract and Detailed) etc....

![Screenshot 2024-04-26 102201](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/71a3393c-2f6e-4b22-8b72-b26eaa22ff83)

 (2) **Floor Planning** & **Power Planning** :
 - Floor Planning is a stage where the position of the components on the chip will be decided by keeping the area of the chip as minimal as possible by following a set of rules.
 - During the Floor Planning Stage itself the position of I/O pins,ports,pads will be determined.

![Screenshot 2024-04-26 102220](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/85b4aae4-3ef6-473d-b638-692f5aace919)

 - In Power Planning stage the Power supply network i.e VDD & GND of the chip will be laid out. During Power PLanning 3 components Power Rings , Power Straps , Power Pads will be laid out.
 - For Power Network Top Metal Layers will be used because the Power Network should have minimum delay as possible and the top layers of metal will have the low resistance, So they are used.

![Screenshot 2024-04-26 102235](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/1aa9278c-331d-474a-8d60-74b9da1cb288)

(3) **Placement** :
- In Placement stage the components are placed within the areas planned during the FloorPlanning Stage.
- Along with them Standard Cells that are required in the design are also placed within the cell boundaries.
- Placement will be performed in 2 stages. They are Global Placement and Detailed Placement.
- During Global Placement the Standard cells may overlap and does not follow the Placement Rules.
- In Detailed Placement every standard cell will be placed in its optimal position by following the Placement rules.

![Screenshot 2024-04-26 102251](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/861d2368-0a25-47d4-a092-67711d3afe1e)

(4) **CTS**(Clock Tree Synthesis) :
- Before Performing Routing of the signals, we should perform Clock Routing.
- While Routing the clock tha major problem is CLock Skew.
- Clock Skew is the difference in time taken for the clock to reach two different destinations in the design.
- In order to eliminate the clock skew, we should deploy the technique called **Symmetric Tree Structure**.
- There are different types of Symmetric Tree Structures. They are H-tree,I-tree,X-tree etc...

![Screenshot 2024-04-26 102308](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/3d64c44e-26cb-4c3e-af1f-e1e09d261e2d)

(5) **Routing** :
- Afetr the clock routing is done, now signals must be routed.
- Router uses the remaining metal layers and makes conections in the design.
- Routing will be carried out in 2 stages.They are Global Routing and Detailed Routinng.
- In the stage of Global Routing, the tool generates a Routing guide by following the instructions given in the PDK.
- In the stage of Detailed Routing, actual routing will be done according to the guide generated in the Global Routing Stage.

![Screenshot 2024-04-26 102325](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/4b8970a1-dfda-454c-a0a8-c789ef0963a2)

(6) **Sign-off** :
- After Routing is done, the chip will be considered as completed and during Sign-off stage different types of checks will be performed.
- Physical Verification Checks : Design Rule Check(DRC) , Layout Vs Schematic(LVS)
- In DRC, the chip will be verified for the violations in the Design Rules provided by the PDK.
- In LVS, the chip will be checked for the functionality whether it matches to the gate level netlist functinality.
- Timing Checks : Static Timing Analysis(STA)
- During STA, the design is checked for Timing violations.


### Introduction to OpenLANE and Strive chipsets

OpenLane is started as an Open Source Flow for a true Open Source Tape-out experiment.It was from e-fabless.It is a platform which supports different tools such as Yosys,OpenRoad,Magic,KLlayout and some other Open source tools.It integrates the various steps of Silicon Implementation and abstracts it. At e-fabless they have an SOC family called Strive. Strive is a family of open everything SOCs having Open PDK, Open RTL, Open EDA.

The Strive SOC family of several members and the list is given below

![Screenshot 2024-04-26 184224](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/8c070b83-410e-4183-ac79-d993d251a588)

The main goal of OpenLane is to "Produce a clean GDS file with no human intervention with no LVS,DRC,Timing violations. It is majorly tuned for Skywater 130nm OpenPDK but also supports XFab180 and GF130G. It is functional out of the box.It can be used Harden Macros and chips. It has two modes of operation , autonomous and interactive. It has a feauture called Design Space Exploration which helps in finding the best set of flow configurations.Presently it also has large no.of design examples nearly 43 and more will be added soon.


### Introduction to OpenLANE detailed ASIC design flow

![Screenshot 2024-04-26 185534](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/6a21e3f7-a4e8-42c7-a1e8-748de6afa021)

The image shows the OpenLane detailed ASIC Design Flow.The flow starts with Design RTL, It goes through RTL synthesis by Yosys and abc giving an optimised gate level netlist. Now we perform STA on the optimised netlist inorder to check for Timing violations. After STA we perofrm DFT and this step is optional and for this we use FAULT tool.

Fault(for DFT) : 
- Scan Insertion
- Automatic Test Pattern Generation(ATPG)
- Test Pattern Compaction
- Fault coverage
- Fault Simulation

![Screenshot 2024-04-28 090349](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/316fe057-88ce-4bf3-9f2a-fb9f42b03756)

 After performing DFT next comes Physical Implementation.It is also called as Automated PnR(Place and Route) and for this we use OpenRoad.

 OpenRoad(for Physical Implementation) :
 - Floor/Power Planning
 - End Decoupling Capacitors and Tap Cells Insertion
 - Placement: Global and Detailed
 - Post placement optimization
 - Clock Tree Synthesis
 - Routing: Global and Detailed

 During PnR for every change in the design, we should check for LEC(Logic Equivalance Checking). LEC is used to confirm that the function did not change after modifying the netlist and also during physical implementation we have a important step called "Fake Antenna Diodes Insertion Script".

Dealing with Antenna Rule violations : When a metal wire segment is fabricated, it can act as an antenna.
- Reactive ion etching causes charge to accumilate on the wire.
- Transistor gates can be damaged during fabrication.

There are two solutions for this problem
- Bridging attaches a higher layer intermediary. It requires Router awareness.

![Screenshot 2024-04-28 093445](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/fddd163a-493a-4799-a659-4d20789d272b)

- Add antenna diode cell to leak away the charges. Antenna diodes are provided by the SCL. For this we took a preventive approach.
  - Add a Fake antenna didoe next to every cell input after placement.
  - Run the Antenna Checker(Magic) on the routed layout.
  - If the checker reports violation on the cell input pin, replace the fake diode cell by a real one 

 ![Screenshot 2024-04-28 094148](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/aa0d19c1-1e9f-47a2-8e16-5e9e4a5b8f3d)

 And at the end, we perform Physical Verification. Which includes DRC(Design Rule Checking) , LVS(Layout Vs Schematic). Along with the P.V we also performs STA to check for timing violations in the design.
 - MAGIC is used for DRC and SPICE Extraction from Layout.
 - MAGIC and Netgen are used for LVS by comparing Extracted SPICE by MAGIC and Verilog Netlist.


## Get familiar to open-source EDA tools

### OpenLane Directory Structure

 In order to access the OpenLane tool, we will be needing some basic linux commands.They are listed below 
 - pwd : It displays the present working directory and its path.
 - cd : Using this command we can move in both ways in the directory tree.
 - ls : It lists all the sub-directories and files present in the current directory.
 - mkdir : Using this command, we can create a new directory.
 - rmdir : Using his command, we can delete an existing directory.
 - rm : This command is used to delete the files.
 - help : using this command we can know the working of any command.
 - clear : This command clears the terminal.


### Design Preparation Setup

In order to enter into BASH, by being in OpenLane directory we should use a command called **`docker`**. By using docker command we will enter into the Bash. After entering into bash we have to use the script flow.tcl, because this .tcl file contains the steps that need to be executed in the OpenLane and along with the tcl file we need to use -interactive switch in order to perform step by step process. If not used interactive switch the whole flow i.e RTL to GDS will be executed once and the final report will be given. The command that we should use for this is **`./flow.tcl -interactive`**.Now OpenLane is opened and we can observe the change in prompt and now we have to input packages required to run the flow and for this we use the command **`package require openlane 0.9`**.

![Screenshot from 2024-04-29 09-36-22](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/89083deb-49db-4be9-8203-658f1f466c6c)

Now we need to select the design on which we are going to perform RTL to GDS flow, we will be having 30 to 40 designs that are pre-built in the design folder in openlane and we will be selecting "picorv32a.v" design for this project.Now in order to perform synthesis(first stage of the project) on this design, first we need to setup the design and for that the command will be **`prep -design picorv32a`**.

![design_prep_comp](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/dc62fda2-9b51-4544-a44f-f000f434ef34)
 
At the end of the terminal we can see that **Preparation is complete**.


### Review files after design prep and run synthesis

After Preparation is done a directory with current date will be created in the runs folder.And in that directory all the directorys that are needed to store the results , reports etc.. will be created.

![Screenshot from 2024-04-29 12-08-25](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/9f13846c-4f11-4eef-9ff0-8342675edeca)

Initially every directory will be empty because we haven't performed any operations on the design.But we will have a direcrory named tmp and it contains different types of files.One of the files will be "merged.lef" file, it contains metal layer level and cell level information.

![Screenshot from 2024-04-29 12-15-29](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/a1ab07ee-58cd-4f00-83dc-9ee39c0e03f8)


![Screenshot from 2024-04-29 12-18-08](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/baaf829a-0cce-4869-91b2-1b8f3558df47)

Now, it's time to proceed with the first step in the project. we need to perform Synthesis on the design. For this we need to use the command **`run_synthesis`**.Tool will take some time to perform synthesis, when completed it displays the **Synthesis was successful** message.

![synthesis_successful](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/7e6d7b96-a567-4089-b655-681cd4508fa0)


### Steps to charactirise Synthesis results

Now we need to find out the flipflop percentage in total cells. For this we use reports from Synthesis stage.

![flopcount](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/48d87542-8838-4d13-9b3c-6979e6f42983)


In the above image,we can see that the total no.of cells used in the design are 14876 and the count of D-flipflops in the design are 1613. So, the flipflop percentage is calculated as

**Flop Ratio = ((no.of flipflops) / (Total no.of cells))*100 = (1613/14876)*100 = 10.84%**

Before Performing Synthesis the reports directory was empty. After Synthesis the reports that are generated during synthesis will be stored in the reports directory.

![synthesis_reports](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/881d4439-a191-4c1c-a781-2e343d0b134e)




# Good FloorPlan Vs Bad FloorPlan and Introduction to Library Cells

## Chip FloorPlanning Considerations

### Utilization Factor and Aspect Ratio

In order to find out the Utilization Factor and Aspect Ratio, first we need to know how to define height and width of core and die areas.
- Core is an area in a chip which is used to place all the logic cells and components in a chip. It is the place where logic lies in a chip.
- Die is an area that encircles the core area and used for placing I/O related components.

![Screenshot 2024-04-29 162940](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/0579fc7f-009a-4e5b-a3e3-f51fecf1d1b2)


The height and width of core area will be decided by the netlist of the design. It will be based on the no.of components required in order to execute the logic and the height and width of the die area will be dependent on the core area height and width.

![Screenshot 2024-04-29 162542](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/e2885f48-30b3-4aad-b746-f0c3369440db)

For example, lets consider a netlist that is having two logic gates and two flipflops each having area of 1 sq.unit. The netlist contains 4 elements and the minimum total area required for the core area will be 4 sq.units. 

![Screenshot 2024-04-29 162459](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/34d0c495-66bb-4582-b15c-e6adf8619ab6)

![Screenshot 2024-04-29 162658](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/4c09360a-29d5-42f7-aec7-46c16614faaa)


**Utilization Factor** : Utilization Factor is defined as "The ratio of the core area occupied by the netlist to the total core area".For a good FloorPlan, The Utilization Factor should never be '1' because when the Utilization factor becomes '1' , there will be no place for adding additional logic if needed and it will be considered as a bad FloorPlan.

**`Utilization Factor = (Area occupied by netlist / Total core area)`**

**Aspect Ratio** : Aspect Ratio is defined as "The ratio of Height of the core to the width of the core". If the Aspect ratio is '1' , then the core is said to be in a square shape and other than '1' the core will be a rectangle.

**`Aspect Ratio = (Height of the core / Width of the core)`**

Lets consider the above mentioned example and evaluate some cases 

![Screenshot 2024-04-29 162721](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/55cf4d1f-628d-4f2a-a968-744a7be7470e)

In this case, when calculated 
- Utilization factor = (4 squnits)/(4 squnits) = 1
- Aspect Ratio = (2 units)/(2 units) = 1 //The core is in a square shape.


![Screenshot 2024-04-29 162810](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/5b4ef1fb-2d73-4819-95c7-d3c36de576fd)

In this case, whwn calculated

- Utilization factor = (4 squnits)/(8 squnits) = 0.5
- Aspect Ratio = (2 units)/(4 units) = 0.5 //The core is in a rectangular shape.


![Screenshot 2024-04-29 165339](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/b8da70b3-81d2-4607-94c6-e130faf9b7ea)

In this case , when calculated

- Utilization factor = (4 squnits)/(16 squnits) = 0.25
- Aspect Ratio = (4 units)/(4 units) = 1 //The core is in a square shape.


### Concept of pre-placed cells

The concept of pre-placing cells is nothing but reusing already designed blocks by not designing them again and again. The most commonly used pre-placed blocks are Memory , comparators , Mux etc.. , These blocks can be called as Macros (or) I.P's .We need to place these macros very carefully in such a way that if these blocks are more connected to input pins, then we should place these close to those input pins. These should be placed in a way such that the wiring length should be decreased.

The term Pre-placed refers to "Placing those blocks prior to placement stage that is in Floorplan stage. After placing those blocks in Floorplan stage we need to define some placement blockages in order to avoid Placing of other standard cell near to those blocks by the tool during placement stage. By using this pre-placed cells the Time-to-Market can be reduced.

![Screenshot 2024-04-29 173001](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/15833499-734d-4f4f-96b7-e87b51bacfec)


### De-coupling Capacitors

Generally these pre-placed blocks will be high-power draining blocks. In some cases, the power they recieve from the power source will not be sufficient for them to perform switching i.e the signal will not be in the range of its noise margin because there will be a voltage drop in the inter-connecting wires. In this case, the De-coupling Capacitors comes into the picture. 

![Screenshot 2024-04-29 180454](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/16730df5-6ed5-4278-84e1-a73b082a9acc)

These De-cap cells will be placed near to the blocks that will drain high power. When there is no switching is being performed the De-cap cell will be connected to power source and gets charged to its high level and when the switching is being performed the De-cap cells will be connected to the blocks and the power required for the block will be supplied by the De-cap cell, and when ever the switching stops again the De-cap cell will start to getting charged. This is the working of De-cap cells and these cells plays a crucial role in the circuit design.

![Screenshot 2024-04-29 180434](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/ca65ac68-b354-4a3b-acd3-ebd001c9d077)


### Power Planning

In the previous section we used De-cap cells to manage power for different blocks.But Decap cells have some limitations such as Leakage power and increase in the area of chip. To overcome these we use a technique called Powerplanning. In some areas of the chip when there is more  switching happening, two tyoes of phenomena can occur
- Voltage drop
- Ground bounce

![Screenshot 2024-04-29 220148](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/e35764ce-4a3d-4348-829b-97467e7ae641)

**Voltage drop** : When a group of cells are simultaneously switching from 0 to 1, then every cell needs the power and In case the power is supplying from one source, there may occur the shotage of power and drop in the input voltage happens at that place. This is called as "Voltage Drop". The problem occurs only when the voltage level goes below the noise margin.

![Screenshot 2024-04-29 220418](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/f1279b81-fd52-4693-aa83-2e871c70b96c)

**Ground Bounce** : When a group of cells are simultaneoisly switching from 1 to 0, then every cell dumps the power to th ground simultaneously to the same ground pin. In this case the ground instead of being at 0 experiences a short rise in the voltage and this is called as "Ground Bounce".The problem occurs only when the voltage level goes above the noise margin.

![Screenshot 2024-04-29 220249](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/239dc9f3-88d5-46d1-ab4d-710e87686f8e)

In order to avoid these abnormalities, a technique called Power Planning is used. In this technique two different Power mashes are used, one for Vdd and another one for Ground.These meshes are prepared by using top two metal layers because they should have less voltage drop. These meshes will be spread across the design and are connected to multiple sources of Vdd and Ground.

![Screenshot 2024-04-29 220510](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/edd194dd-6580-4ac8-a163-a0438714cb30)

With this technique whenever a cell needs power to switch from 0 to 1, it takes from nearest Vdd layer and if a cell needs to drain the power it will drain it to the nearest Ground Layer.

![Screenshot 2024-04-29 220626](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/7e67b60d-cc66-46d2-bb9f-60fd331c0fea)


### Pin placement and logical cell placement blockage

Pin Placement is one of the crucial step in the design process. Bad pin placement results increase in the length of wire used for connectivity, which inturn results in some adverse affects.
Pins should be placed in such a way that the required for connecting them to the blocks should be as less as possible. For example if an input pin is driving two blocks then that pin should be placed near to those two blocks.

Let's consider the below design

![Screenshot 2024-04-29 224141](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/c63b1efc-c7b0-4cdb-b453-cb88b30b8a3e)

For the above design the effective pin placement will look like as follows

![Screenshot 2024-04-29 224300](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/38417a02-524d-4aef-b54d-d9f67a246df1)

In the above pin placement, we can observe two things 
- The order of input pins and output pins is random. As already mentioned the pins should be placed based on the connectivity not based on the order.
- The pins used for clock signals are larger in size when compared to pins used for signals, this is because clock is one of the important signal in the design and delays and voltage drops in the clock signal leads to failure of the chip. That is the reason why we use higher metal layers for routing the clock in the design.

After finishing the pin placement, we should use placement blockages outside of the core area and inside of the die area inorder to avoid placement and routing tool using that space for placement and routing, because it is the area dedicated only for Pin Placement purpose.

![Screenshot 2024-04-29 225000](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/428dda61-6e63-4c8a-b11f-51c5f7da5cb9)


### Steps to run floorplan using OpenLANE


For Floorplan to run smoothly, as a designer we should take care of some switches, that makes changes to the floorplan when changed. For example Utilization factor and aspect ratio are also part of switches. Designer should cross check these switches before initializing floorplan whether they are alligned with the project or not. Below image shows different types of switches in floorplan stage.

![floorplan_switches](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/e31bdee9-2776-4d28-9e7e-c036b3378b03)


![floorplan tcl](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/a666b97c-cb76-4b4e-9c8a-3995db52f61a)

In the OpenLane lowest priority is given to system default(Floorplanning.tcl) and the second highest priority will be given to config.tcl and the highest priority will be given to PDK_varient.tcl for considering the values for switches.


### Review Floorplan files and steps to view floorplan

After confirming that all the switches are as per requirement, now we should executr a command **`run_floorplan`** , in order to start the floorplan stage.

If any errors occur during the floorplan stage it will display those errors.If it does not display any errors then our floorplan stage has succesfully completed.

![floorplan_done](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/d8ffd0cf-245b-47e1-b9c9-47b5352811c9)

After completion of the floorplan we can check the report generated by the tool and check some of the aspects like die area etc.. , but in order to view the design in GUI we should use MAGIC tool.

![Floorplan_report](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/7b320946-dfe0-4f09-a673-20727517a8a7)

In order to enter into the MAGIC tool we need to use the command

**` magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.floorplan.def &`**

And in GUI floorplan looks like this![floorplan_layout(magic)](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/4abb51b3-dbbf-4abe-bdd5-fe9d1c7557ce)


### Review Floorplan layout in magic

While in the GUI, to allign the design to the middle of the screen. First we need to select the whole design by pressing S in the keyboard and then V in the keyboard.

In order to zoom to any particular area first left click the mouse and select the area to zoom and then right click again, and then press Z in the keyboard to zoom in the selected area.

In order to know the details of any cell in the design, just move the cursor to that cell and press S to select the cell and then in the window of tkcon enter the command "what" then it will displey the details of the selected ine.

![vertical_io_pin](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/a28b636e-8614-4f03-85bc-3d715aaab4ec)


![horizontal_io_pin](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/b5d1258f-6447-4f2c-9af0-515cc752618e)


![Decap_cell](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/87d6e43b-79b7-4d1b-9368-73ce6702bf8c)



## Library Bindidng and Placement

### Netlist binding and initial place design

In the netlist every element has its own shape, for example And gate has a different shape and or gate has a different shape. But in a library every element has only a square or rectangle shape. A Library consists of every elements that can be readily used and also the elements comes with their respective properties such as area, delay etc.. . We will have different versions of the same element with different properties.

![Screenshot 2024-04-30 152912](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/f3aa46fa-675b-425a-b871-6073429312bd)


![Screenshot 2024-04-30 152937](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/ed3e79b7-5bc0-4a50-a555-7622a1d3e5f0)

In the above picture we have 3 different sets of same elements. The elements which are larger in size are faster but occupies larger area and the smaller set will occupy less area but are slower when compared to larger ones.


### Optimize placement using estimated wire-length and capacitance

During Placement we should definitely consider the estimated wire length and place the cells according to it. Wire length is estimated by calculating the distance from input source of those cells and the distance to the output sinks that are being driven by them. 

For above example tool will place the blocks by using the estimated wire length as shown in the below figure

![Screenshot 2024-04-30 154924](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/f60da452-6c6d-4304-8108-726e41852c30)


### Congestion aware placement using replace


After successful Floorplanning, the next step in the design process is Placement. Placement stage will consist of two stages 
- Global Placement - In Global Placement stage tool decides the places for all standard cells in the design.
- Detailed Placement - In Detailed Placement stage the tool places all the standard cells in their designated places and legalization of the Placement will be done. Legalization is nothing but making sure that standard cells are not overlapped on each other in the design and are placed with in the site rows of the design.

In order to start the placement we need to use the command **`run_placement`**.

After Placement is done to check whether the cells are placed correctly or not, we need to check GUI and that will be done using MAGIC tool with the following command

**`magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def &`**

![Screenshot from 2024-04-30 22-13-00](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/a5a4b928-7bff-4c9f-bef4-408367312c06)


![Screenshot from 2024-04-30 22-14-10](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/9a284840-6402-40f6-aa1c-9c6c50cb1909)


![Screenshot from 2024-04-30 22-15-57](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/378e46cd-3f9c-4176-8695-2a739af85bba)



# Design library cell using Magic Layout and ngspice characterization


## Inception of Layout and CMOS fabrication process


### Lab steps to create std cell layout and extract spice netlist


We need to extract the spice netlist from the given Inverter from MAGIC Tool inorder to spice simulation in ngspice tool.

First we need to create an extraction file of the inverter. we can do this by using the command **`extract all`** in the tkcon window. This will create an extracted file in the vsdstdcelldesign directory.

![extracted](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/5044221d-1571-4f26-938f-61d2e3aeceab)

Next we need to create a spice file using this extracted file to use within the ngspice tool.For this the command will be

**`ext2spice cthresh 0 rthresh 0`**, this will not create any new file. 

![tkcon](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/4e4a6585-a209-4a4d-9ab6-ac933d074d77)

After that use command **`ext2spice`** , this will create a spice file in the vsdstdcelldesign directory.

![spice](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/0a8ba608-df8d-412d-9b32-09d2d9d6b24a)

![spice_file](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/37c0bd40-8f32-4f2f-a709-65811dccd312)




## Sky130 Tech File Labs


### Lab Steps to create final SPICE deck using Sky130tech


After extracting the SPICE file, we need to update it according to the design.

![Screenshot from 2024-05-02 11-36-21](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/476c1e09-654f-4853-942f-b30616fb74f8)

After that we need to run the SPICE file in the ngspice tool by using the command  **`ngspice sky130_inv.spice`**

![Screenshot from 2024-05-02 11-38-19](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/9fcf36ae-e6dd-46f3-8204-c4249a38ed22)

Now we need to verify the plot of output vs time, we need to use the command  **`plot y vs time a`**

![Screenshot from 2024-05-02 11-49-54](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/bf215ce3-1c35-406a-b93e-baedbfbd2def)



### Lab Steps to characterize the Inverter using sky130 model files


From the plot that we got from ngspice, we need to characterize four parameters of the Inverter.

- **Rise time** : It is the time taken for the output waveform to go to 80% of its max value from 20% of its max value.

  x0 = 6.16138e-09, y0 = 0.660007

  x0 = 6.20366e-09, y0 = 2.64009

  From the above values, Rise time = 0.0422 ns

- **Fall time** : It is the time taken for the output to fall from 80% of its max value to 20% of its max value.

  x0 = 8.04034e-09, y0 = 2.64003

   x0 = 8.06818e-09, y0 = 0.659993

    From the above values , Fall Time = 0.0278 ns

- **Propogation Delay** : It is the time taken for the 50% of transition from 0 to 1 at the output for the 50% transistion from 1 to 0 at the input side.

  x0 = 2.18449e-09, y0 = 1.64994

  x0 = 2.15e-09, y0 = 1.65011
     From the above values , Prop Delay = 0.034 ns

- **Cell Fall Delay** : It is the time taken for the 50% of transition from 1 to 0 at the output for the 50% transistion from 0 to 1 at the input side.

  x0 = 4.05432e-09, y0 = 1.65

  x0 = 4.05001e-09, y0 = 1.65

   From the above values , cell fall delay = 0.0043 ns

  We have succesfully characterized the Inverter, now we should create a LEF file.



  ### Lab Introduction to Sky130 pdk's and steps to download labs

  
  To download the lab files, being in the home directory use the command

  **`wget http://opencircuitdesign.com/open_pdks/archive/drc_tests.tgz`**

  Now you have downloaded the zip file. To extract the labs from the zip file use the command

  **`tar xfz drc_tests.tgz`**

  In the downloaded files , **`.magicrc`** file serves as the start-up script for MAGIC.

  ![Screenshot from 2024-05-02 14-46-09](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/5ff1b106-2271-4497-b7ec-07fd1bb3bd34)

  ![Screenshot from 2024-05-02 15-07-12](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/27f975da-cdff-4964-b65a-95699b11b791)



  ### Lab Introduction to Magic and steps to load Sky130 tech-rules


  Use the command **`magic -d XR`** to open the Magic tool

  ![Screenshot from 2024-05-02 15-16-02](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/dd47ceb4-4e8f-48db-a3c2-dd5fe5b88165)


  Now, select an area in the gui and guide the pointer on to the metal 3 layer and press P. The selected region will be filled with metal 3. Now in tkcon terminal type the command **`cif see VIA2`** , The metal 3 filled area will be filled VIA2 mask.

  ![Screenshot from 2024-05-02 15-44-45](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/644585de-de5d-412e-ac95-a16ad73e0d94)



 ### Lab exercise to fix Poly-9 error in Sky130 tech file


 Now, lets work on the poly.9 file. Load it into the magic tool by using the command **`load poly.mag`**  in tkcon terminal.

![Screenshot from 2024-05-02 23-54-49](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/be29d16e-1f2a-4271-909c-0ae05afa63a9)


 Check for the spacing between Poly resistor and poly in the layout and compare it with the actual value in the Skywater website. In the image below we can clearly see the error in spacing 
 between them. So now lets resolve it

![Screenshot from 2024-05-03 00-00-55](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/fbd1f1be-aa19-4b33-84fb-212b324fb471)


![Screenshot 2024-05-03 003013](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/7ed03823-bd72-4f6b-a40b-79839afc77c8)


Open the Sky130a.tech file, which is in the drc_tests directory and check for poly.9 keyword and make the changes that are shown in the images below and save it.

![Screenshot from 2024-05-03 00-12-48](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/5cd46200-35d0-4ed9-9737-1d1b9c01c5fb)

![Screenshot from 2024-05-03 00-17-50](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/64791bb7-7edc-4901-83d7-6d1c16745747)

 Now again load the tech file by using the command **`tech load sky130A.tech`** , and again check drc by using command **`drc check`** in the tkcon terminal.

![Screenshot from 2024-05-03 00-20-00](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/1cc3741e-e424-466d-b74a-ae7d24b9be1b)



### Lab challenge exercise to describe DRC error as geometrical construct
 

Now load nwell.mag file into the magic and check for violations.

![Screenshot 2024-05-03 012127](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/950b4a6a-dcaf-4e57-bf12-e6bda2ff602a)

![Screenshot from 2024-05-03 01-45-28](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/7ac6a97a-1ac4-4572-924c-fd4389de7862)

In the above layout we have some violations, Open tech file and make changes as shown

![Screenshot from 2024-05-03 01-32-47](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/1ac46750-2e45-45d1-b9df-0099222e9e19)


![Screenshot from 2024-05-03 01-36-45](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/cb7f2348-0880-4012-a6f4-fe26663efefc)



### Lab challenge to find missing or Incorrect rules and fix them


After updating the tech file load it again and check for errors

![Screenshot from 2024-05-03 01-44-19](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/f0a0fda2-7cda-4bd9-aee6-542aa47c7a41)

Now after tapping the nwell violations are resolved.



# Pre-layout timing analysis and importance of good clock tree

## Timing modelling using delay tables

### Lab steps to convert grid info to track info


 Now to proceed further we will be needing LEF file of the Inverter cell. we need to extract if from the current Inverter cell.

 From PNR point of view, while designing standard cell set two things must be considered
 - The Input and output ports must lie on the intersection of the Vertical and Horizontal tracks.
 - The width of the standard cell should be an odd multiple of the track pitch and height should be an odd multiple of track vertical pitch.

 Open the tracks.info file to know more about tracks

 ![Screenshot from 2024-05-03 14-25-47](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/c2dfc964-c417-409b-a3c4-6f799d31741e)

 In the cell design input and output ports are on the li1 layer.We need to convert the grid into tracks.

 Open the tkcon window and give the command for grid according to the track file.

![Screenshot from 2024-05-03 14-41-05](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/3e6c78c1-4883-4858-8332-3cb6d451dfbb)

 Now we can see that both input and output ports are placed at the intersection of the tracks. Here our second condition also satisfies as 3 boxes are covered between the boundaries.

![Screenshot from 2024-05-03 14-43-07](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/11ac8a4d-9e0f-40fa-9b70-d07415a46ca2)



### Lab steps to convert magic layout to standard cell LEF


Now we need to extract the LEF file.First save .mag file by using the command **`save sky130_vsdinv.mag`** in the tkcon terminal.

![Screenshot from 2024-05-03 15-06-12](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/773a41d2-5c04-4481-bd6c-0342d686e21f)

Now open the saved .mag file using the command **`magic -T sky130A.tch sky130_vsdinv.mag &`**

![Screenshot from 2024-05-03 15-10-20](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/1b3829cf-0f5b-4bfc-bc41-089e1014f306)

Now in the tkcon terminal use the command **`lef write`** in order to create a LEF file.

![Screenshot from 2024-05-03 15-12-34](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/eebf9888-d9fa-4d53-a91c-d3998b1faaef)

 Now we can open the LEF file and go through it.

![Screenshot from 2024-05-03 15-15-52](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/85905d3c-ccdc-4f3a-ad3c-ccda8672cb70)

 
### Introduction to timing libs and steps to include new cell in synthesis


To proceed futher lets keep all the required files at single place thet is in src directory. First copy the extracted LEF file into src directory.

After LEF file we need to copy the required libraries, here we will have different types of libraries such as fast , slow, typical etc.. , we need to copy all those .lib files to src directory by using **`cp`** command.

  ![Screenshot from 2024-05-03 15-40-24](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/d5eda7fb-d80f-4ae2-b393-b5d3807c44d2)

Now we need to make some changes in the .config file as shown in the image

![Screenshot from 2024-05-03 16-01-12](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/635dbe20-014c-4eb8-a798-5c360be1f282)

After that we need to open bash using command **`docker`** being in openlane directory. And enter into the open lane and prepare the design as shown in figure. Once preparation is complete we need to use following commands 

**`set lefs [glob $::env(DESIGN_DIR)/src/*.lef]`**

**`add_lefs -src $lefs`**

![Screenshot from 2024-05-03 16-22-21](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/ae8f5081-bccd-4e13-a4c4-ebb9704e8d83)

And now again use the command **`run_synthesis`** and check whether it maps our custom vsdinverter or not.

![Screenshot from 2024-05-03 16-28-45](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/34d10bf0-9d1c-4795-af34-c74ebfc6a03f)

From the above figure we can see that synthesis was succesful and also we have 1554 instances of our vsdinverter. So this stage is successful.



### Lab steps to configure synthesis settings to fix slack and include vsdinv


 As we completed with synthesis stage, now we need to perform floorplan by using the following commands

 **`init_floorplan`**

 **`place_io`**

 **`tap_decap_or`**

![Screenshot from 2024-05-03 22-50-28](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/a035ddeb-bb1d-4ff5-8760-4bac7fcd62c6)

 Now as we done with Floorplan stage, we can proceed to placement stage by using the command **`run_placement`**

![Screenshot from 2024-05-03 22-51-48](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/2c16610e-7eac-4855-a2f5-8ee1d2fdc4b1)

 Now after the placement is done,lets check whether the cell that we have created is placed in the design. For this being in the placement directory we should use the command

 **`magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def &`**

![Screenshot from 2024-05-03 23-01-51](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/90cd7edf-09d6-4c67-94ac-baeb8ebe49b2)

![Screenshot from 2024-05-03 23-04-53](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/943b3346-a76b-4dbe-8079-b55e0c5da016)


 Clearly we can see that the cell that we have created " sky130_vsdinv" is placed in the design and now lets check whether it is alligned correctly with other cells or not by using the command **`expand`** in the tkcon terminal.

![Screenshot from 2024-05-03 23-06-49](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/0117d6f3-7935-4e30-84c6-5f97865d5b89)

 Yes,Its perfectly alligned!



 ## Timing analysis with ideal clocks using openSTA


 ### Lab steps to configure OpenSTA for post-synth timing analysis


Next step is to perform STA on the design. For this first we need to complete the synthesis stage. After synthesis is done some steps need to be followed.

First, we need to create a new file **`pre_sta.conf`** in the openlane directory.

![pre_sta conf](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/7847af0f-d514-4277-b0db-fcc622cc3646)

After that we need to create another file called **`my_base.sdc`** in the src directory which is picorv32a directory.

![my_base sdc](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/0df33cc7-db83-4611-88df-e9cb2e0d196c)

Now we need to use the command **`sta pre_sta.conf`** being in the openlane directory.

We can say that STA is succesful when the slack that we will get equals to that of synthesis stage.

![sta_done](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/e8f90b9c-848f-49e5-bd7b-a7a78a0f48fe)

As we can see that Slack is equal to of that we got in synthesis stage. So STA is succesful.



## Clock tree synthesis TritonCTS and signal integrity


### Lab steps to run CTS using TritonCTS


After improving the timing of the design, the previous design should be replaced with improved design by using the command

**`write_verilog //path of the previous design//`**

Now the design will get updated with the improved version.

Now we can start working on it, starting with Floorplan by using the same commands that were used before. After succesful completion of Floorplan we should do placement by using the command **`run_placement`**.

![placement_done](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/b2bc9249-6c30-4ea1-a953-e102ec8c77f1)

After placement is done, we can proceed with cts stage. To perform CTS we should use the command **`run_cts`**.

![cts_done](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/a022b59d-6f48-4806-8b35-97626c8bf5bf)

After completion of the cts we can observe that in the synthesis results directory a new **.cts** file is added. The newly added CTS file contains both the previous netlist and also the clock buffers that were added during the cts stage.

![cts v _file](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/b21c6b13-f78f-45c9-a2dd-57c6f06cf0e8)


## Timing analysis with real clocks using openSTA


### Lab steps to analyze timing with real clocks using OpenSTA


 To create a database in the openroad, first we need to enter into the openroad by using the command **`openroad`**.

 After that we need to follow the following list of commands in the openroad

 **`read_lef /openLANE_flow/designs/picorv32a/runs/04-05_21-50/tmp/merged.lef`**

 **`read_def /openLANE_flow/designs/picorv32a/runs/04-05_21-50/results/cts/picorv32a.cts.def`**

 **`write_db pico_cts.db`**

 **`read_db pico_cts.db`**

 **`read_verilog /openLANE_flow/designs/picorv32a/runs/04-05_21-50/results/synthesis/picorv32a.synthesis_cts.v`**

 **`read_liberty $::env(LIB_SYNTH_COMPLETE)`**

 **`read_sdc /openLANE_flow/designs/picorv32a/src/my_base.sdc`**

 **`set_propagated_clock [all_clocks]`**

**`report_checks -path_delay min_max -format full_clock_expanded -digits 4`**

![steps_to_db](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/b2490265-5cce-4c54-a1a5-e04d928df9f0)

![db_created](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/d4b47d98-eef0-4e16-8845-4196fb1eb75b)


After all these steps the db will get created and by using the last command we will get a timing report too.

![db_done](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/03755c81-1025-4938-8176-a493c63881f5)


### Lab steps to execute OpenSTA with right timing libraries and CTS assignment


To remove sky130_fd_sc_hd__clkbuf_1 from the list

**`set ::env(CTS_CLK_BUFFER_LIST) [lreplace $::env(CTS_CLK_BUFFER_LIST) 0 0]`**

To check the current value of CTS_CLK_BUFFER_LIST

**`echo $::env(CTS_CLK_BUFFER_LIST)`**

To check the current value of CURRENT_DEF

**`echo $::env(CURRENT_DEF)`**

To set def as placement def

**`set ::env(CURRENT_DEF) /openLANE_flow/designs/picorv32a/runs/04-05_21-50/results/placement/picorv32a.placement.def`**

To run cts

**`run_cts`**

To check the current value of CTS_CLK_BUFFER_LIST

**`echo $::env(CTS_CLK_BUFFER_LIST)`**



### Lab steps to observe impact of bigger CTS buffers on setup and hold timing


We need to follow the similar steps that we have followed earlier in the openroad.

**`read_lef /openLANE_flow/designs/picorv32a/runs/04-05_21-50/tmp/merged.lef`**

**`read_def /openLANE_flow/designs/picorv32a/runs/04-05_21-50/results/cts/picorv32a.cts.def`**

**`write_db pico_cts1.db`**

**`read_db pico_cts1.db`**

**`read_verilog /openLANE_flow/designs/picorv32a/runs/04-05_21-50/results/synthesis/picorv32a.synthesis_cts.v`**

**`read_liberty $::env(LIB_SYNTH_COMPLETE)`**

**`link_design picorv32a`**

**`read_sdc /openLANE_flow/designs/picorv32a/src/my_base.sdc`**

**`set_propagated_clock [all_clocks]`**

**`report_checks -path_delay min_max -fields {slew trans net cap input_pins} -format full_clock_expanded -digits 4`**

**`report_clock_skew -hold`**

**`report_clock_skew -setup`**

![Screenshot from 2024-05-05 06-23-26](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/10e89ad9-f9fd-4646-bf3a-b04e98980485)


![Screenshot from 2024-05-05 06-17-10](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/beee43d7-b727-41ad-b57e-c34c3879c155)



# Final steps for RTL2GDS using tritonRoute and openSTA


## Power Distribution Network and routing


### Lab steps to build power distribution network


After completion of CTS, now we need to lay down power distribution network(PDN) for the design and it is done by using the command **`gen_pdn`** .

![gen_pdn_command](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/5ce794df-a8a4-4d8c-a687-103a247b6b09)

![pdn_done](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/2e684127-62a7-4e3f-938f-14ce6b0570ad)

We can clearly see that "PDN generation was succesful".

![rails straps_info](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/4a2d278c-849e-4fb1-b906-d297b12c7401)

In the above figure we can see that the pitch of the standard cell rails is 2.720, which we have expected.


### Lab steps from power straps to std cell power

![Screenshot 2024-05-07 104244](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/9cecd9c1-5a25-4a26-851d-11f6ce4fbc49)

In the above figure we can observe the path through which power is delivered all the way to standard cells.

- The blocks that we can observe around the design are I/o pads and those with Red and Blue colours are Power Pads. Red pad is for power and the Blue one is for Gnd.
- Those blocks are connected to Power and Gnd Rings, which go around the design and supply power to straps.
- The vertical connections that we can observe for the rings are called Power Straps.
- From Power straps and Rings connections will be made to the Power rails. The standard cell will be placed in between these power rails. The height of the standard cells should be the multiples of the pitch of the rails in order to get power and gnd supplies accurately.

  This is the overview of the PDN structure.


### Basics of global and detail routing and configure TritonRoute
  

The Final stage in the flow is ROUTING. we can start routing by using the command **`run_routing`** .

![routing_done](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/1e136428-7ac7-4eed-b71d-5b3d754f08b4)

![no_violations](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/fcd6128c-86ba-4871-a904-0713a24f3c3b)

From tha above figures we can see that routing is done and it is done with 0 violations, So our routing is succesful but we can see the negative slack. We need to eliminate that negative slack for succesful completion of Physical design flow.

We can see the final layout in gui using magic tool by using the command 

**`magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read /home/vsduser/Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/04-05_21-50/tmp/merged.lef def read /home/vsduser/Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/04-05_21-50/results/routing/picorv32a.def &`**


![final_layout](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/6f8f6bcb-8d0f-45bb-a0c4-61ea2db92a15)



## References

* https://github.com/nickson-jose/vsdstdcelldesign
* https://github.com/google/skywater-pdk
* https://github.com
* Material provided in workshop


 
  

   





