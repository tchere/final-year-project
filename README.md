
# 📘 Final Year Project: Measureing Rényi Entanglement entropy in 1-D Transverse Field Ising Model (TFIM) using Monte Carol simulation 

## 🔬 Overview

This project explores the **1-D Transverse Field Ising Model (TFIM)**—a foundational model in quantum many-body physics and quantum phase transitions. A key focus of this work is the **computation of entanglement entropy** using **Monte Carlo simulations**, enabling to understand more about the quantum critical behavior of the system.

## 🎯 Objectives

- Calculate **entanglement entropy**, especially **Rényi entropy** varying in different system size of TFIM
- Calculate the magnetization of 2-D classical ising model and 2-D tranverse field ising model
- Anylzing the critical behavior of those model
- Match the slope result with the Conformal field theory

## 🧮 Methods
- **Quantum Monte Carlo (QMC)** espeically on Metropolis and Wloff Algorithm
- imaginary time Replica trick (for Rényi entropy calculation)
- Visualization of entropy scaling and phase transition behavior

## Significant Result
- The simulation result with the transformed X axis match the theoretical result from the Conformal Field Theory (CFT), 
<p align="center">
  $$
  S_A^{n=2} = \frac{c}{3} \log\left(\frac{L}{\pi} \sin\left(\frac{\pi l}{L}\right)\right) + \text{const.}
  $$
</p>
