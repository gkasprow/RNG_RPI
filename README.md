# RNG_RPI
RNG processing box based on FPGA and Raspberry PI
This module takes 4 gigabit streams from Random Number Generators, 
samples it with GTP transceiver and calculates statistics in real time in the FPGA.
Data are time-tagged with GPS time.
Data are then transferred to the RPI which sends them to the central server.
RPI is also responsible for FPGA update/configuration
This design is derived from NETV2 project
https://github.com/AlphamaxMedia/netv2-mainboard
Parts of schematics and routing were used.
