#  Hereditary Fructose Intolerance: analysis on the causes
Ferré Parés Josep, Grau Martín Júlia, Iturriaga Pizarro Jana, Zhouchen Diana

Bachelor's Degree in Bioinformatics, UPC-UPF-UAB-UB, Barcelona, Spain

## Abstract
[Provide a structured abstract covering Background, Results, and Conclusions (Max 350
words).]
### Keywords
Hereditary Fructose Intolerance (HFI), Aldolase B (ALDOB), Protein Structure, fructose 1-phosphate, Coding Sequence (CDS) 

## Background

Fructose is a monosaccharide found in foods consumed daily, such as fruits, vegetables, and sweeteners, and it is also produced in small amounts by the brain. Aldolase B is one of the three aldolase isoenzymes and is found in the liver, kidney, and intestinal tissue, which are important organs in fructose metabolism (Ravi and Sharma 2026). It catalyses the reversible conversion of fructose 1,6-bisphosphate into glyceraldehyde 3-phosphate and dihydroxyacetone phosphate in glycolysis and gluconeogenesis, and it also cleaves fructose 1-phosphate in fructolysis.

Hereditary fructose intolerance (HFI) is an autosomal recessive disorder caused by mutations in the gene that codes for the isoenzyme aldolase B (ALDOB). It is an inherited condition with an estimated prevalence of 1 in 20 000 people, and it affects both sexes equally. When a person with HFI ingests fructose, fructokinase quickly converts it into fructose 1-phosphate. Without aldolase B to process this molecule, it accumulates, causing a depletion of both ATP and phosphate, which is responsible for long-term organ injury. The accumulation also increases the degradation of adenine nucleotides by adenosine deaminase, which increments the production of uric acid. In addition, the rise in uric acid is similar in glucose-6-phosphatase deficiency and fructose 1,6-bisphosphatase deficiency. 
The acumulation of fructose also activates pyruvate kinase, the enzyme that catalyses the final step of glycolysis, so precursors of the Krebs cycle build up and contribute to acidosis. As a result, it leads to abdominal pain, vomit, nausea, hypoglycemia (a drop of blood sugar level) and even kidney and liver failure, which can be life-threatening. 

HFI is diagnosed after several clinical tests that look at how the body reacts once the patient has eaten fructose, sucrose, or foods containing sorbitol. A more invasive option is a liver biopsy, which is used to check whether aldolase B is present. The urine can also be inspected for reducing substances, and the values are compared with the expected results. The main treatment for HFI is a diet free of fructose and sucrose, including products that contain sorbitol. This includes medicines or vaccines that have sorbitol as a main component.
In a discrete choice experiment, adult patients had to choose, between their current fructose-restricted diet and a pharmacological therapy. A random parameter model first showed a tendency to prefer the diet. However, most participants chose an option which was closer to the pharmacological therapy. The authors therefore concluded that, despite the first model, patients were in fact more inclined towards pharmacological therapy.

(informacion de notes pero no tengo ni idea de donde se ha sacado)

For aldolase B to work, it must fold correctly into a homotetramer. Its four identical subunits need enough flexibility to open and close their contact interfaces and to orient the catalytic amino acids into exact positions, a process called induced fit. A variant that changes the properties of the protein chain may therefore stop the enzyme from working properly. Many ALDOB variants cause disease, but here we focus on p.Ala150Pro (c.448G>C), which has an allele frequency of 0.0031256 .






***
## Results
[Present your findings. Use subheadings as needed.]
### Gene and Protein Identification Across Genomic Databases 
To identify which was the causative gene and protein from the WT coding sequence (CDS) and the aminoacids FASTA files, we executed sequence similarity searches using BLAST, the Basic Local Alignment Search Tool. The first search iteration arose taxonomic discrepancy because the protein query we focused on was searched against a non-human primate homologue, a Sumatran orangutan (_pongo abelii_, accession NP_001127166.1). Simultaneously, a cross-search using OMIM, the Online Mendelian Inheritance in Man, was carried out. After typing the query search "Herederitary Fructose Intolerance" and learning about this disease from the first entries, we extracted the conclusion that we had to focus on the isoenzyme Aldolase B. 

After repeating the searches, this time restricting the outputs to _Homo sapiens_, both the WT nucleotide CDS and protein sequences matched the 1-fructose,6-biphosphate aldolase B (ALDOB, accession NM_000035.4,chromosome 9q31.1 , nine exons; UniProtKB 364 amino acids, 39 473 Da, sequence updated in  2007). Querying the FASTA files compared to the human reference, sequence identity decreased from 100% (WT) to 99.91% (mutant) at the CDS level, and from 99.18% (WT) to 98.90% (mutant) at the protein level.

### Identification of the Pathogenic Variant
Pairwise alignment between the human WT and the mutant CDS sequences identified a single variation between the two, a nucleotide substitution at position 448 (c.448C>G). There was no insertion of deletion of nucleotides, so the open reading frame remains intact with no frameshift mutations. At protein level, this single nucleotide changes makes for a codificaiton of another nucleotide, causing a missense mutation at codon 150, replacing Alanine with Proline ( p.Ala150Pro ). GCA (WT codon) syntesizes Alanine, while CCA (mutant codon) synthesizes Proline. UniProtKB classifies this substitution as a physicochemical transition from a small, hydrophobic residue (Alanine, A) to a medium-sized, hydrophobic residue (Proline, P) with a BLOSUM score of −1, indicating an evolutionarily disfavoured replacement.

Although both Alanine and Proline are neutral, non-polar aminoacids that contain the same functional groups, standard carboxyl (-COOH) and amino (-NH2), the position inside the molecule affects how they interact with other molecules and backbone connectivity. The alanine amino group retains a free amide hydrogen after being incorporated to the polypeptide chain. This is due to it being in an extreme of the molecule, which allows it to act as a hydrogen-bond donor. Moreover, alanine is the aminoacid with the highest propensity to form stable α-helices in aqueous environments. On the other hand, Proline's amino group is caged inside a rigid cyclic ring that is bonded to its own backbone nitrogen atom. This means that proline has no free amide hydrogen that can act as a hydrogen-bond donor, causing a complete change in the structure of the protein. Proline bends the main chain, and acts as a classic secondary-structure breaker ("helix and β-strand breaker") due to its structural characteristics.

### Evolutionary Conservation Comparison Analysis Between Species
We compared human aldolase B with two mammals: rabbit (Oryctolagus cuniculus), the species assigned to our group, and Sumatran orangutan (Pongo abelii), a closely related primate. Following the practical guidelines, we only used curated RefSeq records: NM_001171114.1 and NP_001164585.1 for rabbit, and NM_001133694.1 and NP_001127166.1 for orangutan.

**Table 2. Sequence identity of the orthologs with human aldolase B.**

| Species | CDS identity | Protein identity | Amino-acid differences | Gaps |
|:---|:---:|:---:|:---:|:---:|
| *Pongo abelii* | 98.63 % | 99.18 % | 3 | None |
| *Oryctolagus cuniculus* | 93.42 % | 96.98 % | 11 | None |

At the CDS level, we found three long blocks identical in the three species: positions 313–389, 397–449 and 688–740. The block 397–449 ends at nucleotide 449, so it includes the first base of codon 150, the site of the variant. We also found substitutions, for example at position 465, where the human C is replaced by T in both orangutan and rabbit.

At the protein level, 351 of 364 positions (96.4 %) are identical in the three species. One of the longest identical blocks covers positions 68–167, and Ala150 lies inside it. Orangutan differs from human at 3 positions and rabbit at 11 positions; for example, Met333 is replaced by Val in both species. No gaps were found.

The three species are more similar at the protein level than at the CDS level. Many nucleotide differences do not change the amino acid (synonymous substitutions), because the genetic code is degenerate: several codons encode the same amino acid. This indicates that the protein sequence has been conserved more strongly than the DNA sequence, and that the region containing Ala150 tolerates few changes.

### Protein Structure Comparision and Atomic-Level Perturbations
We searched the PDB with the UniProt accession of human aldolase B (P05062). Four human structures are available: 1QO5 and 8D44 have no mutations, while 1XDL and 1XDM contain the A149P substitution, the same variant found in our mutant sequence. We selected 1QO5 as the WT reference because it has the highest resolution (2.50 Å), and 1XDM as the main mutant structure. For the rabbit we used 1FDJ (liver aldolase B), because most rabbit aldolase structures in the PDB belong to the muscle isoform (aldolase A), which is a different gene.

**Table 3. PDB structures analysed.**

| | 1QO5 (human WT) | 1XDM (human A149P) | 1FDJ (rabbit WT) |
|:---|:---:|:---:|:---:|
| Method / resolution | X-ray, 2.50 Å | X-ray, 3.00 Å | X-ray, 2.10 Å |
| R-free / R-work | 0.276 / 0.224 | 0.310 / 0.264 | 0.214 / 0.171 |
| Chains in the PDB file | 18 | 8 | 4 |
| Biological assembly | Homotetramer | Homodimer | Homotetramer |
| Ligands | SO4 | SO4 | 2FP, 13P, G3P, SO4 |
| Secondary structure at residue 150 | β-strand | β-strand | β-strand |
| B-factor of residue 150 (Cα) | 26.53 Å² | 92.42 Å² | 8.80 Å² |

All structures have medium resolution (2–3.5 Å). The mutant structure has higher R-values than the WT, which indicates a poorer fit between the model and the experimental data, as expected for a partially disordered protein. The PDB files of 1QO5 (18 chains) and 1XDM (8 chains) contain several copies of the biological assembly. The PDB describes the WT enzyme as a homotetramer and the A149P mutant as a homodimer, which suggests that the mutation affects how the subunits assemble.

In the 3D viewer, residue 150 is located in a β-strand, in agreement with the UniProt annotation (β-strand 145–152), and close to a sulfate ion bound near Arg148. In the WT, its B-factor is moderate (26.53 Å²), so this region is quite stable. In the mutant, the B-factor of Pro150 is more than three times higher (92.42 Å²) and several residues after the mutation have no coordinates, which means that this region becomes highly mobile and disordered. The Cα atom of residue 150 has an occupancy of 1.00 in both structures, so it has no alternative positions.

In the rabbit structure, the region around residue 150 is identical in sequence to the human one and very stable (B-factor below 10 Å²). Together with the sequence conservation, this indicates that this region is important for the structure of aldolase B in both species.

### Protein comparison between WT orthologs
After comparing the physichochemical structure between the Human WT and the ortholog given at the start of the project, _Oryctolagus cuniculus_, using BLAST both proteins were almost identical with a sequence identity (aligned positions) of 96.7%, same physicochemical class (including identical residues) of 98.3% and a global RMSD of 6.17 Å 

> Although the percentages excludes alignment gaps there's only one protein at the start that the Human WT has that the ortholog doesn't

When looking at the 3D model of the WT proteins, the major changes apear at the ends of the protein
<img width="950" height="700" alt="image" src="https://github.com/user-attachments/assets/df9354aa-af37-4236-bc23-1b1b6737e2ed" />
###### figure 1. Superposition of Homo sapiens and Oryctolagus cuniculus structures. They are coloured by RMSD: white means they are perfectly superposed and red means they are separated in space and badly aligned. Yellow segments identify regions that were ignored during superposition.


## Discussion
[Discuss implications, compare with existing research, and highlight limitations.]
***
## Conclusions
[State the main conclusions and their significance.]
***
## Methods
[Provide technical details for reproducibility: Data Sources, Implementation, Statistical
Analysis.]

Three-dimensional structures of aldolase B are available in the Protein Data Bank (PDB). The reference structure of the human enzyme (1QO5) was solved by X-ray diffraction at a resolution of 2.50 Å from a protein produced in Escherichia coli, and it shows a homotetramer. Two structures of the A149P mutant (1XDL and 1XDM) were solved by X-ray diffraction at 3.00 Å, at 277 K and at 291 K respectively, and the mutant is described as a homodimer instead of a tetramer (Malay et al. 2005). The residue changed in this variant is numbered 150 in UniProt but 149 in these structures, because the PDB numbering does not count the initial methionine. Finally, the structure of the rabbit (Oryctolagus cuniculus) liver aldolase (1FDJ), solved at 2.10 Å in complex with substrate and product ligands, allows the human protein to be compared with that of another mammal (Author Year).
***
## Abbreviations
[List abbreviations used, e.g., AI: Artificial Intelligence.]
Hereditary fructose intolerance (HFI)
Coding Sequence (CDS)

***
## Declarations
Availability of data and materials: All data used in this study are publicly available.
- The wild-type and mutant CDS and protein sequences (FASTA files) were provided by the course.
- The ALDOB Conservation file was also provided by the course.
- Reference sequences were obtained from NCBI (BLAST) (NM_000035.4, NP_000026.2, NM_001171114.1, NP_001164585.1, NM_001133694.1 and NP_001127166.1) and UniProtKB (P05062), and protein structures from the RCSB Protein Data Bank (1QO5, 1XDL, 1XDM, 8D44 and 1FDJ.

Authors' contributions: [Specify roles]
***
## References
1. Author A, Author B. Title. BMC Bioinformatics. Year;Vol:Pages.

Cross NC, Tolan DR, Cox TM. Catalytic deficiency of human aldolase B in hereditary fructose intolerance caused by a common missense mutation. Cell 1988;53:881-5.

Esposito G, Imperato MR, Ieno L et al. Hereditary fructose intolerance: functional study of two novel ALDOB natural variants and characterization of a partial gene deletion. Hum Mutat 2010;31:1294-303. 

Esposito G, Vitagliano L, Santamaria R et al. Structural and functional analysis of aldolase B mutants related to hereditary fructose intolerance. FEBS Lett 2002;531:152-6.

Janssen LEF, Hiligsmann M, Timmer C et al. Treatment preferences of adult patients with hereditary fructose intolerance: a discrete choice experiment. Mol Genet Metab 2025;145:109169.

Ravi U, Sharma L. Fructose-1-phosphate aldolase deficiency. In: StatPearls [Internet]. Treasure Island (FL): StatPearls Publishing, 2026.
   
Rumping L, Waterham HR, Kok I et al. Hereditaire fructose-intolerantie [Hereditary fructose intolerance]. Ned Tijdschr Geneeskd 2014;158:A6889. (In Dutch).

Sánchez-Gutiérrez JC, Benlloch T, Leal MA et al. Molecular analysis of the aldolase B gene in patients with hereditary fructose intolerance from Spain. J Med Genet 2002;39:e56.

Santamaria R, Vitagliano L, Tamasi S et al. Novel six-nucleotide deletion in the hepatic fructose-1,6-bisphosphate aldolase gene in a patient with hereditary fructose intolerance and enzyme structure-function implications. Eur J Hum Genet 1999;7:409-14.
