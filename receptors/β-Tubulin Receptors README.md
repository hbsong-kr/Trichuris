# β-Tubulin Receptors

This folder contains the wild-type and mutant *Trichuris trichiura* β-tubulin structures used in molecular docking.

The β-tubulin protein was modeled from the amino-acid sequence corresponding to accession AAB99949. Homology modeling was performed using SWISS-MODEL with the AlphaFold structure O44388.1.A as the structural template.

Mutant receptor structures were generated using the PyMOL mutagenesis tool.

## Receptor models

The following receptor structures are included:

| Receptor | Description |
|---|---|
| `WT` | Wild-type β-tubulin |
| `G308W` | Korean-specific glycine-to-tryptophan substitution at residue 308 |
| `A352D` | Korean-specific alanine-to-aspartic-acid substitution at residue 352 |
| `F167Y` | Phenylalanine-to-tyrosine substitution at canonical resistance codon 167 |
| `E198A` | Glutamate-to-alanine substitution at canonical resistance codon 198 |
| `F200Y` | Phenylalanine-to-tyrosine substitution at canonical resistance codon 200 |

The G308W and A352D structures represent variants identified in Korean isolates.

The F167Y, E198A, and F200Y structures represent established benzimidazole-resistance-associated substitutions and were included as comparative mutant models.

## Current files

The folder contains modeled receptor PDB files and prepared docking receptor PDBQT files:

```text
A352D_receptor.pdbqt
E198A_receptor.pdbqt
F167Y_receptor.pdbqt
F200Y_receptor.pdbqt
G308W_receptor.pdbqt

MT_A352D.pdb
MT_E198A.pdb
MT_F167Y.pdb
MT_F200Y.pdb
MT_G308W.pdb

WT_receptor.pdb
WT_receptor.pdbqt
