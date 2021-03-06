# NonlinearWave
A collection of Jupyter notebooks that tests different nonlinear models based on FEniCS package.

- 2D-Wave-DamageDG-Fsource: 2D DG code with IVM model.

- DG-1DWaveProp-Internal-NewFunc2-BCs: Implemented with DG method. Internal variable model with sofening, hysteresis and healing (https://royalsocietypublishing.org/doi/pdf/10.1098/rspa.2017.0024). The new function for evolution of the internal variable is proposed. Testing implementations for non-reflection BCs.

- DG-1DWaveProp-Internal-NewFunc2.ipynb: Implemented with DG method. Internal variable model with sofening, hysteresis and healing (https://royalsocietypublishing.org/doi/pdf/10.1098/rspa.2017.0024). The new function for evolution of the internal variable is proposed. And problems with the BCs for DG=0 have been solved. (Feb. 22nd, 2022)

- DG-1DWaveProp-Internal-Clean.ipynb: Implemented with DG method. Internal variable model with sofening, hysteresis and healing (https://royalsocietypublishing.org/doi/pdf/10.1098/rspa.2017.0024). The results are quanlitatively matching those in the paper. But the BCs for DG=0 are still with problems. This will be figured out in the next version. (Jan. 20th, 2022)

- WaveProp1D-Internal-Explicit.ipynb: Internal variable model with sofening, hysteresis and healing (https://royalsocietypublishing.org/doi/pdf/10.1098/rspa.2017.0024)

- Sensitivity-Wave-Veri-Cleaned.ipynb: Code for testing the sensitivity analysis with dolfin-adjoint package (http://www.dolfin-adjoint.org/en/latest/documentation/verification.html)

- WaveProp1D-MPII-absTest.ipynb: Full MPII model that considers multiple yielding surface, testing the correctness of abs() function

- WaveProp1D-Veri3.ipynb: Cleaned up for redundant code. Try to verify the solution with the Method of Manufactured Solutions, convergence study

- WaveProp1D-Veri2.ipynb: Try to verify the solution with the Method of Manufactured Solutions, convergence study

- WaveProp1D-Veri.ipynb: Try to verify the solution with the Method of Manufactured Solutions

- WaveProp1D-MPII-Tidy.ipynb: Full MPII model that considers multiple yielding surface

- WaveProp1D.ipynb: Only the bone curve of MPII model, more or less a non-linear elasticity model

- WaveProp2D-Real-Plas.ipynb: vonMises plasticity with strain hardening
