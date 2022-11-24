# One way vs Two way Repeaters 
## A comparison

Using Netsquid to compare the two repeater schemes.

Nov 24 2022: Added the simple_link.py example - a netsquid example for the meet in the middle protocol. The code requires many to-dos for it to be usable for our case-

TO-DOS:
1. Extend the entire program to arbitrary number of qubits. (a) Look into the class NetworkProtocol function run. Currently the code has run requests hard-coded for 3 qubits. Need to be changed to arbitrary number of qubits. (b) Add more memory qubits in qproc
2. Extend the formulation to multi-node. This eill require creating a factory of such setups
3. Metric for comparison - I am thinking of throughput - can be achieved by counting number of end to end entangled pairs created. Currently the code only looks into fidelity.
4. 
