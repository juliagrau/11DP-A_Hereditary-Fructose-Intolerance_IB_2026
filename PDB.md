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

**Chains/Length**: 18 chains. Sequence length: 363

**Source organism**: _Homo sapiens_

**Expression System**: Escherichia coli

**Primary Citation**: Dalby AR, Tolan DR, Littlechild JA (2001). The structure of human liver fructose-1,6-bisphosphate aldolase. Acta Crystallographica Section D 57: 1526.

Scientist created a 3D map of a liver enzyme (aldolase B). Comparing it with other similar enzymes in the body (the muscle is ozone (aldolase A)), they found that the liver version had an extra fold at the C-terminal tail that makes it highly flexible. However, genetic mutations can damage this specific fold, making this enzyme stop working and causing a severe disease called hereditary fructose intolerance.

**Ligand**: Sulfate ion (SO4)

**Biologial Assembly**: Homotetramer

### Mutated proteins

**PDB code**: 1XDM, 1XDL

**Tittle 1XDL**: Structure of human aldolase B associated with hereditary fructose intolerance (A149P), at 277K 
          
**Tittle 1XDM**: Structure of human aldolase B associated with hereditary fructose intolerance (A149P), at 291K

**Classification**: LYASE

**Method**:  X-ray Diffraction

**Resolution**: 3Å (medium)

**R-Value**:
 - R-Value Free: 0.310 (1XDM), 0.340 (1XDL)
 - R-Value Work: 0.264 (1XDM), 0.299 (1XDL)

**Chains/Length**: 8 chains. Sequence length: 365 

**Source organism**: _Homo sapiens_

**Expression System**: Escherichia coli

**Primary Citation**: Malay, A.D., Allen, K.N., Tolan, D.R. (2005) J Mol Biol 347: 135-14

Researchers analyzed the most common genetic mutation behind hereditary fructose intolerance. They discover that a singles amino acid substitution in the liver enzyme triggers a chain reaction of molecular disorder. This structural chaos spreads through the protein, disrupting its quaternary structure and destroying its ability to process sugar, specially as temperatures rise.

**Ligand**: Sulfate ion (SO4)

**Biologial Assembly**: Homodimer (A2)


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

### Rabbit homolog (Oryctolagus cuniculus)

**PDB code**: 1FDJ

**Tittle**: Fructose 1,6-bisphosphate Aldolase from Rabbit Liver
(We used the liver isoform because is the one related to HFI)

**Classification**: LYASE

**Method**:  X-ray Diffraction

**Resolution**: 2.10 Å (medium, close to high)

**R-Value**:
 - R-Value Free: 0.214
 - R-Value Work: 0.171

**Chains/Length**: 4 chains. Sequence length: 363

**Source organism**: _Oryctolagus cuniculus_

**Primary Citation**: Dalby AR, Tolan DR, Littlechild JA (2001). The structure of human liver fructose-1,6-bisphosphate aldolase. Acta Crystallographica Section D 57: 1526.

Scientist created a 3D map of a liver enzyme (aldolase B). Comparing it with other similar enzymes in the body (the muscle is ozone (aldolase A)), they found that the liver version had an extra fold at the C-terminal tail that makes it highly flexible. However, genetic mutations can damage this specific fold, making this enzyme stop working and causing a severe disease called hereditary fructose intolerance.

**Ligands**:  2FP (fructose-1,6-bisphosphate), 13P (dihydroxyacetone phosphate), G3P (glycerol-3-phosphate) and SO4

**Biologial Assembly**: Homotetramer

**B-factor of residue 149 (Cα)**: 8.80 Å²
(((The region around residue 149 is identical in the rabbit and human, and in the rabbit structure it is very stable (B-factor below 10 Å²). This shows that this region is conserved and structurally important in both species. 

The sequence around residue 150 is identical in rabbit and human, as we saw in the multiple sequence alignment. In the rabbit structure, this region has a very low B-factor (below 10 Å²), so it is very stable, as in the human wild-type structure. A region that is conserved between species and well ordered in the healthy proteins is probably important for the structure of the enzyme. This agrees with the fact that changing alanine to proline in this region disorders the protein.)))????

### Comparisons

- The 1QO5 structure corresponds to the reference human aldolase B, without mutations, and has a resolution of 2.50 Å. The 1XDM and 1XDL structures correspond to human aldolase B with the A149P substitution, which is associated with hereditary fructose intolerance, and have a resolution of 3.00 Å.

- 1QO5 has lower R-values than 1XDM and 1XDL, indicating a better fit between the electron density measured in the crystal and the electron density explained by the model.

- The PDB identifies 1QO5 as a homotetramer, while the assembly shown for 1XDM and 1XDL is a homodimer.

- There are important structural alterations near the mutated site. In the mutant, residues 150–158 and three neighbouring loops (110-129, 189–199 and 235–242) have no coordinates because they are disordered, and the B-factor of residue 149 increases from 26.53 Å² to 92.42 Å².
