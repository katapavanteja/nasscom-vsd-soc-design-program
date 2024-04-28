# nasscom-vsd-soc-design-program
# Contents
1) Day-1: [Inception of open-source EDA, OpenLANE and Sky130 PDK](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#sky130-day-1---inception-of-open-source-eda-openlane-and-sky130-pdk)
    - [How to talk to computers](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#how-to-talk-to-computers)
       - [Introduction to QFN-48 Package, chip, pads, core, die and IPs](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-qfn-48-package-chip-pads-core-die-and-ips)
       - [Introduction to RISC-V](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-risc-v)
       - [From Software Applications to Hardware](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#from-software-applications-to-hardware)
    - [SOC Design and OpenLane](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#soc-design-and-openlane)
       - [Introduction to all components of open-source digital asic design](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-all-components-of-open-source-digital-asic-design)
       - [Simplified RTL2GDS Flow](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#simplified-rtl2gds-flow)
       - [Introduction to OpenLANE and Strive chipsets](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-openlane-and-strive-chipsets)
       - [Introduction to OpenLANE detailed ASIC design flow](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-openlane-detailed-asic-design-flow)
    - [Get familiar to open-source EDA tools](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#get-familiar-to-open-source-eda-tools)
       - [OpenLane Directory Structure](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#openlane-directory-structure)
       - [Design Preparation Setup](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#design-preparation-setup)
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


  

 
  

   





