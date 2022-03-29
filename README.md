# ICDC2019_prelim_univ_cell_based

## Description

This is a project for 2019 ic design contest university group, which implements an image convolutional circuit.

## Executing Program

A testbench code (./testfixture.v) and several golden data were provided by the contest host.  
The RTL behavior of the chip can be simulated by using the following command: 
```
$ ncverilog -f rtl_01.f +access+r
```
To see the simulated wave form, use nWave
```
$ nWave &
```
to read the fsdb files generated by ncverilog.  

The gate-level circuit can be tested by using the following command:
```
$ ncverilog -f rtl_02.f +access+r
```

## ICD Contest Host
For more information, please download the spec and problem description at:  
http://icdc.ntust.edu.tw/2022/index2.php?page=OldExams

## Authors

Contributors names and contact info

Hao-Wei, Liang (b07502022@ntu.edu.tw) 

Yen-An, Lu (b07501003@ntu.edu.tw)

