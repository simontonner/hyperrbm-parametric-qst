# Parametric Quantum State Tomography with HyperRBMs

Implements parametric quantum state tomography using hypernetwork-conditioned Restricted Boltzmann Machines.  
The approach reconstructs entire families of quantum ground states across phase diagrams using a single neural network.

This repository accompanies the paper:

**Simon Tonner, Viet T. Tran, Richard Kueng (2026)**  
*Parametric Quantum State Tomography with HyperRBMs*  
[arXiv:2601.20950](https://arxiv.org/abs/2601.20950)

All experiments run on CPU. No CUDA is required.

Experiments are organized by system type (e.g. `tfim_3x3`, `tfim_4x4`, `tfim_16`). Each folder contains the necessary
data and notebooks to reproduce the corresponding results, including training and evaluation.

Curated visualizations corresponding to the figures in the paper can be found in the `visualization` folder.

The core implementation is located in `hyper_rbm/`, with shared data utilities in `data_handling/`.

For experiments run over multiple random seeds, see the branch `ensemble-experiments`.  
These experiments are used to obtain averaged results and associated uncertainty estimates.

---

## License

© 2026, Simon Tonner

This project is licensed under the MIT License.  
See the `LICENSE` file for details.
