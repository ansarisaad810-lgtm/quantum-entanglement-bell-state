# Bell State Simulation using Qiskit

A Python project that creates a 2-qubit **Bell State** (quantum entanglement) using the Qiskit quantum simulation library.

## Project Description

This project builds a small quantum circuit with two qubits:

1. A **Hadamard gate** puts the first qubit into superposition (a mix of 0 and 1).
2. A **CNOT gate** entangles the second qubit with the first.
3. Both qubits are **measured** 1000 times on a simulator.

The output shows only `00` and `11`, each appearing about 50% of the time. The qubits always agree with each other, which demonstrates quantum entanglement.

## Technologies Used

- Python 3
- Qiskit
- Qiskit Aer (quantum simulator)
- Matplotlib
- Google Colab

## How to Run

### Option 1: Google Colab (no installation needed)
1. Open [Google Colab](https://colab.research.google.com).
2. Click **File → Upload notebook** and select `bell_state_project.ipynb`.
3. Click **Runtime → Run all**.

### Option 2: On your own computer
1. Install Python 3.9 or newer.
2. Install the libraries:
```
   pip install qiskit qiskit-aer matplotlib
```
3. Run the script:
```
   python bell_state.py
```

## Expected Output

```
Results: {'00': ~500, '11': ~500}
```

A bar chart shows two roughly equal bars for `00` and `11`. Exact counts vary slightly on each run because quantum measurement is random.

## Key Concepts Covered

- Qubits, superposition, and entanglement
- The Hadamard and CNOT gates
- Building, simulating, and measuring a quantum circuit in Qiskit

## Author

Your Name
