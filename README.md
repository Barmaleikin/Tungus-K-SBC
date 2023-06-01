# Tungus-K-SBC
A simple and naive FPGA-assisted Single Board Computer project

One may note during software emulation of non-binary hardware that significally ammount of run time wasted by conversion between different numbers bases: binary-to-other and vice versa. This project is an attempt to build a hardware, which uses a special techniqe to eliminate or reduce the overhead.

FPGA is used to buidl a special functional unit (FU) to implement kibnd of harware number-base converter, which acts also as an arithmetics unit.
