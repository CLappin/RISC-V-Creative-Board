## RISC-V Creative Development Board FlashPro Express Programming Files

Sample Mi-V FlashPro Express files for FPGA designs for RISC-V Creative board. The RISC-V Creative Development Board includes a IGLOO2 M2GL025 FPGA.

### FlashPro Express
This folder contains default build, exported programming files, there is a choice to use an AXI or AHB Core based design. Each (.job) file is capapble of programming your target device using the standalone installer for FlashPro Express which can be found [here](https://www.microsemi.com/product-directory/programming/4977-flashpro#software).
Please note that you only need to install this standalone version of FlashPro Express for Libero v12.3 if you do not have Libero tools installed. The programming procedure is as follows:

### Programming the Device using FPExpress
---------------------------------------------
1. Download or Clone this repository to get the contents of FlashPro_Express_Projects.
2. Power-up your board and connect it to your programming device running FlashPro Express.
3. Launch FPExpress v12.3 and wait for it to load.
4. Click into Project from the top left bar and select "New Job Project from FlashPro Express Job"
5. For "Programming job file:" navigate to your FlashPro_Express_Project/Programming_Files directory and select the (.job) programming file you want to program your board with.
6. For "FlashPro Express job project location:" select the FlashPro_Express_Projects folder you have downloaded with this project.
8. Click OK, wait for the new window to pop-up.
7. From the bottom left drop-down menu select the PROGRAM option if it's not selected by default and click RUN. Wait for device to be programmed.

### Target Hardware
The RISC-V Creative Development Board includes a IGLOO2 M2GL025 FPGA. Details of the features available for this development board are available [here](https://www.microsemi.com/products/fpga-soc/design-resources/dev-kits/risc-v-creative-board).

The TickTackToe example uses a [TFT Touch Shield for Arduino, with Resistive Touch Screen](https://www.adafruit.com/product/1651)

### Target Mi-V CPU
Details of the features of Mi-V CPUs are available [here](https://github.com/RISCV-on-Microsemi-FPGA/CPUs).