# Δ-Helix Structural Project (Δ12 / Δ14 / Δ30)

This repository presents a novel class of artificial helical peptides, collectively termed "Δ-helix". These sequences are short, resilient, and form triangular helical structures not observed in natural proteins. The contents include original sequence definitions, AlphaFold2-predicted PDB files, and MD simulation data.

## Overview

Δ-helix is a helix-like motif with a triangular cross-section and a periodicity of approximately 4.5 residues per turn. Unlike α-helices, Δ-helices are not stabilized by classical hydrogen bond networks. Instead, they rely on polar interactions at the termini and internal structural compression. These peptides were designed using a resilin-derived backbone and optimized via iterative structure prediction and MD validation.

## Repository Structure

```
/pdb/
    delta12.pdb
    delta14.pdb
    delta30.pdb

/md/100ns/
    (Δ14 simulation at 303.15K, 1 atm - 100 ns)

/md/350K3atm/
    (Δ14 simulation at 350.15K, 3 atm - 50 ns)

/docs/
    Δhelix github草案.pdf (Japanese)
    Δhelix github草案（EN).pdf (English)
```

## Key Sequences

- Δ12: `TTRPSDSYGTPTTGN`
- Δ14: `TTRPSDSYGTPTTGNA`
- Δ30: `TTRPSDSYGTPTTGNAAS TTRPSDSYGTPTTGNAA`

These sequences all show stable Δ-helix formation in AlphaFold2 predictions. Δ14 in particular was validated via 100ns MD simulation and extreme condition simulation (350K, 3 atm), showing high structural resilience.

## MD Conditions

All MD simulations were performed using GROMACS 2023 with TIP3P water and CHARMM36m force field. 
Due to file size constraints, full molecular dynamics (MD) simulation data are not hosted directly in this repository.
You can access all MD simulation output files via the following Google Drive link:https://drive.google.com/drive/folders/1EuZO2_6k7cipLn5AJPWUeAOJC3vAir9_)

This includes .xtc, .tpr, .gro, and related files for Δ14 100ns and 50ns (extreme conditions).
If you encounter any issues or need further data, please contact the author.

## License

All materials are released under the following license:

**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**
You are free to use, share, and modify under non-commercial terms.
See `LICENSE.txt` for details.

##Note
This project presents preliminary research findings. The Δ-helix structures and simulation results have not yet undergone formal peer review and should be interpreted accordingly.


## Author

Rintaro Nagai
Undergraduate, Hiroshima University
Contact via GitHub or Discord
