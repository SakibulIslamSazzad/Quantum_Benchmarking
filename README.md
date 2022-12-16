# Quantum Distance on NISQ Circuits

On this project, a set of NISQ circuits are selected based on the hardware agnostic benchmarking called SupermarQ [1]. Main goal of the project is to mimic a noise model for real quantum hardware. For modeling noisy simulation, three errors are chosen :*bit flip error*, *depolarising error*, *thermal error*. Parameters for the noise model prepared by following state of the art. One key aspects of the work is to calculate diamond norm for 3 qubits circuits and calculate the complete-bound-trace-norm for the noise model [2]. All NISQ circuits are run on the available IBM Quantum Open Backends and error bar plot is introduced for running the circuits in three times.



**[1] Teague Tomesh, Pranav Gokhale, Victory Omole, Gokul Subramanian Ravi, Kaitlin N Smith, Joshua Viszlai, Xin-Chuan Wu, Nikos Hardavellas, Margaret R Martonosi, and Frederic T Chong. Supermarq: A scalable quantum benchmark suite. In 2022 IEEE International Symposium on High-Performance Computer Architecture (HPCA), pages 587–603. IEEE, 2022.**

**[2] J. Watrous. “Simpler semidefinite programs for completely bounded norms”, arXiv:1207.5726 [quant-ph] (2012)**
