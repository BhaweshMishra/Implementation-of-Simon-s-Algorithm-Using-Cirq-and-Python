
# Implementation of Simon's Algorithm Using Cirq and Python

This project shows the implementation of Simon's Algorithm. If we are given a 2-1 function f:{0,1}<sup>n</sup> —> {0,1}<sup>n</sup> such that there is a secret string s such that: f(x) = f(x xor s). In the cases of classical algorithms, the time complexity will be O(2<sup>n</sup>) since we need to apply brute force and check for most of values of x and wait for a collision. However by using Simon's Algorithm we can reduce the time complexity to O(n)

## Simon's Algorithm Working
Truth Table:

![image](https://user-images.githubusercontent.com/77975276/228043131-8c566430-043e-4dd7-9f46-aad1a7d49621.png)


Quantum Circuit:
![image](https://user-images.githubusercontent.com/77975276/228045354-668af469-cb87-40b9-aeef-f0040a6e358e.png)

To implement the gate:
The gate can be implemented by generating its gate matrix using the truth_table_to_quantum_gate_matrix function. More information on this function is given in 
https://github.com/BhaweshMishra/Quantum-gate-matrix-generator




## Installation

The Python program is written in a Jupyter Notebook for easier and cell wise implementation. 

The program requires the NumPy and Cirq module to run.

Incase Numpy module is not on your device, install it using

```bash
  pip install numpy
```
    
Incase Cirq module is not on your device, install it using

```bash
  pip install cirq
```

Download the simons_algo_implementation.ipynb file and run it.
## About the file
Download the Jupyter Notebook. The step wise working of the program is written in the comments.
