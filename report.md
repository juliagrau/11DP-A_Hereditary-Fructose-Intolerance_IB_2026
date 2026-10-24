#  Hereditary Fructose Intolerance: analysis on the causes
Ferré Parés Josep, Grau Martín Júlia, Iturriaga Pizarro Jana, Zhouchen Diana

Bachelor's Degree in Bioinformatics, UPC-UPF-UAB-UB, Barcelona, Spain

## Abstract
[Provide a structured abstract covering Background, Results, and Conclusions (Max 350
words).]
### Keywords
Hereditary Fructose Intolerance (HFI), Aldolase B, Protein Structure, Fructose-1 [Keyword 1, Keyword 2, Keyword 3, Keyword 4, Keyword 5]

## Background

Fructose is a monosaccharide found in foods consumed daily, such as fruits, vegetables, and sweeteners, and it is also produced in small amounts by the brain. Aldolase B is one of the three aldolase isoenzymes and is found in the liver, kidney, and intestinal tissue, which are important organs in fructose metabolism (Ravi and Sharma 2026). It catalyses the reversible conversion of fructose 1,6-bisphosphate into glyceraldehyde 3-phosphate and dihydroxyacetone phosphate in glycolysis and gluconeogenesis, and it also cleaves fructose 1-phosphate in fructolysis.

Hereditary fructose intolerance (HFI) is an autosomal recessive disorder caused by mutations in the gene that codes for the isoenzyme aldolase B (ALDOB). It is an inherited condition with an estimated prevalence of 1 in 20 000 people, and it affects both sexes equally. When a person with HFI ingests fructose, fructokinase quickly converts it into fructose 1-phosphate. Without aldolase B to process this molecule, it accumulates, causing a depletion of both ATP and phosphate, which is responsible for long-term organ injury. The accumulation also increases the degradation of adenine nucleotides by adenosine deaminase, which increments the production of uric acid. In additinal, the rise in uric acid is similar in glucose-6-phosphatase deficiency and fructose 1,6-bisphosphatase deficiency. 
The acumulation of fructose also activates pyruvate kinase, the enzyme that catalyses the final step of glycolysis, so precursors of the Krebs cycle build up and contribute to acidosis. As a result, it leads to abdominal pain, vomit, nausea, hypoglycemia (a drop of blood sugar level) and even kidney and liver failure, which can be life-threatening. 

HFI is diagnosed after several clinical tests that look at how the body reacts once the patient has eaten fructose, sucrose, or foods containing sorbitol. A more invasive option is a liver biopsy, which is used to check whether aldolase B is present. The urine can also be inspected for reducing substances, and the values are compared with the expected results. The main treatment for HFI is a diet free of fructose and sucrose, including products that contain sorbitol. This includes medicines or vaccines that have sorbitol as a main component.
In a discrete choice experiment, adult patients had to choose, between their current fructose-restricted diet and a pharmacological therapy. A random parameter model first showed a tendency to prefer the diet. However, most participants chose an option which was closer to the pharmacological therapy. The authors therefore concluded that, despite the first model, patients were in fact more inclined towards pharmacological therapy.

(informacion de notes pero no tengo ni idea de donde se ha sacado)

For aldolase B to work, it must fold correctly into a homotetramer. Its four identical subunits need enough flexibility to open and close their contact interfaces and to orient the catalytic amino acids into exact positions, a process called induced fit. A variant that changes the properties of the protein chain may therefore stop the enzyme from working properly. Many ALDOB variants cause disease, but here we focus on p.Ala150Pro (c.448G>C), which has an allele frequency of 0.0031256 .




Three-dimensional structures of aldolase B are available in the Protein Data Bank (PDB). The reference structure of the human enzyme (1QO5) was solved by X-ray diffraction at a resolution of 2.50 Å from a protein produced in Escherichia coli, and it shows a homotetramer. Two structures of the A149P mutant (1XDL and 1XDM) were solved by X-ray diffraction at 3.00 Å, at 277 K and at 291 K respectively, and the mutant is described as a homodimer instead of a tetramer (Malay et al. 2005). The residue changed in this variant is numbered 150 in UniProt but 149 in these structures, because the PDB numbering does not count the initial methionine. Finally, the structure of the rabbit (Oryctolagus cuniculus) liver aldolase (1FDJ), solved at 2.10 Å in complex with substrate and product ligands, allows the human protein to be compared with that of another mammal (Author Year).

***
## Results
[Present your findings. Use subheadings as needed.]
### Gene and Protein Identification Across Genomic Databases 
To identify which was the causative gene and protein from the WT coding sequence (CDS) and the aminoacids FASTA files, we executed sequence similarity searches using BLAST, the Basic Local Alignment Search Tool. The first search iteration arose taxonomic discrepancy because the protein query we focused on was searched against a non-human primate homologue, a Sumatran orangutan (_pongo abelii_, accession NP_001127166.1). Simultaneously, a cross-search using OMIM, the Online Mendelian Inheritance in Man, was carried out. After typing the query search "Herederitary Fructose Intolerance" and learning about this disease from the first entries, we extracted the conclusion that we had to focus on the isoenzyme Aldolase B. 

After repeating the searches, this time restricting the outputs to _Homo sapiens_, both the WT nucleotide CDS and protein sequences matched the 1-fructose,6-biphosphate aldolase B (ALDOB, accession NM_000035.4,chromosome 9q31.1 , nine exons; UniProtKB 364 amino acids, 39 473 Da, sequence updated in  2007). Querying the FASTA files compared to the human reference, sequence identity decreased from 100% (WT) to 99.91% (mutant) at the CDS level, and from 99.18% (WT) to 98.90% (mutant) at the protein level.

### Identification of the Pathogenic Variant
Pairwise alignment between the human WT and the mutant CDS sequences identified a single variation between the two, a nucleotide substitution at position 448 (c.448C>G). There was no insertion of deletion of nucleotides, so the open reading frame remains intact with no frameshift mutations. At protein level, this single nucleotide changes makes for a codificaiton of another nucleotide, causing a missense mutation at codon 150, replacing Alanine with Proline ( p.Ala150Pro ). GCA (WT codon) syntesizes Alanine, while CCA (mutant codon) synthesizes Proline. UniProtKB classifies this substitution as a physicochemical transition from a small, hydrophobic residue (Alanine, A) to a medium-sized, hydrophobic residue (Proline, P) with a BLOSUM score of −1, indicating an evolutionarily disfavoured replacement.

Although both Alanine and Proline are neutral, non-polar aminoacids that contain the same functional groups, standard carboxyl (-COOH) and amino (-NH2), the position inside the molecule affects how they interact with other molecules and backbone connectivity. The alanine amino group retains a free amide hydrogen after being incorporated to the polypeptide chain. This is due to it being in an extreme of the molecule, which allows it to act as a hydrogen-bond donor. Moreover, alanine is the aminoacid with the highest propensity to form stable α-helices in aqueous environments. On the other hand, Proline's amino group is caged inside a rigid cyclic ring that is bonded to its own backbone nitrogen atom. This means that proline has no free amide hydrogen that can act as a hydrogen-bond donor, causing a complete change in the structure of the protein. Proline bends the main chain, and acts as a classic secondary-structure breaker ("helix and β-strand breaker") due to its structural characteristics.


## Discussion
[Discuss implications, compare with existing research, and highlight limitations.]
***
## Conclusions
[State the main conclusions and their significance.]
***
## Methods
[Provide technical details for reproducibility: Data Sources, Implementation, Statistical
Analysis.]
***
## Abbreviations
[List abbreviations used, e.g., AI: Artificial Intelligence.]
Hereditary fructose intolerance (HFI)

***
## Declarations
Availability of data and materials: [Statement on repository/access]
Authors' contributions: [Specify roles]
***
## References
1. Author A, Author B. Title. BMC Bioinformatics. Year;Vol:Pages.
