# **Creating custom gates using qiskit pulse**
## **NPTEL: Quantum computing. IIT Madras** 


The project [report](https://github.com/SoumikSamanta10/Quantum-gate-using-qiskit-pulse/blob/deb4a6eda70d7bc5e33fbc86a67afd106e08040c/Creating%20custom%20gates%20using%20qiskit%20pulse.pdf) in the folder `Report'.

## **Project Description:**

A Quantum Circuit is a model for quantum computation, in which a computation is a sequence of quantum gates, measurements, initialization of qubits to known values, and possibly other actions. Quantum Circuit model allows user to only work at circuit level thus hiding the underlying physical implementation of quantum gates and measurements. Qiskit Pulse is a low level pulse-programming paradigm implemented as a module within Qiskit Terra. This gives user precise control over working at real quantum hardware level, the ability to calibrate and execute pulse, and read-out level instructions. In this paper we use Qiskit Pulse model to calibrate and create gates with high fidelity. We start by calibrating the qubit frequency of qubit 0 at IBMQ Armonk backend, accurately by frequency sweep method, which will later be implemented in preparing pulse schedule for our custom gate in section 5. We perform calibration of single qubit Hadamard Gate by defining and varying the pulse parameters, in different cloud-based IBM backends to higher fidelity. Finally, we create a single qubit custom gate ‘C’ and 2-qubit custom bellgate ‘BG’, and display the results from IBMQ Armonk and IBMQ Belem respectively. 
   

## **Key Results:**
•	Demonstrated Qiskit Pulse, low level pulse-programming paradigm implemented as a module within Qiskit Terra, which gives precise control over working at real quantum hardware level, the ability to calibrate and execute pulse, and read-out level instructions.

•	Calibrate and create gates with high fidelity, while started by calibrating the qubit frequency of qubit 0 at IBMQ Armonk backend, accurately by frequency sweep method, which implemented in preparing pulse schedule for our custom gate.

•	Perform calibration of single qubit Hadamard Gate by defining and varying the pulse parameters, in different cloud-based IBM backends to higher fidelity.

•	Create a single qubit custom gate ‘C’ and 2-qubit custom bellgate ‘BG’, and display the results from IBMQ Armonk and IBMQ Belem respectively




## **References:**

[1] Pulse (qiskit.pulse) - Qiskit 0.44.2 documentation


