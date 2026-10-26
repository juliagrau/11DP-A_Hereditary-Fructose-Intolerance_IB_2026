#  Hereditary Fructose Intolerance: analysis on the causes
Ferré Parés Josep, Grau Martín Júlia, Iturriaga Pizarro Jana, Zhouchen Diana

Bachelor's Degree in Bioinformatics, UPC-UPF-UAB-UB, Barcelona, Spain

## Abstract
Hereditary fructose intolerance (HFI) is an autosomal recessive metabolic disorder with an estimated prevalence of 1 in 20 000 individuals, caused by mutations in the ALDOB gene encoding the isoenzyme fructose-1,6-bisphosphate aldolase B. This isoenzyme is found in the liver, kidney, and small intestine, and aldolase B must fold into a flexible homotetramer to catalyse the reversible cleavage of fructose 1,6-bisphosphate in glycolysis and gluconeogenesis and the cleavage of fructose 1-phosphate in fructolysis. 
We investigated the molecular, evolutionary, and structural basis of HFI using bioinformatic tools such as the Basic Local Alignment Search Tool (BLAST), Online Mendelian Inheritance in Man (OMIM), UniProtKB, and the Protein Data Bank (PDB). Sequence searches mapped the human wild-type (WT) coding sequence (CDS) and protein to ALDOB on chromosome 9q31.1 (NM_000035.4, nine exons; UniProt P05062, 364 amino acids, 39 473 Da). Pairwise alignment of the mutant sequence identified a single nucleotide substitution, c.448G>C (allele frequency 0.0031256), preserving the reading frame without insertions or deletions while causing the missense mutation p.Ala150Pro (BLOSUM score −1).
Cross-species alignments with Pongo abelii (98.63% CDS and 99.18% protein identity) and Oryctolagus cuniculus (93.42% CDS and 96.98% protein identity); demonstrated that genetic code degeneracy presents silent nucleotide variations while strictly conserving the core block (positions 68–167) containing Ala150, that if affected, presents life-threatening consequences.
Comparing WT human 3D structures against the mutant human 3D structure we could see that replacing a hydrogen-bond-donating Alanine with a rigid, cyclic Proline lacking a free amide hydrogen disrupts $\beta$-strand. This structural collapse prevents fructose 1-phosphate cleavage, triggering a depletion of intracellular adenosine triphosphate (ATP) and phosphate, uric acid elevation, acidosis, hypoglycaemia, and organ failure—explaining the need for strict dietary fructose exclusion.

### Keywords
Hereditary Fructose Intolerance (HFI), Aldolase B (ALDOB), Protein Structure, fructose 1-phosphate, Coding Sequence (CDS) 

## Background

Fructose is a monosaccharide found in foods consumed daily, such as fruits, vegetables, and sweeteners, and it is also produced in small amounts by the brain. Aldolase B is one of the three aldolase isoenzymes and is found in the liver, kidney, and intestinal tissue, which are important organs in fructose metabolism (Ravi and Sharma 2026). It catalyses the reversible conversion of fructose 1,6-bisphosphate into glyceraldehyde 3-phosphate and dihydroxyacetone phosphate in glycolysis and gluconeogenesis, and it also cleaves fructose 1-phosphate in fructolysis.

Hereditary fructose intolerance (HFI) is an autosomal recessive disorder caused by mutations in the gene that codes for the isoenzyme aldolase B (ALDOB). For aldolase B to work, it must fold correctly into a homotetramer. Its four identical subunits need enough flexibility to open and close their contact interfaces and to orient the catalytic amino acids into exact positions, a process called induced fit. A variant that changes the properties of the protein chain may therefore stop the enzyme from working properly. It is an inherited condition with an estimated prevalence of 1 in 20 000 people, and it affects both sexes equally. When a person with HFI ingests fructose, fructokinase quickly converts it into fructose 1-phosphate. Without aldolase B to process this molecule, it accumulates, causing a depletion of both ATP and phosphate, which is responsible for long-term organ injury. The accumulation also increases the degradation of adenine nucleotides by adenosine deaminase, which increments the production of uric acid. In addition, the rise in uric acid is similar in glucose-6-phosphatase deficiency and fructose 1,6-bisphosphatase deficiency. 
The acumulation of fructose also activates pyruvate kinase, the enzyme that catalyses the final step of glycolysis, so precursors of the Krebs cycle build up and contribute to acidosis. As a result, it leads to abdominal pain, vomit, nausea, hypoglycemia (a drop of blood sugar level) and even kidney and liver failure, which can be life-threatening. 

HFI is diagnosed after several clinical tests that look at how the body reacts once the patient has eaten fructose, sucrose, or foods containing sorbitol. A more invasive option is a liver biopsy, which is used to check whether aldolase B is present. The urine can also be inspected for reducing substances, and the values are compared with the expected results. The main treatment for HFI is a diet free of fructose and sucrose, including products that contain sorbitol. This includes medicines or vaccines that have sorbitol as a main component.
In a discrete choice experiment, adult patients had to choose, between their current fructose-restricted diet and a pharmacological therapy. A random parameter model first showed a tendency to prefer the diet. However, most participants chose an option which was closer to the pharmacological therapy. The authors therefore concluded that, despite the first model, patients were in fact more inclined towards pharmacological therapy.









***
## Results and Discussion

### Gene and Protein Identification Across Genomic Databases 
To identify which was the causative gene and protein from the WT coding sequence (CDS) and the aminoacids FASTA files, we executed sequence similarity searches using BLAST, the Basic Local Alignment Search Tool. The first search iteration arose taxonomic discrepancy because the protein query we focused on was searched against a non-human primate homologue, a Sumatran orangutan (_pongo abelii_, accession NP_001127166.1). Simultaneously, a cross-search using OMIM, the Online Mendelian Inheritance in Man, was carried out. After typing the query search "Herederitary Fructose Intolerance" and learning about this disease from the first entries, we extracted the conclusion that we had to focus on the isoenzyme Aldolase B. 

After repeating the searches, this time restricting the outputs to _Homo sapiens_, both the WT nucleotide CDS and protein sequences matched the 1-fructose,6-biphosphate aldolase B (ALDOB, accession NM_000035.4,chromosome 9q31.1 , nine exons; UniProtKB 364 amino acids, 39 473 Da, sequence updated in  2007). Querying the FASTA files compared to the human reference, sequence identity decreased from 100% (WT) to 99.91% (mutant) at the CDS level, and from 99.18% (WT) to 98.90% (mutant) at the protein level.

### Identification of the Pathogenic Variant
Pairwise alignment between the human WT and the mutant CDS sequences identified a single variation between the two, a nucleotide substitution at position 448 (c.448G>C) which has an allele frequency of 0.0031256. There was no insertion of deletion of nucleotides, so the open reading frame remains intact with no frameshift mutations. At protein level, this single nucleotide changes makes for a codificaiton of another nucleotide, causing a missense mutation at codon 150, replacing Alanine with Proline ( p.Ala150Pro ). GCA (WT codon) syntesizes Alanine, while CCA (mutant codon) synthesizes Proline. UniProtKB classifies this substitution as a physicochemical transition from a small, hydrophobic residue (Alanine, A) to a medium-sized, hydrophobic residue (Proline, P) with a BLOSUM score of −1, indicating an evolutionarily disfavoured replacement.

Although both Alanine and Proline are neutral, non-polar aminoacids that contain the same functional groups, standard carboxyl (-COOH) and amino (-NH2), the position inside the molecule affects how they interact with other molecules and backbone connectivity. The alanine amino group retains a free amide hydrogen after being incorporated to the polypeptide chain. This is due to it being in an extreme of the molecule, which allows it to act as a hydrogen-bond donor. Moreover, alanine is the aminoacid with the highest propensity to form stable α-helices in aqueous environments. On the other hand, Proline's amino group is caged inside a rigid cyclic ring that is bonded to its own backbone nitrogen atom. This means that proline has no free amide hydrogen that can act as a hydrogen-bond donor, causing a complete change in the structure of the protein. Proline bends the main chain, and acts as a classic secondary-structure breaker ("helix and β-strand breaker") due to its structural characteristics.

### Evolutionary Conservation Comparison Analysis Between Species
We compared human aldolase B with two mammals: rabbit (Oryctolagus cuniculus), the species assigned to our group, and Sumatran orangutan (Pongo abelii), a closely related primate. Following the practical guidelines, we only used curated RefSeq records: NM_001171114.1 and NP_001164585.1 for rabbit, and NM_001133694.1 and NP_001127166.1 for orangutan.

**Table 1. Sequence identity of the orthologs with human aldolase B.**

| Species | CDS identity | Protein identity | Amino-acid differences | Gaps |
|:---|:---:|:---:|:---:|:---:|
| *Pongo abelii* | 98.63 % | 99.18 % | 3 | None |
| *Oryctolagus cuniculus* | 93.42 % | 96.98 % | 11 | None |

At the CDS level, we found three long blocks identical in the three species: positions 313–389, 397–449 and 688–740. The block 397–449 ends at nucleotide 449, so it includes the first base of codon 150, the site of the variant. We also found substitutions, for example at position 465, where the human C is replaced by T in both orangutan and rabbit.

At the protein level, 351 of 364 positions (96.4 %) are identical in the three species. One of the longest identical blocks covers positions 68–167, and Ala150 lies inside it. Orangutan differs from human at 3 positions and rabbit at 11 positions; for example, Met333 is replaced by Val in both species. No gaps were found.

The three species are more similar at the protein level than at the CDS level. Many nucleotide differences do not change the amino acid (synonymous substitutions), because the genetic code is degenerate: several codons encode the same amino acid. This indicates that the protein sequence has been conserved more strongly than the DNA sequence, and that the region containing Ala150 tolerates few changes.

### Protein Structure Comparision and Atomic-Level Perturbations
We searched the PDB with the UniProt accession of human aldolase B (P05062). Four human structures are available: 1QO5 and 8D44 have no mutations, while 1XDL and 1XDM contain the A149P substitution, the same variant found in our mutant sequence. We selected 1QO5 as the WT reference because it has the highest resolution (2.50 Å), and 1XDM as the main mutant structure. For the rabbit we used 1FDJ (liver aldolase B), because most rabbit aldolase structures in the PDB belong to the muscle isoform (aldolase A), which is a different gene.

**Table 2. PDB structures analysed.**

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

Most of the changes visible in the image are at the ends where the structure isn't rigid since it molds the ends to hold onto other structures meaning that the red regions will not be taken into acount to see the superposition of the proteins.
Looking at the protein sequence in detail, there are protein mutations between the 2 sequences (E.g. p.Ser65Thr) that do not have an impact in the structure and funcionality of the protein since both of the proteins have very similar physicochemical properties. These mutations can be found through the sequences but they never have an impact on the seconday structures. 
***
## Conclusions
In resolving the molecular basis of Hereditary Fructose Intolerance (HFI) through bioinformatic tools of BLAST and OMIM records, we can see that the severity of the disorder is not caused by the amount of mutations in the genetic sequence of ALDOB, but by the chemical incompatibility of a residue with the rest of the sequence. Although the ALDOB variant is a single nucleotide mutation and thus preserves the reading frame without insertions or deletions, this single change is enough to abolish the enzymatic function of this molecule due to it highly modifying the physical properties of the protein. This is confirmed when we execute cross-species comparisons with Pongo abelii and Oryctolagus cuniculus, which reveal how mutations are silent as long as they don’t alter a spot that has been maintained across species. Proven in the accuracy percentages when compared to the Homo Sapiens CDS sequence, since the orangutan and rabbit (98.63% and 93.42% accuracy rates respectively) don’t have a 100% match in nucleotide sequences we understand that the silent variations between the genetic code occurred in the flexible ends of the DNA strands. Individuals who presented alterations in the areas that abolished the enzymatic functions of the protein couldn’t survive, consequently couldn’t reproduce and pass on the coding sequence presenting the mutation. Nature allows silent DNA changes that don’t modify the amino acid, but strictly forbids the ones that alter its structure, proving that what causes HFI is not the amount of mutations, but by the magnitude and position of them.

At the macromolecular level, analyzing the sequence with three-dimensional crystallography reveals an important biophysical factor. The mutation introduces rigidity into a protein backbone which causes a mobile and disordered three-dimensional structure across its architecture. By replacing a small, hydrogen-bond-donating Alanine with a cyclic Proline lacking a free backbone amide hydrogen, the entire -strand structure is modified and the protein can’t hold onto itself, this way the homotetramer can’t be formed and is collapsed into a homodimer.

By tracing the structural collapse to the clinical implications we are able to see how a single localized perturbation can transcend into a life-threatening disease. The loss of the ALDOB functionality in liver, kidney and small intestine means the accumulation of a metabolic toxin, fructose 1-phosphate, consequently the depletion of intracellular ATP and phosphate. This error in macromolecular folding transforms into organ failure, defining it as a secondary consequence caused by structural mutations in the protein. The method to treat this disease is through specialized diets for the affected individuals, but through experiments it has been proven that adult HFI patients agree in a daily-dose pill to be able to ingest this saccharide. 

***
## Methods

**Data sources.** The wild-type and disease-associated CDS and protein sequence (FASTA files) were provided by the course. The literature on HFI was searched in PubMed. Gene, transcript and protein records were obtained from NCBI, gene-disease relationships from OMIM, protein annotation from UniProtKB, and 3D structures from the RCSB Protein Data Bank (PDB). All databases were accessed in October 2026. Following the course guidelines, we only used curated NCBI Reference Sequence (accessions starting with NM_ for transcripts and NP_ for proteins) and discarded predicted records (XM_ and XP_).

**Sequence searches and aligments.** BLASTn (fro CDS) and BLASTp (for proteins) were run on the NCBI web server with default parameters, first without restrictions and then restricting the organism to _Homo sapiens_. For each search, we selected the curated hit with the highest identity, query coverage and lowest E-value whose description matched aldolase B. Homologs were obtained in the same way, restricting the search to _Orictolagus cuniculus_ (species assigned by the course) and _Pongo abelii_ (additional species chosen by the team). The WT and mutant sequences were compared with the BLAST pairwise alignment option, and the three species with the multiple alignment option, using the human sequence as the reference and the "query-anchored with dots for identities" view. Conserved blocks, substitutions and identities were identified from these alignments.

**Structural analysis.** PDB structures were searched with the Uniprot accession of human aldolase B (P05062) and of rabbit aldolase B (P79226). For each entry, we recorded the data of the Structure Summary Page (method,resolution,R-values,chains,biological assembly, ligand and mutation).Following the course criterion, the wild-type structure with the highest resolution was selected as the reference. The asymmetric unit and the biological assembly were compared with the image options of each page. B-factors and occupancies were read from the coordinate files in legacy PDB format, and the location and secondary structure of residue 150 were examined in the Mol*3D viewer. In the PDB files, residues are numbered without the initial methionine, so residue 150 of our sequences correspond to residue 149 (and to residue 1149 in the rabbit file 1FDJ, where chain A is numbered from 1001).

***
## Abbreviations
HFI: Hereditary fructose intolerance

CDS: Coding Sequence

ALDOB: Aldolase B

ATP: Adenosine Triphosphate

PDB: Protein Data Bank

WT: Wild-Type

NCBI: National Center for Biotechnology Information (US)

***
## Declarations
**Availability of data and materials**: All data used in this study are publicly available.
- The wild-type and mutant CDS and protein sequences (FASTA files) were provided by the course.
- The ALDOB Conservation file was also provided by the course.
- Reference sequences were obtained from NCBI (BLAST) (NM_000035.4, NP_000026.2, NM_001171114.1, NP_001164585.1, NM_001133694.1 and NP_001127166.1) and UniProtKB (P05062), and protein structures from the RCSB Protein Data Bank (1QO5, 1XDL, 1XDM, 8D44 and 1FDJ).
- All files, notes, tables and references used in this report are available in the GitHub repository 11DP-A_Hereditary-Fructose-Intolerance_IB_2026.

**Authors' contributions**: 
- **Júlia Grau Martín** (project coordinator): coordination of the project and the team, UniProtKB analysis of aldolase B (function, disease variant, physicochemical change and BLOSUM score, and protein sequence), writing of the Results section, management of the GitHub repository and publication of the final version.
- **Jana Iturriaga Pizarro** (principal investigator): PDB structure search and analysis (structure selection, asymmetric unit and biological assembly, B-factor and occupancy, location of the mutated residue and comparison with the rabbit structure), writing of the Results section (sequence conservation and protein structure) and of the Declarations.
- **Diana Zhou Chen** (lead writer and risk supervisor): PDB structure search and analysis, risk analysis of the project plan, writing of the Background and methods sections, and writing and review of the report.
- **Josep Ferré Parés** (communication and design manager): literature search on PubMed about HFI (disease, aldolase B function, diagnosis and treatment), which was used to write the Background section, writing of the Results section.

All authors took part in the BLAST searches and sequence alignments of the practical sessions, contributed to the Gantt chart and project status, and reviewed and approved the final report.
***
## References

- Blom NS, White A, Sygusch J. Fructose 1,6-bisphosphate aldolase from rabbit liver. RCSB Protein Data Bank, PDB ID 1FDJ. https://www.rcsb.org/structure/1FDJ (26 October 2026, date last accessed).

- Cross NC, Tolan DR, Cox TM. Catalytic deficiency of human aldolase B in hereditary fructose intolerance caused by a common missense mutation. Cell 1988;53:881-5.

- Dalby AR, Tolan DR, Littlechild JA. Fructose 1,6-bisphosphate aldolase from human liver tissue. RCSB Protein Data Bank, PDB ID 1QO5. https://www.rcsb.org/structure/1QO5 (26 October 2026, date last accessed).

- Esposito G, Imperato MR, Ieno L et al. Hereditary fructose intolerance: functional study of two novel ALDOB natural variants and characterization of a partial gene deletion. Hum Mutat 2010;31:1294-303. 

- Esposito G, Vitagliano L, Santamaria R et al. Structural and functional analysis of aldolase B mutants related to hereditary fructose intolerance. FEBS Lett 2002;531:152-6.

- Janssen LEF, Hiligsmann M, Timmer C et al. Treatment preferences of adult patients with hereditary fructose intolerance: a discrete choice experiment. Mol Genet Metab 2025;145:109169.

- Lyu M, Yu EW. Cryo-electron microscopy structure of human kidney fructose-bisphosphate aldolase B. RCSB Protein Data Bank, PDB ID 8D44. https://www.rcsb.org/structure/8D44 (26 October 2026, date last accessed).

- Malay AD, Allen KN, Tolan DR. Structure of human aldolase B associated with hereditary fructose intolerance (A149P), at 277K. RCSB Protein Data Bank, PDB ID 1XDL. https://www.rcsb.org/structure/1XDL (26 October 2026, date last accessed).

- Malay AD, Allen KN, Tolan DR. Structure of human aldolase B associated with hereditary fructose intolerance (A149P), at 291K. RCSB Protein Data Bank, PDB ID 1XDM. https://www.rcsb.org/structure/1XDM (26 October 2026, date last accessed).

- Ravi U, Sharma L. Fructose-1-phosphate aldolase deficiency. In: StatPearls [Internet]. Treasure Island (FL): StatPearls Publishing, 2026.
   
- Rumping L, Waterham HR, Kok I et al. Hereditaire fructose-intolerantie [Hereditary fructose intolerance]. Ned Tijdschr Geneeskd 2014;158:A6889. (In Dutch).

- Sánchez-Gutiérrez JC, Benlloch T, Leal MA et al. Molecular analysis of the aldolase B gene in patients with hereditary fructose intolerance from Spain. J Med Genet 2002;39:e56.

- Santamaria R, Vitagliano L, Tamasi S et al. Novel six-nucleotide deletion in the hepatic fructose-1,6-bisphosphate aldolase gene in a patient with hereditary fructose intolerance and enzyme structure-function implications. Eur J Hum Genet 1999;7:409-14.

- UniProt Consortium. P05062 · ALDOB_HUMAN: Fructose-bisphosphate aldolase B (Homo sapiens). UniProtKB. https://www.uniprot.org/uniprotkb/P05062/entry (26 October 2026, date last accessed).

