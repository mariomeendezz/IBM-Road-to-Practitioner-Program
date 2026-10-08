# BasQ–IBM Road to Practitioner — Third Edition

This repository contains practical assignments from the third edition of Road to Practitioner (R2P). Basque Quantum (BasQ) and IBM provide this training program. The program helps participants develop their knowledge of quantum computing and Qiskit.

The program has two phases and six modules, from September to November 2026. It includes theory lessons, practical exercises, and a final project called the Capstone Project.

For more information, see the [official program description](https://www.basquequantum.eus/en/news/basq-ibm-road-practitioner-3rd-edition).

## First assignment: Introduction to Qiskit

The [Introduction notebook](1-%20Introduction.ipynb) shows how to build a quantum circuit, prepare it for a quantum device, execute it, and examine the results.

The assignment includes Bell states and GHZ states, which are quantum states with entangled qubits. It examines qubit correlations and the effects of noise as the number of qubits increases. It also includes the quantum Fourier transform (QFT), which converts quantum states from the computational basis to the Fourier basis.

## Second assignment: Optimization with QAOA

The [QAOA notebook](2-%20QAOA.ipynb) uses the quantum approximate optimization algorithm (QAOA) to solve a Max-Cut problem. Max-Cut divides the vertices of a graph into two groups. The objective is to get the largest number of edges between the groups.

The assignment includes graph construction and conversion of the graph into a Hamiltonian, which represents the cost function. It also includes circuit transpilation, parameter optimization, and analysis of the results. The final part examines whether two colors are sufficient to color the graph so that connected vertices have different colors.
