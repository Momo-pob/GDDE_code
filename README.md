# GDDE_code
This is an introduction to the program Matlab code about GDDE

GDDE-optimization-algorithm

A dimensional complementarity-based periodic game differential evolution for numerical optimization and real-world challenges

Authors：Pengpeng Shang, Sanyang Liu, Yiguang Bai, Yudong Gonga, Chunfeng Wang

Main.m: The main program that runs

BoundConstraint.m：Population upper and lower bound processing program

Initial.m: Population initialization program

cec17_func.mexw64: CEC2017 benchmark test suite
LSOPs: large-scale optimazition problems
cec22_func.mexw64: CEC2022 benchmark test suite

Modify directly "fhd= str2func('cec17_func')" in Main.m to call other benchmark tests

Modify the funcnum of Main.m to switch function calculations

Simply modifying other parameters of Main.m can achieve the desired function
