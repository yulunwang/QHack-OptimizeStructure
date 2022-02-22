Team Name: BladeRunner

# Topic: Qubit efficient calculation of optimal molecular geometry

Project Description:
One of the most challenging and important tasks in chemistry is finding the stable geometry of molecules. Classically the problem is computationally intensive. Hence, there is huge interest in quantum computers to solve this problem. The problem can be formulated as a optimization problem, wherein we minimize the energy by placing the atoms in molecules properly. This can be achieved by modelling it using qubit Hamiltonian and solving it using VQE. VQE is the algorithm of choice as it has proven itself one of the best algorithms to run on current NISQ machines. However, is there a way we can make VQE even more efficient and resilient to noise?
The answer is yes! What if we could reduce the number of qubits required for the problem? This would translate to massive gains in saving computational cost and noise resiliency. In our project we aim to do so using the qubit efficient encoding. We will contrast our method against the standard VQE method and demonstrate the better performance in presence of noise by running examples on a real quantum computer. The molecules we consider are H20 and H4 (2+) dication. Furthermore we will also explore extension of the method to dynamical systems.

Reference:
Shee, Yu, et al. "A Qubit-Efficient Encoding Scheme for Quantum Simulations of Electronic Structure." arXiv preprint arXiv:2110.04112 (2021).

Source code:
https://github.com/yulunwang/QHack-OptimizeStructure/blob/main/README.md

Resource Estimate:
We will run a toy example and demonstrate the effects of noise on standard VQE vs qubit efficient VQE on a real quantum computer.
