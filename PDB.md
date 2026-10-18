# FRUCTOSE ALDOLASE B - PDB Documentation

**Note on residue numbering:** the mutated residue is position 150 in our sequences and in UniProt (p.Ala150Pro), where the initial methionine is counted as residue 1. The PDB structures used here number the residues without this initial methionine, so the same residue appears as position 149 (A149P). Both numbers refer to the same amino acid.

### Reference protein (wild type)

**PDB code**: 1QO5

**Tittle**: Fructose 1,6-bisphosphate Aldolase from Human Liver Tissue

**Classification**: LYASE

**Method**:  X-ray Diffraction

**Resolution**: 2.50 Å (medium)

**R-Value**:
 - R-Value Free: 0.276
 - R-Value Work: 0.224
   
**Source organism**: _Homo sapiens_

**Expression System**: Escherichia coli

**Primary Citation**: Dalby AR, Tolan DR, Littlechild JA (2001). The structure of human liver fructose-1,6-bisphosphate aldolase. Acta Crystallographica Section D 57: 1526.

Scientist created a 3D map of a liver enzyme (aldolase B). Comparing it with other similar enzymes in the body (the muscle is ozone (aldolase A)), they found that the liver version had an extra fold at the C-terminal tail that makes it highly flexible. However, genetic mutations can damage this specific fold, making this enzyme stop working and causing a severe disease called hereditary fructose intolerance.

**Ligand**: Sulfate ion (SO4)

**Biologial Assembly**: Homotetramer

### Mutated proteins

**PDB code**: 1XDM, 1XDL

**Tittle**: Structure of human aldolase B associated with hereditary fructose intolerance (A149P), at 277K

**Classification**: LYASE

**Method**:  X-ray Diffraction

**Resolution**: 3Å (medium)

**R-Value**:
 - R-Value Free: 0.310 (1XDM), 0.340 (1XDL)
 - R-Value Work: 0.264 (1XDM), 0.299 (1XDL)
   
**Source organism**: _Homo sapiens_

**Expression System**: Escherichia coli

**Primary Citation**: Malay, A.D., Allen, K.N., Tolan, D.R. (2005) J Mol Biol 347: 135-14

Researchers analyzed the most common genetic mutation behind hereditary fructose intolerance. They discover that a singles amino acid substitution in the liver enzyme triggers a chain reaction of molecular disorder. This structural chaos spreads through the protein, disrupting its quaternary structure and destroying its ability to process sugar, specially as temperatures rise.

**Ligand**: Sulfate ion (SO4)

**Biologial Assembly**: Homodimer (A2)

### Comparisons

The 1QO5 structure corresponds to the reference human aldosa B, which is without mutations, and has a resolution of 2.5Å. Meanwhile the 1XDL structure corresponds to human aldolase B with A149P substitution, which is associated with hereditary fructose intolerance, and has a resolution of 3.00Å.

The 1QO5 has a lower R-values than 1XDL, indicating that it has a better fit of the mesured electron density of the crystal and the electron density explained by the current model.

The PDB identifies 1QO5 as a homotetramer and the assembly shown for 1XDL is homodimer.

(poner que hay una alteraciones estructurales cerca del sitio mutado A149P????)

### Asymmetric unit vs biological assembly

**1QO5**
- **Chains in the PDB file (asymmetric unit)**: 18 (A-R)
- **Biological assembly**: Homotetramer (4 chains)
- The asymmetric unit contains several assemblies (18>4)

**1XDM**
- **Chains in the PDB file (asymmetric unit)**: 8 (A-D, W-Z)
- **Biological assembly**: Homodimer (2 chains)
- The asymmetric unit contains several assemblies

Aldolase B works as a homotetramer (4 chains). The 1QO5 file contains 18 chains, so it includes several assemblies (four and a half tetramers). The 1XDM file contains 8 chains, and the PDB defines its assembly as a dimer (2 chains), so it also contains several assemblies.

### Atomic-level data

**1QO5**
- **Residue 149 (Cα atom)**: Ala149
- **B-factor**: 26.53

**1XDM**
- **Residue 149 (Cα atom)**: Pro149
- **B-factor**: 92.42

In wild type, residue 149 has a moderate B-factor, so this part of the protein is quite stable. In the mutant, the B-factor of Pro149 is more that three times higher and well above 50Å², which means that this region is disordered.

The occupancy (from 0 to 1) indicates whether an atom is found in the same position in all the molecules of the crystal. The Cα atom of residue 149 has an occupancy of 1.00 in both structures, as do almost all the atoms, so there are no alternative positions for this residue.

### Link to the disease

We located residue 150 (Ala149 in the PDB numbering) in the 3D viewer. and observed that it is a part of a ß-strand, which agrees with the UniProt annotation (ß-strand 145-152). Its B-factor is  26.53 Å² in the wild type (1QO5) and 92.42 Å² in the mutant (1XDM).

**Interpretation**: As we discussed in the sequence analysis (Q8-Q9), proline cannot form some of the hydrogen bonds that hold a ß-strand together and makes the chain more rigid. This is because its side chain is a ring bound to its own backbone nitrogen
