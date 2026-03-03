# quasicrystal-vdos-project
MSc project: Quasicrystal vibrational analysis using MACE

# Quasicrystal VDOS Project

**MSc ES98C Project** | University of Warwick  
**Supervisor:** Dr Albert Bartók-Pártay

## Overview

Investigating whether golden-ratio (τ = 1.618) spectral features can be captured in quasicrystal vibrational spectra using Machine Learning Interatomic Potentials (MACE).

## Current Progress

| Objective | Description | Status |
|-----------|-------------|--------|
| O1 | MACE stability on Al-Ni-Co | ✅ Complete |
| O2 | Harmonic vs anharmonic VDOS | 🔄 In progress |
| O3 | Finite-size τ-analysis | ⬜ Planned |
| O4 | Periodic benchmark | ⬜ Planned |
| O5 | Uncertainty quantification | ⬜ Planned |

## Key Results

### O1: MACE Stability Test
- **Structure:** W-AlCoNi (197 atoms) from CMU Database
- **Energy:** -4.27 eV/atom 
- **Status:** Structure stable under MACE-MP-0

### O2: VDOS (Preliminary)
- Computed at 300K using VACF method
- Shows acoustic peak (0-2 THz) and optical modes (8-10 THz)
- Possible pseudo-gap around 5-6 THz

## Files

| File | Description |
|------|-------------|
| `MACE_Validation.ipynb` | Main analysis notebook |
| `W-AlCoNi_265.txt` | CMU structure file (265 atoms) |

## References

1. Matsuura et al. (2024) "Singular continuous and nonreciprocal phonons in quasicrystal AlPdMn" *Phys. Rev. Lett.* 133, 136101
2. Batatia et al. (2024) "A foundation model for atomistic materials chemistry"

## Installation

```bash
pip install mace-torch ase phonopy matplotlib scipy
```
