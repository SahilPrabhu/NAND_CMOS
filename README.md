# NAND_CMOS

![Basic-CMOS-Structure](https://github.com/SahilPrabhu/NAND_CMOS/assets/92974277/9fbb5c8a-e620-4e08-bce2-469bb9eff76b)

For two input NAND gate, if A and B are the inputs then its output Y = (A.B)’.
In NMOS network when we have AND operation between the two variables, then two NMOS transistors will get connected in series. And the output will be complement of it.
The PMOS network is dual of the NMOS network. In the NMOS network, if two transistors are connected in series then in the PMOS network, the two PMOS transistors will get connected in parallel

## Schematic using Cadence Virtuoso

![NAND Schematic](https://github.com/SahilPrabhu/NAND_CMOS/assets/92974277/704aaf18-f362-40d3-8ac3-aec5eb024006)

We use labels for all input and output pins and design the schematic layout of NAND Gate.

## Generating Symbol and Testing Functionality

![NAND Symbol](https://github.com/SahilPrabhu/NAND_CMOS/assets/92974277/3d0b2a37-6323-4d8e-a633-0ae59c4e1502)

We generate a symbol from the design and apply inputs in place of labels as Vpulse and Vdc. This helps us check functionality of our NAND gate using transient analysis in ADE L.
 
## Making the Layout using Layout XL in Cadence

![NAND Layout](https://github.com/SahilPrabhu/NAND_CMOS/assets/92974277/771617d8-29d8-47d7-93a0-0358d29a8d93)

As we can see the P&R has completed and it shows 0 DRC errors and LVS is also done succesfully.
