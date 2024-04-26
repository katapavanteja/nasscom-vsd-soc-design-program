# nasscom-vsd-soc-design-program
# Contents
 1) [Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#sky130-day-1---inception-of-open-source-eda-openlane-and-sky130-pdk)
    - [How to talk to computers](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#how-to-talk-to-computers)
       - [Introduction to QFN-48 Package, chip, pads, core, die and IPs](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-qfn-48-package-chip-pads-core-die-and-ips)
       - [Introduction to RISC-V](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-risc-v)
       - [From Software Applications to Hardware](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#from-software-applications-to-hardware)
    - [SOC Design and OpenLane](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#soc-design-and-openlane)
       - [Introduction to all components of open-source digital asic design](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-all-components-of-open-source-digital-asic-design)
       - [Simplified RTL2GDS Flow](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#simplified-rtl2gds-flow)
# Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK
##  How to talk to computers
###   Introduction to QFN-48 Package, chip, pads, core, die and IPs

**Aurdino Board**: The image below is an Aurdino Microcontroller Board. Here we focus more on the encircled area, which contains the 'Microprocessor',that we will be designing from abstract level till fabrication level by using RTL to GDS flow

![Screenshot 2024-04-25 120653](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/assets/168015988/c8ff1aa9-59fb-4053-a00a-d7378a40045f)

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



 (2) **Floor Planning** & **Power Planning** :
 - Floor Planning is a stage where the position of the components on the chip will be decided by keeping the area of the chip as minimal as possible by following a set of rules.
 - During the Floor Planning Stage itself the position of I/O pins,ports,pads will be determined.


 - In Power Planning stage the Power supply network i.e VDD & GND of the chip will be laid out. During Power PLanning 3 components Power Rings , Power Straps , Power Pads will be laid out.
 - For Power Network Top Metal Layers will be used because the Power Network should have minimum delay as possible and the top layers of metal will have the low resistance, So they are used.


(3) **Placement** :
- In Placement stage the components are placed within the areas planned during the FloorPlanning Stage.
- Along with them Standard Cells that are required in the design are also placed within the cell boundaries.
- Placement will be performed in 2 stages. They are Global Placement and Detailed Placement.
- During Global Placement the Standard cells may overlap and does not follow the Placement Rules.
- In Detailed Placement every standard cell will be placed in its optimal position by following the Placement rules.


(4) **CTS**(Clock Tree Synthesis) :
- Before Performing Routing of the signals, we should perform Clock Routing.
- While Routing the clock tha major problem is CLock Skew.
- Clock Skew is the difference in time taken for the clock to reach two different destinations in the design.
- In order to eliminate the clock skew, we should deploy the technique called **Symmetric Tree Structure**.
- There are different types of Symmetric Tree Structures. They are H-tree,I-tree,X-tree etc...



(5) **Routing** :
- Afetr the clock routing is done, now signals must be routed.
- Router uses the remaining metal layers and makes conections in the design.
- Routing will be carried out in 2 stages.They are Global Routing and Detailed Routinng.
- In the stage of Global Routing, the tool generates a Routing guide by following the instructions given in the PDK.
- In the stage of Detailed Routing, actual routing will be done according to the guide generated in the Global Routing Stage.



(6) **Sign-off** :
- After Routing is done, the chip will be considered as completed and during Sign-off stage different types of checks will be performed.
- Physical Verification Checks : Design Rule Check(DRC) , Layout Vs Schematic(LVS)
- In DRC, the chip will be verified for the violations in the Design Rules provided by the PDK.
- In LVS, the chip will be checked for the functionality whether it matches to the gate level netlist functinality.
- Timing Checks : Static Timing Analysis(STA)
- During STA, the design is checked for Timing violations.
  

   





