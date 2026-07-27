<h1 align="center">Aparna Krishnan</h1>

<p align="center">
  <a href="https://aksharma412.github.io"><img src="https://img.shields.io/badge/Website-181717?logo=github&logoColor=white" alt="Website"></a>
  <a href="https://scholar.google.com/citations?user=2_NRMS8AAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://www.linkedin.com/in/aparna-krishnan-57643a172/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

I work on molecules that come in mirror-image pairs — like your left and right hands — and on the software that predicts how they interact with light. Which mirror image you get decides whether a drug works or harms, so it is worth computing accurately.

Most people either derive the equations or write the code. I do both, and I think that's the only way to do either one well.

### How I work

**Derive → prove → implement → validate.** In that order, and the last step is not optional. If the analytic result doesn't match finite difference to 10⁻⁷, it isn't finished.

- Analytic derivative theory for chiroptical spectroscopy — atomic axial tensors, polar tensors, Hessians at CISD, MP2, and CCSD
- Real-time and unitary coupled-cluster dynamics
- Occasionally, a proof that an equivalence everyone assumes holds actually doesn't

### Things I've built

| | |
|---|---|
| [**PyCC**](https://github.com/CrawfordGroup/pycc) | Open-source Python coupled-cluster package. I contribute TD-EOM-CC methods, VCD pipelines, and orbital decomposition analysis. |
| [**Biorthogonal Jacobi-Davidson**](https://github.com/aksharma412/Biorthogonal-Jacobi-Davidson-algorithm) | Non-Hermitian eigensolver for EOM-CC. Tracks left and right eigenvectors at once, 25× faster than direct diagonalization. |
| [**CC equation generator**](https://github.com/aksharma412/dual_exponent_automatic_equation_and_code_generator) | Wick's theorem and BCH expansion done symbolically, emitting `np.einsum` code. Weeks of error-prone algebra, automated. |

### Before quantum chemistry

I trained as a mechanical engineer. Turns out tensors are tensors.

### Tools

`Python` · `C++` · `NumPy/SciPy` · `SymPy` · `HDF5` · `Psi4` · `Gaussian 16` · `CFOUR` · `SLURM` · `Qiskit`

<sub>Ph.D. candidate, <a href="https://crawford.chem.vt.edu">Crawford Group</a>, Virginia Tech · Blacksburg, VA</sub>
