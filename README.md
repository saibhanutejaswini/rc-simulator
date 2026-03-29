# RC Circuit Charging and Discharging using LTspice

## Project Overview
This project demonstrates the charging and discharging behavior of a capacitor in an RC circuit using LTspice simulation and C programming calculations.

The capacitor voltage changes exponentially over time, which depends on the resistance (R) and capacitance (C) values. The simulation results are verified using mathematical formulas implemented in C code.

## Objective
To understand the transient response of an RC circuit and verify theoretical results using simulation and programming.

## Components Used
- Resistor (1k ohm)
- Capacitor (100 microfarad)
- Voltage source (5V pulse input)

## Software Used
- LTspice (for circuit simulation)
- C Programming Language (for mathematical verification)

## Theory

Time constant:
τ = RC

Charging equation:
Vc(t) = V(1 - e^(-t/RC))

Discharging equation:
Vd(t) = V e^(-t/RC)

Where:
R = Resistance
C = Capacitance
t = Time
V = Supply voltage

## Result
The LTspice graph shows exponential increase and decrease of capacitor voltage during charging and discharging.

The calculated values from C program match the simulation output.

## Learning Outcome
- Understanding capacitor charging and discharging behavior
- Learning LTspice simulation basics
- Implementing mathematical formulas using C programming
- Verifying theoretical and simulated results

## Author
Sai Bhanu Tejaswini
