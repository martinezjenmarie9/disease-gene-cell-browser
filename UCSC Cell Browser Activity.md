# From Genome to Cell: Exploring Disease Gene Using the UCSC Cell Browser
**Name:** Jen Marie A. Martinez
**Assigned Gene:** PSEN1  
**Associated Disease:** Early-Onset Alzheimer's Disease (EOAD)  
**Organism:** Human  
**Selected Organ/Tissue:** Brain 

## Part B. UCSC Cell Browser Dataset
**Selected Dataset:** Aging Brain and Alzheimer's Disease

**Reason for Selection:**  
I chose the Aging Brain and Alzheimer’s Disease dataset because it provides single-cell RNA sequencing data specifically focused on human brain tissues, specifically focusing on human prefrontal cortex tissue affected by Alzheimer’s disease. Since my assigned gene is PSEN1, which is heavily linked to early-onset Alzheimer's, this dataset is a great fit. It allows me to explore how PSEN1 is expressed across different types of brain cells,such as neurons, giving me a clearer picture of its potential role and cellular involvement in the disease pathology.

**Relevant Cell Types:**  
Prefrontal cortex 

**Publication/Study:**  
Epigenomic dissection of Alzheimer's disease pinpoints causal variants and reveals epigenome erosion (Manolis Kellis, Li-Huei Tsai Lab, MIT)

**UCSC Cell Browser Dataset URL:**  
[https://ad-aging-brain.cells.ucsc.edu](https://ad-aging-brain.cells.ucsc.edu]

### Required proof - Screenshot 1
The prefrontal cortex is one of the key brain regions heavily impacted by neurodegeneration in Alzheimer's disease. Focusing on this tissue allows me to examine how the PSEN1 gene is expressed across critical cell types like neurons and supporting cells to understand their role in the disease.

![Dataset Proof](images/your-screenshot-filename.png)]

## Part C: Understanding the Cell Map

**a. What type of visualization is being shown?**  
  A two-dimensional scatter plot layout (UMAP/t-SNE) used to visualize high-dimensional single-cell genomic data.

**b. What does one dot represent?**  
  Each dot represents an individual cell nucleus, as this is a single-nucleus RNA sequencing (snRNA-seq) dataset.

**c. What do the clusters represent in this particular dataset?**  
  The clusters represent distinct groups of cells with similar molecular profiles, corresponding to major cell types found in the human prefrontal cortex.

**d. List at least three cell-type or cluster labels visible in the dataset:**  
  * Excitatory neurons (Exc)
  * Oligodendrocytes (Oli)
  * Inhibitory neurons (Inh)

## Part D: Search for Your Assigned Gene

**a. Assigned gene symbol:** PSEN1

**b. Dataset used:** 
The dataset used is the single-nucleus RNA sequencing (snRNA-seq) of the prefrontal cortex across 92 individuals from the aging brain and Alzheimer's disease collection.

**c. Is expression widespread, restricted, or low/undetected?** 
Widespread across multiple major cell populations.

**d. Which cluster(s) appear to contain cells with stronger expression?** 
Oligodendrocytes (Oli), Excitatory neurons (Exc), and Astrocytes (Ast).

**e. Which cluster(s) appear to contain little or no detectable expression?** 
Vascular cells (Vas) and certain sub-regions showing sparser grey/undetected levels.

### Required proof - Screenshot 2
![PSEN1 Gene Expression Proof](images/image_752bfe.jpg)

## Part E: Identify the Cell Types Expressing Your Gene

**a. Cell type/cluster with the strongest visible expression:**  
The cell type cluster showing the strongest and most dense visible *PSEN1* expression is the Oligodendrocytes (Oli) cluster.

**b. Another cell type/cluster with detectable expression:**  
Another cell population with clear, detectable expression is the Oligodendrocyte progenitor cells (Opc) cluster and the Excitatory cluster (Exc).

**c. Cell type/cluster with relatively low or undetected expression:**  
The Vascular cells (Vas) display relatively low or minimal detectable expression.

**d. Is the expression pattern broad or cell-type restricted?**  
The expression pattern is broad, as PSEN1 transcripts are visible across multiple major cell types rather than being strictly limited to a single population.

**e. Biological explanation:**  
Based on this selected dataset, the widespread presence of PSEN1 across various neural and glial cell types suggests that it plays a fundamental housekeeping or regulatory role in cellular maintenance. Because PSEN1 encodes an essential component of the gamma-secretase complex, its expression is expected across diverse brain cell populations to support critical transmembrane cleavage pathways.Please note that this is an interpretation based on the selected dataset.  

### Required proof - Screenshot 3
![PSEN1 Gene Expression and Cell Types Proof](images/image_760e36.jpg)

## Part F: Select Cells and Examine an Expression Plot

**a. Which cells/cluster did you select?**  
The dot plot compares all cell types simultaneously, highlighting Oligodendrocytes (Oli) as the primary population of interest.

**b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?**  
The oligodendrocytes (Oli) show a higher expression intensity and a larger fraction of expressing cells compared to most other cell types in the prefrontal cortex dataset.

**c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?**  
The dot plot adds a clear quantitative breakdown by simultaneously displaying both the average expression level (via color intensity) and the precise fraction of cells expressing the gene (via dot size) across every cluster, which is harder to gauge precisely from scatter density alone.

 ### Required proof - Screenshot 4
![Dot Plot Expression Comparison Proof](images/image_762f61.png)

### Part G: Explore Marker Genes

**a. Cluster/cell type examined:** Oligodendrocytes (Oli)

**b. Marker gene 1:** MBP

**c. Marker gene 2:** MOBP

**d. Marker gene 3:** OLIG1

**e. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly:** 
PSEN1 does not behave like a cell-type-specific marker. Unlike traditional markers that are tightly restricted to single lineages, PSEN1 displays a broad, generalized expression pattern across multiple cell populations in the prefrontal cortex.

 ### Required proof - Screenshot 5
![Marker Gene Comparison Proof](images/image_8105a1.jpg)

### Part H: Compare Your Assigned Gene With One Marker Gene

**a. Assigned disease gene:** PSEN1
  
**b. Marker gene:** OLIG1
  
**c. Which gene shows a more cell-type-restricted expression pattern?** 
OLIG1 is restricted primarily to the oligodendrocyte and progenitor lineages.
  
**d. Which gene appears more broadly expressed?** 
PSEN1 is expressed broadly across multiple cell populations in the prefrontal cortex.

**e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?** 
It demonstrates that disease-associated genes (like PSEN1) can have generalized or widespread housekeeping functions across many cell types rather than uniquely defining a single lineage, whereas cell-type markers (like OLIG1) are specialized transcripts utilized to identify specific cellular identities.

### Required proof - Screenshot 6
![Multi-Gene Comparison Dot Plot Proof](images/image_8188ce.png)

