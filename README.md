# Diff-Probe

![Circuit Board](/Pictures/pcba.jpg)

## Overview
The goal of this project was to create a relatively cheap and simple differential probe, intended mostly for hobbyists and makers.

## Specification
This probe has a voltage rating of ±500V on each input, which means a differential rating of ±1000V.  
Depending on the opamps the usable bandwith can be in excess of 10 MHz.  


The power supply is done via a USB-C connector and a DC/DC converter for galvanic isolation.

I've tried to different opamps, which whom the Diff-Probe can reach the following bandwidths:

| Opamp  | Opamp bandwith | Probe bandwidth | Cost per opamp |
| -----  | -------------- | --------------- | ------ |
| TL072  | 3MHz           | ~1MHz           | <0.20$ |
| AD8039 | 350MHz         | ~18MHz          | ~2.50$ |

## Cost
All the components cost about 20 to 25 USD with the more expensive opamp option.

## Housing
<img src="/Pictures/assembled_1.jpg" width="200"> <img src="/Pictures/assembled_2.jpg" width="200">  
This housing is printed in ABS for durability, but can easily be printed in PLA.  
It is held together with two M3x10 and one M2x12 screw, which are each screwed into heat set inserts.  
The M2 screw can be omitted, but the housing will probably not fully close on that side and leave a small gap.

Assembly of the Diff-Probe:  
<img src="/Pictures/PXL_20230820_140837396.MP.jpg" width="200">  


## Files
[Schematic](/PCB/OUTPUT/Diff-Probe_A00_SCH.PDF)  
[Assembly Drawing](/PCB/OUTPUT/Diff-Probe_A00_PCBA.PDF)  
[Bill of Material](/PCB/OUTPUT/Diff-Probe_A00_BOM.xlsx)  

[CAD for Housing](/Housing/)
