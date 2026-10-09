# QAOAforOFDMASystemSumRateMaximization

This Jupyter Notebook (.ipynb) implements the Quantum Approximate Optimization Algorithm (QAOA) for sum transmission rate maximization in an uplink OFDMA network through joint transmit power optimization. Each user's transmit power is discretized into 16 levels and encoded using four qubits. The implementation uses PennyLane for quantum circuit simulation, incorporates power constraints through a penalty-based cost Hamiltonian, and employs a classical optimizer to update the QAOA parameters. 
