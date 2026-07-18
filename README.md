# Oscillator-based-Neuromorphic-computing

## Overview

**Oscillator-Based Neuromorphic Computing** explores unconventional computing paradigms that leverage the synchronization dynamics of coupled nonlinear oscillators to perform computation. Inspired by synchronization phenomena observed in biological neural systems, oscillator networks encode information in the phase relationships between oscillators, offering an alternative to conventional Boolean logic. This repository investigates both **VO₂ relaxation oscillators** and **CMOS Schmitt Trigger oscillators** for implementing logic functions and solving combinatorial optimization problems.

---

## Why Oscillator-Based Computing?

As conventional CMOS technology approaches its physical scaling limits, there is an increasing demand for computing architectures that are more energy-efficient and inherently parallel. Oscillator-based computing exploits the natural synchronization behavior of coupled oscillators, allowing computation to emerge from their collective dynamics rather than sequential logic operations. This makes oscillator networks a promising approach for next-generation neuromorphic and unconventional computing systems.

---

## Project Objectives

- Design and simulate **VO₂ relaxation oscillators**.
- Design and simulate **CMOS Schmitt Trigger oscillators**.
- Study synchronization dynamics in coupled oscillator networks.
- Implement oscillator-based **logic gates**.
- Solve **MaxCut optimization** problems using oscillator synchronization.
- Compare the computational characteristics of **VO₂** and **CMOS** oscillator implementations.

---

## Repository Structure

| Directory | Description |
| :-------- | :---------- |
| [`vo2/`](./vo2/) | VO₂ relaxation oscillator circuits, simulations, and synchronization-based applications. |
| [`cmos/`](./CMOS/) | CMOS Schmitt Trigger oscillator circuits, logic gate implementations, and optimization applications. |

---

## Tools

- Cadence Virtuoso
- KiCad
- Verilog-A

---

## References


1. D. E. Nikonov *et al.*, **"Coupled Oscillator Networks for Neuromorphic Computing,"** *Nature Electronics*.

2. M. Jerry *et al.*, **"Oscillatory Neural Networks Based on VO₂ Relaxation Oscillators,"** *Scientific Reports*, 2017.

3. J. Wang *et al.*, **"Phase Transition Devices for Neuromorphic Computing,"** *Nature Materials*.

4. S. Datta, **"Physical Ising Machines for Combinatorial Optimization,"** *IEEE Journal on Exploratory Solid-State Computational Devices and Circuits*.

5. Nikhil Shukla, Mohammad Khairul Bashar, *et al.*, **"Experimental Demonstration of a Reconfigurable Coupled Oscillator Platform to Solve the Max-Cut Problem,"** *IEEE Journal on Exploratory Solid-State Computational Devices and Circuits*, vol. 6, no. 2, pp. 116–121, 2020.

6. Nikhil Shukla *et al.*, **"Computational Models Based on Synchronized Oscillators for Solving Combinatorial Optimization Problems,"** *arXiv preprint*, arXiv:2206.05907, 2022.

7. Michel X. Goemans and David P. Williamson, **"Improved Approximation Algorithms for Maximum Cut and Satisfiability Problems Using Semidefinite Programming,"** *Journal of the ACM*, vol. 42, no. 6, pp. 1115–1145, 1995.
