
# Exploring a Human Disease Gene Using UCSC Genome Browser and NCBI ClinVar
## Student Information
**Name:** Estrellanes, Klea Mae G.  
**Assigned Gene:** FMR1  
**Associated Disease:** Fragile X Syndrome  
**Genome Assembly:** GRCh38/hg38  
---
# 1. Assigned Gene and Disease
The assigned gene for this activity is **FMR1**, which stands for **Fragile X Messenger Ribonucleoprotein 1**. It is associated with **Fragile X syndrome**, a genetic disorder that mainly affects neurological development.
---
# 2. UCSC Gene Location
The FMR1 gene was searched using the UCSC Genome Browser with the human **GRCh38/hg38** genome assembly.
### Gene Information
| Parameter | Result |
|---|---|
| Official gene symbol | FMR1 |
| Full gene name | Fragile X messenger ribonucleoprotein 1 |
| Chromosome | X |
| Cytogenetic location | Xq27.3 |
| Genome assembly | GRCh38/hg38 |
| Genomic coordinates | chrX:147,911,919–147,951,125 |
| DNA strand | + |
| Approximate gene size | 39,207 bp or about 39.2 kb |
| Selected transcript | NM_002024.6 |
The UCSC Genome Browser showed FMR1 on chromosome X at Xq27.3. The gene spans approximately 39.2 kb in the GRCh38/hg38 assembly.
### Screenshot 1 – Gene Location
![FMR1 Gene Location](screenshots/01_gene_location.png)
---
# 3. Exons, Introns, and Transcripts
The **NCBI RefSeq curated** track was used to examine the structure of FMR1. The selected transcript for exon counting was **NM_002024.6**.
### Observations
- **Selected transcript:** NM_002024.6
- **Number of exons identified:** 17
- **Multiple transcripts/isoforms visible:** Yes
Exons are regions that remain in the mature RNA after RNA processing, while introns are intervening sequences removed during RNA splicing. In the UCSC Genome Browser, exons appeared as boxed regions, while introns appeared as connecting lines between the exon boxes.
The introns of FMR1 generally appeared much longer than the exons. Multiple transcript isoforms were also visible, showing that FMR1 can be processed into different transcript forms.
### Screenshot 2 – Gene Structure
![FMR1 Gene Structure](screenshots/02_gene_structure.png)
---
# 4. UCSC Annotation Tracks
The following annotation tracks were examined:
- **NCBI RefSeq**
- **MANE Select Plus Clinical**
- **ClinVar Variants**
- **ClinVar Short Nucleotide Variants**
- **100 Vertebrates Basewise Conservation by PhyloP**
ClinVar-related variant marks were visible within the FMR1 gene region.
Some regions showed stronger conservation signals than others. Several stronger peaks occurred within the FMR1 gene region, although not all exons and introns showed the same level of conservation.
Strong conservation across different species may suggest biological importance because important DNA sequences are often maintained during evolution. Regions that are highly conserved may be less tolerant of sequence changes because they may have important structural or regulatory functions.
### Screenshot 3 – Annotation Tracks
![FMR1 UCSC Tracks](screenshots/03_tracks.png)
---
# 5. Selected ClinVar Variant
A documented FMR1 variant was selected from NCBI ClinVar.
### Variant Information
| Parameter | Result |
|---|---|
| Gene | FMR1 |
| Variant | NM_002024.6(FMR1):c.80C>A |
| Protein change | p.Ser27Ter / S27* |
| Variation ID | 29987 |
| ClinVar accession | VCV000029987.1 |
| Variant type | Single nucleotide variant |
| Variant length | 1 bp |
| GRCh38 location | X:147,921,961 |
| Cytogenetic location | Xq27.3 |
| Molecular consequence | Nonsense |
| Clinical significance | Pathogenic |
| Review status | Single submission |
| dbSNP | rs1569545382 |
| Associated disease | Fragile X syndrome |
The selected variant changes coding nucleotide 80 from cytosine to adenine. This results in a nonsense mutation that changes serine at amino-acid position 27 into a premature stop codon.
### Screenshot 4 – ClinVar Record
![FMR1 ClinVar Variant](screenshots/04_clinvar_variant.png)
### ClinVar Record
https://www.ncbi.nlm.nih.gov/clinvar/variation/29987/
---
# 6. Locating the Variant in UCSC
The selected ClinVar variant was located in the UCSC Genome Browser using the GRCh38 coordinate:
**chrX:147,921,961**
The genome browser was zoomed in to examine the variant relative to the FMR1 gene model.
### Observations
**a. Where is the variant located relative to the gene?**  
The selected variant is located within the FMR1 gene.
**b. Is it in an exon, intron, UTR, splice region, or another region?**  
The variant is located within an exon.
**c. Is it likely located in a coding or non-coding region?**  
The UCSC annotation shows that the variant is located in a coding region of FMR1.
**d. How might the variant affect the gene or gene product?**  
The c.80C>A substitution changes the codon for serine at amino-acid position 27 into a premature stop codon. This produces the nonsense variant p.Ser27Ter and is predicted to terminate translation very early, resulting in a severely truncated FMRP product.
**e. What additional evidence would be needed before concluding that the variant causes disease?**  
Additional experimental evidence would be needed to determine the effect of the variant on FMRP production, stability, localization, cellular function, and disease phenotype. Functional experiments and published clinical evidence can provide stronger support for the biological consequences of the variant.
### Screenshot 5 – Variant in UCSC
![FMR1 Variant in UCSC](screenshots/05_variant_in_ucsc.png)
---
# 7. Interpretation
The UCSC Genome Browser made it possible to connect the FMR1 variant to its exact location within the gene. The c.80C>A variant is located in a coding exon and corresponds to amino-acid position 27.
The ClinVar and UCSC results together support the interpretation that the variant introduces an early stop codon. However, genome-browser location and computational annotation alone cannot demonstrate the actual biological effect of the variant in cells.
---
# 8. Reflection
### 1. What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?
The UCSC Genome Browser showed the exact genomic location and structure of FMR1, including its exons, introns, transcript isoforms, and nearby annotation tracks. It also showed how the gene is positioned relative to clinically reported variants and conserved regions.
### 2. Why is knowing the exact genomic location of a disease-associated variant useful?
Knowing the exact genomic location helps determine whether a variant lies in a coding exon, intron, UTR, splice region, or another regulatory area. This information helps predict how a variant may affect the gene or protein and allows comparison with genome annotations and clinical databases.
### 3. What is one limitation of predicting a variant's effect only from its genomic location?
Genomic location alone cannot prove the actual biological effect of a variant. Experimental studies are still needed to determine whether the variant changes protein production, stability, cellular function, or contributes to the disease phenotype.
### 4. What was the most interesting feature you observed about your assigned gene?
The most interesting feature was seeing the FMR1 c.80C>A variant directly within the coding region and aligned with amino-acid position 27. It was also interesting to observe the multiple FMR1 transcript isoforms and the differences in conservation across the gene region.
---
# 9. References and Links
### UCSC Genome Browser
https://genome.ucsc.edu/
### NCBI ClinVar
https://www.ncbi.nlm.nih.gov/clinvar/
### Selected ClinVar Variant
https://www.ncbi.nlm.nih.gov/clinvar/variation/29987/
### NCBI FMR1 Gene
https://www.ncbi.nlm.nih.gov/gene/2332
### NCBI RefSeq Transcript
https://www.ncbi.nlm.nih.gov/nuccore/NM_002024.6
---
# Summary
This activity demonstrated how the UCSC Genome Browser and NCBI ClinVar can be used together to study the genomic location, structure, annotation, and clinical significance of a disease-associated gene and variant. FMR1 was located on chromosome X at Xq27.3, and the selected transcript NM_002024.6 contained 17 identified exon blocks.
The selected ClinVar variant, NM_002024.6:c.80C>A, is a pathogenic nonsense variant located in a coding exon of FMR1. It produces the predicted protein change p.Ser27Ter and demonstrates how a single-nucleotide substitution can result in premature termination of protein translation.
