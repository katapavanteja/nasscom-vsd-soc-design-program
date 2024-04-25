# nasscom-vsd-soc-design-program
# Contents
 1) [Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#sky130-day-1---inception-of-open-source-eda-openlane-and-sky130-pdk)
    - [How to talk to computers](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#how-to-talk-to-computers)
       - [Introduction to QFN-48 Package, chip, pads, core, die and IPs](https://github.com/katapavanteja/nasscom-vsd-soc-design-program/edit/main/README.md#introduction-to-qfn-48-package-chip-pads-core-die-and-ips)
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

