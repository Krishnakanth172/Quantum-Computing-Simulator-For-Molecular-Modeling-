This project demonstrates a Quantum Computing Simulator for Molecular Modeling using PennyLane, Qiskit, and Python. 
The primary goal is to model molecular systems and compute their quantum states and interactions using quantum simulation techniques. 
By leveraging quantum computing, the simulator enables high-precision calculations of molecular structures, providing insights into molecular behavior that are difficult to achieve using classical methods.

Key Features: 
Quantum Circuit Design: A quantum circuit is built to simulate molecular systems using quantum gates.
Hamiltonian Calculation: The molecular Hamiltonian is generated to represent the quantum energy levels and states of the molecule.
Quantum Simulation: PennyLane and Qiskit are used to simulate the quantum states of the molecule, providing insights into the electronic structure and molecular interactions.

Visualization: The probabilities of different quantum states are plotted, giving a detailed view of the quantum behavior of molecules.

Dataset: The project can either use molecular data inputted manually or fetched from the ChemBL or PubChem database. 
The molecules are converted into Hamiltonian representations for quantum simulations.

Example molecules include H₂, LiH, or larger organic molecules.
The molecular data includes atomic structures, bond lengths, and angles, which are processed to generate the Hamiltonian.

Model Architecture
The quantum simulation process involves:
Quantum Circuit: The quantum circuit simulates the molecular system using quantum gates such as Pauli-X, Pauli-Z, Hadamard, and CNOT gates.
Hamiltonian Generation: The molecular Hamiltonian is calculated using quantum chemistry algorithms like the Jordan-Wigner Transformation.
Quantum State Evolution: The quantum circuit evolves the quantum state of the system based on the input Hamiltonian.
Measurement: The final state of the quantum system is measured to compute the probability of each possible molecular configuration.

Requirements
Python 3.x
PennyLane
Qiskit
RDKit
NumPy
Matplotlib

You can install the required libraries using:
pip install pennylane qiskit numpy matplotlib rdkit
How to Run

Clone the repository:
git clone <repository_url>
cd <repository_directory>

Run the Python script:
python quantum_molecular_simulator.py

The script will:
Fetch or input molecular data
Generate the molecular Hamiltonian
Simulate the quantum circuit using PennyLane and Qiskit
Plot the quantum state probabilities

Output
Accuracy & Results:
The quantum simulation will output the probabilities of different quantum states.
You will also receive a visual representation of the molecular structure and quantum states.

Sample Prediction:
The simulator will display the most probable quantum state configuration of the molecule.
Results Visualization

During the simulation:
A plot of the quantum state probabilities is generated, showing the likelihood of each quantum state.
A molecular visualization representing the simulated molecular structure is provided.
