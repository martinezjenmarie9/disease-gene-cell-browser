# From Genome to Cell: Exploring Disease Gene Using the UCSC Cell Browser
**Name:** Jen Marie A. Martinez **Assigned Gene:** PSEN1  **Associated Disease:** Early-Onset Alzheimer's Disease (EOAD)  
**Organism:** Human  **Selected Organ/Tissue:** Brain 

## UCSC Cell Browser Dataset
**Selected Dataset:** Aging Brain and Alzheimer's Disease

**Reason for Selection:**  I chose the Aging Brain and Alzheimer’s Disease dataset because it provides single-cell RNA sequencing data specifically focused on human brain tissues, specifically focusing on human prefrontal cortex tissue affected by Alzheimer’s disease. Since my assigned gene is PSEN1, which is heavily linked to early-onset Alzheimer's, this dataset is a great fit. It allows me to explore how PSEN1 is expressed across different types of brain cells,such as neurons, giving me a clearer picture of its potential role and cellular involvement in the disease pathology.

**Relevant Cell Types:**  Prefrontal cortex 

**Publication/Study:**  Epigenomic dissection of Alzheimer's disease pinpoints causal variants and reveals epigenome erosion (Manolis Kellis, Li-Huei Tsai Lab, MIT)

**UCSC Cell Browser Dataset URL:**  [https://cells.ucsc.edu/?ds=ad-aging-brain](https://cells.ucsc.edu/?ds=ad-aging-brain+ad-atac)]

## Understanding the Cell Map

**a. What type of visualization is being shown?**  A two-dimensional scatter plot layout (UMAP/t-SNE) used to visualize high-dimensional single-cell genomic data.

**b. What does one dot represent?**  Each dot represents an individual cell nucleus, as this is a single-nucleus RNA sequencing (snRNA-seq) dataset.

**c. What do the clusters represent in this particular dataset?**  The clusters represent distinct groups of cells with similar molecular profiles, corresponding to major cell types found in the human prefrontal cortex.

**d. List at least three cell-type or cluster labels visible in the dataset:**  
  * Excitatory neurons (Exc)
  * Oligodendrocytes (Oli)
  * Inhibitory neurons (Inh)

##  Assigned Gene Expression

**a. Assigned gene symbol:** PSEN1

**b. Dataset used:** The dataset used is the single-nucleus RNA sequencing (snRNA-seq) of the prefrontal cortex across 92 individuals from the aging brain and Alzheimer's disease collection.

**c. Is expression widespread, restricted, or low/undetected?** Widespread across multiple major cell populations.

**d. Which cluster(s) appear to contain cells with stronger expression?** Oligodendrocytes (Oli), Excitatory neurons (Exc), and Astrocytes (Ast).

**e. Which cluster(s) appear to contain little or no detectable expression?** Vascular cells (Vas) and certain sub-regions showing sparser grey/undetected levels.

## Cell Types and Clusters

**a. Cell type/cluster with the strongest visible expression:**  The cell type cluster showing the strongest and most dense visible *PSEN1* expression is the Oligodendrocytes (Oli) cluster.

**b. Another cell type/cluster with detectable expression:**  Another cell population with clear, detectable expression is the Oligodendrocyte progenitor cells (Opc) cluster and the Excitatory cluster (Exc).

**c. Cell type/cluster with relatively low or undetected expression:**  The Vascular cells (Vas) display relatively low or minimal detectable expression.

**d. Is the expression pattern broad or cell-type restricted?**  The expression pattern is broad, as PSEN1 transcripts are visible across multiple major cell types rather than being strictly limited to a single population.

**e. Biological explanation:**  Based on this selected dataset, the widespread presence of PSEN1 across various neural and glial cell types suggests that it plays a fundamental housekeeping or regulatory role in cellular maintenance. Because PSEN1 encodes an essential component of the gamma-secretase complex, its expression is expected across diverse brain cell populations to support critical transmembrane cleavage pathways.Please note that this is an interpretation based on the selected dataset.  

## Expression Plot

**a. Which cells/cluster did you select?**  The dot plot compares all cell types simultaneously, highlighting Oligodendrocytes (Oli) as the primary population of interest.

**b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?**  The oligodendrocytes (Oli) show a higher expression intensity and a larger fraction of expressing cells compared to most other cell types in the prefrontal cortex dataset.

**c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?**  The dot plot adds a clear quantitative breakdown by simultaneously displaying both the average expression level (via color intensity) and the precise fraction of cells expressing the gene (via dot size) across every cluster, which is harder to gauge precisely from scatter density alone.

### Marker Genes

**a. Cluster/cell type examined:** Oligodendrocytes (Oli)

**b. Marker gene 1:** MBP

**c. Marker gene 2:** MOBP

**d. Marker gene 3:** OLIG1

**e. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly:** PSEN1 does not behave like a cell-type-specific marker. Unlike traditional markers that are tightly restricted to single lineages, PSEN1 displays a broad, generalized expression pattern across multiple cell populations in the prefrontal cortex.

###  Disease Gene vs. Marker Gene

**a. Assigned disease gene:** PSEN1
  
**b. Marker gene:** OLIG1
  
**c. Which gene shows a more cell-type-restricted expression pattern?** OLIG1 is restricted primarily to the oligodendrocyte and progenitor lineages.
  
**d. Which gene appears more broadly expressed?** PSEN1 is expressed broadly across multiple cell populations in the prefrontal cortex.

**e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?** It demonstrates that disease-associated genes (like PSEN1) can have generalized or widespread housekeeping functions across many cell types rather than uniquely defining a single lineage, whereas cell-type markers (like OLIG1) are specialized transcripts utilized to identify specific cellular identities.

## Connection to Genome Browser and ClinVar

**1. On which chromosome is your assigned gene located?**  PSEN1 is located on Chromosome 14 (chr14).

**2. What disease-associated variant did you examine previously?**  I examined pathogenic missense variants, specifically p.Gly206Ala (Variation ID: 18143), associated with early-onset familial Alzheimer's disease.

**3. In the current Cell Browser dataset, which cell type(s) express the gene?**  PSEN1 is expressed broadly across multiple major brain cell populations in the prefrontal cortex, prominently including Oligodendrocytes (Oli), Excitatory Neurons (Exc), and Astrocytes (Ast).

**4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease? Explain in 3–5 sentences.**  The observed expression pattern makes strong biological sense. PSEN1 encodes an essential component of the gamma-secretase complex, which mediates the cleavage of vital transmembrane proteins like the Amyloid Precursor Protein (APP). Because these baseline proteolytic and cell-signaling pathways are required across various neural and glial environments, transcription is expected to span multiple cell populations. This generalized presence aligns with how Alzheimer's disease pathology impacts both neuronal networks and supporting glial cells throughout the brain.

**5. Can this single Cell Browser dataset prove that the gene causes the disease? Explain why or why not.**  A single single-nucleus RNA-seq dataset cannot prove causation on its own. The Cell Browser provides observational, correlative evidence showing transcriptional expression levels across cell types, but it does not test functional impact. Proving definitive disease causation requires rigorous experimental validation, such as functional genetic assays, mechanistic studies, or in vivo disease models.

##  Short Reflection

**1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?**  While the regular Genome Browser gave me a close-up look at PSEN1's DNA sequence and physical layout on chromosome 14, it couldn't tell me where that gene is actually active in tissue. The Cell Browser really filled in that blank by letting me see how the gene's expression lights up across different cell types in the brain, like neurons versus oligodendrocytes. It completely bridged the gap between raw genomic data and real biological context in specific cells.

**2. Why can the same gene have different expression levels among different cell types?**  Different cell types have unique jobs to do, so they don't all turn on the same genes in the exact same amounts. Even though a gene might be present across the board, regulatory proteins and epigenetic factors control how actively it gets transcribed depending on what that specific cell needs. For instance, a neuron might require different levels of a protein compared to an astrocyte or glial cell to carry out its daily functions.

**3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?**  Seeing zero expression for a gene in a single-cell dataset doesn't automatically mean the cell doesn't use it at all. Single-cell RNA sequencing can suffer from technical "dropouts" where low-abundance transcripts just aren't captured during sequencing, or the gene might be transcribed in short, intermittent bursts. It's easy to misinterpret blank spots as a total lack of function when it could just be a limitation of the technology or sequencing depth.

**4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?**  Combining all these layers gives you the full picture rather than just looking at isolated pieces of the puzzle. Knowing where a mutation sits on the chromosome tells you the structural problem, but seeing it alongside cell-specific expression helps you figure out which specific cell types are most vulnerable to that change. It successfully connects DNA-level genetics with actual tissue-level disease mechanisms.

**5. What was the most interesting observation you made about your assigned gene?**  The coolest thing I noticed was how PSEN1 didn't act like a neat, exclusive cell-type marker, but instead showed up across a bunch of different brain cells like neurons and oligodendrocytes. It really highlighted how a gene can play a vital, widespread housekeeping role across the entire brain tissue rather than just defining one single type of cell. Seeing that contrast completely changed how I think about disease-associated genes versus standard marker genes.

## Links 
(https://cells.ucsc.edu/?ds=ad-aging-brain)

(https://cells.ucsc.edu/?ds=ad-aging-brain+ad-atac)]
