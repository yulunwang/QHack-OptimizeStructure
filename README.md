### Team Name: 
#### BladeRunner

### Topic: Qubit efficient calculation of optimal molecular geometry

### Project Description:

One of the most challenging and important tasks in chemistry is finding the stable geometry of molecules. Classically the problem is computationally intensive. Hence, there is huge interest in quantum computers to solve this problem. The problem can be formulated as a optimization problem, wherein we minimize the energy by placing the atoms in molecules properly. This can be achieved by modelling it using qubit Hamiltonian and solving it using VQE. VQE is the algorithm of choice as it has proven itself one of the best algorithms to run on current NISQ machines. However, is there a way we can make VQE even more efficient and resilient to noise?
The answer is yes! What if we could reduce the number of qubits required for the problem? This would translate to massive gains in saving computational cost and noise resiliency. In our project we aim to do so using the qubit efficient encoding. We will contrast our method against the standard VQE method and demonstrate the better performance in presence of noise by running examples on a real quantum computer. The molecules we consider are H20, H4 (2+) dication. Furthermore we will also explore extension of the method to dynamical systems.



Applications in Biotechnology: By calculating Molecular Geometries to such a high degree of accuracy we are able to create better drugs. The molecular geometry uses spherical representations, again more accurate. Application examples include the following: the most efficient/precise computation of the blending surface over an input molecule, the computation of the van der Waals volume (and area); an efficient docking simulation; the recognition of internal voids and their volume computation; the recognition of molecular tunnels, the comparison (or superposition) of the boundary structures of two molecules, shape reasoning such as measuring the sphericity of molecules, the efficient computation of the optimal side-chain placement for proteins, etc.

Improvements for future: We would like to add more to this after the Hackathon by implementing more Geometries of other molecules.

<img src="https://user-images.githubusercontent.com/33207831/155512375-9d3f18c8-b9ba-45ac-aba6-2073a1b62caa.png" width="450">

### Presentation

[Optimize H3+ structure using QEE - Presentation](https://docs.google.com/presentation/d/1lKY0P5rQSDCLQkPKvkeHMzE5Hakn4-2rP0qmInWVTkc/edit?usp=sharing)

### Reference:

Shee, Yu, et al. "A Qubit-Efficient Encoding Scheme for Quantum Simulations of Electronic Structure." arXiv preprint arXiv:2110.04112 (2021).
https://pennylane.ai/qml/demos/tutorial_mol_geo_opt.html 

Alan Aspuru Guzik et al "Quantum algorithm for molecular properties and geometry optimization" (2009)
https://www.kassal.group/assets/papers/kassal005.pdf

Alberto Peruzzo, Jarrod McClean et al., ???A variational eigenvalue solver on a photonic quantum processor???. Nature Communications 5, 4213 (2014).
Jacob T. Seeley, Martin J. Richard, Peter J. Love. ???The Bravyi-Kitaev transformation for quantum computation of electronic structure???. Journal of Chemical Physics 137, 224109 (2012).
https://pennylane.ai/qml/demos/tutorial_vqe.html
