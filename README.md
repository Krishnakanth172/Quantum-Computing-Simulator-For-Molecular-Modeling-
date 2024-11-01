This is a Quantum Computing Simulator for Molecular Modeling using PennyLane, Qiskit, and Python. This will model the molecular systems so that their
quantum states and interactions can be calculated through quantum simulation techniques. The application of quantum computing allows the simulator to obtain 
highly accurate calculations for molecular structures that are otherwise challenging when computed using classical methods.
Draw up the quantum circuit that would demonstrate a simulation for the given molecule system of quantum gate and its outcomes.
Write down the expression for the molecular Hamiltonian.

Quantum simulation: Run the implementation with both PennyLane and Qiskit programs in order to understand how quantized energy can be quantified throughout space
for the quantum states represented of the atoms in that particular molecule: it determines all the electronic distribution and hence further interaction as well that it goes on.

Dataset: A dataset of molecular data may be used which can be entered directly or retrieved from ChemBL or PubChem database. 
The molecules are written in Hamiltonian form for quantum simulations.
Examples: H2, LiH or larger organic molecules
Molecular data include atomic structure, bond length, and angle, all of which will be processed to give the Hamiltonian.

Model Architecture
The quantum simulation has
Quantum Circuit: quantum circuit simulation of the quantum system by the application of various quantum gates,
namely the Pauli-X gate and Pauli-Z gates; Hadamard and the CNOT gates. Application of Quantum Chemistry Algorithm that is used by Jordan Wigner
Transformation for generating Molecular Hamiltonian.
Quantum state evolution: the evolution of the quantum state of the given system as per the provided Hamiltonian.
Measurement: The final state of the quantum system is measured in order to calculate the probability of each possible molecular configuration.

Requirements
Python 3.x
PennyLane
Qiskit
RDKit
NumPy
Matplotlib

You can install the above libraries by running:
pip install pennylane qiskit numpy matplotlib rdkit
How to Run

Clone the repository:
git clone <repository_url>
cd <repository_directory>
Run the Python script
python quantum_molecular_simulator.py
The above script will do the following:
Fetch or input molecular data
Generate the molecular Hamiltonian
Simulate the quantum circuit using PennyLane and Qiskit
Plot the quantum state probabilities

Output
Accuracy & Results:
The quantum simulation will show the probabilities of different types of quantum states.
There will be a graphical description of the molecular structure with respect to the quantum states.

Demonstration of Prediction:
Output from the simulator
Configuration of the quantum state will be shown with maximum likelihood.

Visualization of Results 
At the time of run
A plot for a probability of quantum states shows the probability of every individual quantum state.
Molecular view of the simulated molecular structure.
