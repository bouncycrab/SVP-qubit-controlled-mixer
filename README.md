this is a sample workflow to map an input basis to be solved via (classically simulated) quantum computer. One can edit the classical simulator to use qiskit's quantum hardware instead since this is in qiskit.

there are two methods inside, one uses a penalty method to penalize zero-vector qubit encoding, while the other one uses a controlled mixer method to result in amplitudes of certain states to remain constant.

both results do rather poorly
