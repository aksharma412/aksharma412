# Aparna Krishnan

PhD candidate in theoretical chemistry, [Crawford Group](https://crawford.chem.vt.edu), Virginia Tech. Graduating 2027.

I derive quantum chemistry methods and implement them. Most people do one or the other — the interesting problems need both. My work is in analytic derivative theory, real-time coupled-cluster dynamics, and the software that makes both run on real molecules.

[Website](https://aksharma412.github.io) · [Google Scholar](#) · [LinkedIn](https://www.linkedin.com/in/aparna-krishnan-57643a172/) · aparnak22@vt.edu

---

### Research

**Chiroptical spectroscopy from first principles.**
Density-matrix formulation of atomic axial tensors for vibrational circular dichroism at the CISD, MP2, and CCSD levels — the property that determines absolute configuration of chiral molecules. Full analytic pipelines: Hessians, atomic polar tensors, atomic axial tensors, rotational strengths. Every stage validated against finite difference to better than 10⁻⁷.

**Real-time coupled-cluster spectroscopy.**
Real-time CC gives accurate absorption spectra but no explanation of what causes each peak. I developed methods that decompose any spectral feature into the individual orbital transitions responsible, using both the autocorrelation function and the dipole moment as the starting observable. The ACF route cuts storage by 95%.
→ [arXiv:2605.17409](https://arxiv.org/abs/2605.17409), accepted in *J. Phys. Chem. A*

**Unitary coupled-cluster.**
In standard CC, real-time and equation-of-motion excitation energies are provably identical — an equivalence routinely used to validate new implementations. I showed it fails for the unitary ansatz: σ = T − T† does not commute with the excitation operators and its BCH expansion never terminates, so the two routes disagree at any finite truncation order. Derived the discrepancy in closed form and certified it against exact operator algebra to 10⁻¹².

---

### Software

**[PyCC](https://github.com/CrawfordGroup/pycc)** — open-source Python coupled-cluster package from the Crawford Group.
Contributor (16 merged commits). Implemented TD-EOM-CC methods, VCD pipelines, and the orbital decomposition analysis described above.

**[Biorthogonal Jacobi-Davidson](https://github.com/aksharma412/Biorthogonal-Jacobi-Davidson-algorithm)** — non-Hermitian eigensolver for EOM-CC.
Tracks left and right eigenvectors simultaneously and enforces biorthogonality throughout. 25× faster than direct diagonalization on EOM-CC test matrices.

**[Dual-exponent CC equation generator](https://github.com/aksharma412/dual_exponent_automatic_equation_and_code_generator)** — symbolic derivation to executable code.
Takes a coupled-cluster ansatz, applies Wick's theorem via SymPy's `secondquant`, performs the BCH expansion to 4th order, and emits validated `np.einsum` code. Built at IIT Bombay for Prof. Rahul Maitra's group.

---

### Tools

`Python` `C++` `NumPy/SciPy` `SymPy` `h5py/HDF5` `Psi4` `Gaussian 16` `CFOUR` `SLURM / HPC` `Qiskit` `Cirq` `QDK`

---

### Selected talks

Invited talk, SERMACS 2026 · MES 2026 (Greece) · MRPSS 2025 (Stockholm) · ESQC 2024 (Palermo) · Best Poster Award, SETCA 2026
