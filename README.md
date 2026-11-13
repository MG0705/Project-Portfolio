# Project-Portfolio

**PROJECT 1: MLP**

This PyTorch project essentially involved constructing a MLP (to learn non-linear decision boundaries in sorting coloured points) consisting of multiple non-linear ReLU stages followed by an output using the Softmax logic function with the model being trained on varied generated datasets.

**LINK:** https://github.com/MG0705/Project-1---MLP

 ----
 **PROJECT 2: Computer Vision**

This computer vision project (using PyTorch) took an image as an input and carried out edge and corner detection followed by keypoint detection with SIFT being used to identify the dominant orientation of each keypoint.

**LINK:** https://github.com/MG0705/Project-2--ComputerVision

----
 **PROJECT 3: Gaussian Boson Sampling**

This quantum photonics project compiled Gaussian boson sampling circuits onto a programmable Clements MZI mesh and modelled how fabrication errors in its couplers distort the sampler's output photon statistics. Spatially correlated errors proved 9–15% more detrimental than independent errors of the same size, with the worst case occurring when errors are correlated over roughly the size of a single MZI.

**LINK:** https://github.com/MG0705/Project-3--Gaussian-Boson-Sampling

----
 **PROJECT 4: Precision Limits of Nonvolatile Photonic Matrix Multipliers**

This photonics project models a photonic matrix multiplier programmed with phase-change elements. It separates the precision lost to programming (limited levels, noisy writes, write-verify) from the precision lost to fabrication error in the couplers, independent or spatially correlated. In an 8x8 multiplier, 0.02 rad of coupler error caps precision at about 4.4 effective bits, so write-verify stops paying off at about 4 pulses per element.

**LINK:** https://github.com/MG0705/Project-4--Nonvolatile-Photonic-Precision

----
 **PROJECT 5: Self-Configuring Photonic Meshes under Correlated Fabrication Error**
 
This project is a simulation of Miller's self-configuring line, set element by element from local detector feedback, with MZI and double-MZI elements. A layout choice that makes no difference for independent errors decides the outcome once errors are correlated, where, on the same correlated errors, the staircase layout loses 20-220x more light than a bus layout and double MZIs remove the loss up to 0.15 rad.

**LINK:** https://github.com/MG0705/Project-5--Self-Configuring-Meshes

----
**PROJECT 6: Correcting Correlated Fabrication Error from Sparse Monitors**

This project implements a differentiable JAX model of a Clements mesh that re-optimises its phases for the fabricated couplers, either known exactly or estimated from noisy monitors on a quarter of the couplers. Once errors are correlated over 4 or more pitches, the monitors remove 96-99.6% of the error, against 24% for independent errors.

**LINK:** https://github.com/MG0705/Project-6--Correlated-Error-Correction
