<h1 align="center">Aparna Krishnan</h1>

<p align="center">
  <a href="https://aksharma412.github.io"><img src="https://img.shields.io/badge/Website-181717?logo=github&logoColor=white" alt="Website"></a>
  <a href="https://scholar.google.com/citations?user=2_NRMS8AAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://www.linkedin.com/in/aparna-krishnan-57643a172/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

I work on high accuracy quantum chemistry methods and the code that runs them. Most of my research is on chiral molecules: how they respond to light, and how to predict that from first principles.

### How I work

**Derive → prove → implement → validate.** In that order, and the last step is not optional.

- Analytic derivative theory for chiroptical spectroscopy: atomic axial tensors, polar tensors, and Hessians at CISD, MP2, and CCSD
- Real-time and unitary coupled-cluster dynamics
- Checking whether methods that should agree actually do, and working out why when they don't

### Things I've built

| | |
|---|---|
| [**PyCC**](https://github.com/CrawfordGroup/pycc) | Open-source Python coupled-cluster package from our group. I contribute TD-EOM-CC methods, VCD pipelines, and orbital decomposition analysis. |
| [**Biorthogonal Jacobi-Davidson**](https://github.com/aksharma412/Biorthogonal-Jacobi-Davidson-algorithm) | A non-Hermitian eigensolver for EOM-CC that tracks left and right eigenvectors together and keeps them biorthogonal. |
| [**CC equation generator**](https://github.com/aksharma412/dual_exponent_automatic_equation_and_code_generator) | Applies Wick's theorem and the BCH expansion symbolically, then writes out the `np.einsum` code. Saves a lot of algebra by hand. |

### Before quantum chemistry

I trained as a mechanical engineer. Turns out tensors are tensors.

### Tools

`Python` · `C++` · `NumPy/SciPy` · `SymPy` · `HDF5` · `Psi4` · `Gaussian 16` · `CFOUR` · `SLURM` · `Qiskit`

<sub>Ph.D. candidate, <a href="https://crawford.chem.vt.edu">Crawford Group</a>, Virginia Tech · Blacksburg, VA</sub>
