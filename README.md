# Implementation of an integrated pipeline of FEM-VQE on IBM QPUs
**Variational quantum algorithms exploit the features of superposition and entanglement to optimize a cost function efficiently by manipulating the quantum states. They are suitable for noisy intermediate-scale quantum (NISQ) computers that recently became accessible to the worldwide research community. Here, we implement and demonstrate the numerical processes on the 5-qubit and 7-qubit quantum processors on the IBM Qiskit Runtime platform. We combine the commercial finite-element-method (FEM) software ABAQUS with the implementation of Variational Quantum Eigensolver (VQE) to establish an integrated pipeline. Three examples are used to investigate the performance: a hexagonal truss, a Timoshenko beam, and a plane-strain continuum. We conduct parametric studies on the convergence of fundamental natural frequency estimation using this hybrid quantum-classical approach. Our findings can be extended to problems with many more degrees of freedom when quantum computers with hundreds of qubits become available in the near future.**

files need collaborator's permission jiakun@seas.upenn.edu: FEM_consistent_system_for_HexTruss.ipynb; FEM_lumped_system_for_PlaneStrain.ipynb

# Citing
If you use [FEM-VQE_on_IBM_simulator_and_QPUs] in your research, please cite the accompanying paper:

> **Liu, Y., Liu, J., Raney, J.R. and Wang, P., 2024. Quantum computing for solid mechanics and structural engineering–A demonstration with Variational Quantum Eigensolver. Extreme Mechanics Letters, 67, p.102117.**

**BibTeX:**
```bibtex
@article{liu2024quantum,
  title={Quantum computing for solid mechanics and structural engineering--A demonstration with Variational Quantum Eigensolver},
  author={Liu, Yunya and Liu, Jiakun and Raney, Jordan R and Wang, Pai},
  journal={Extreme Mechanics Letters},
  volume={67},
  pages={102117},
  year={2024},
  publisher={Elsevier}
}
