# RNASeqMelanoma
## Identification of Critical Candidate Genes in Melanoma Development and Progression 
This repository contains the research and analysis conducted as part of my thesis project titled "Identification of Critical Candidate Genes during Melanoma Development and Progression based on RNA sequencing data.

## Abstract 

Melanoma is a lethal form of skin cancer. Over 90% of cancer patients die from metastatic disease, which happens when the cancer cells migrate from their primary sites to distant organs. The incidence 
of melanoma has rapidly grown recently, and the survival rate of melanoma patients is still poor. Melanoma develops when melanocytes in the skin change, divide uncontrollably, and expand radially. 
After this radial development, vertical growth may occur, which leads to an invasion through the basement membrane into the dermis below and results in metastasis.

In this study, we aimed to identify key regulators and candidate genes responsible for the transition to the individual stages of melanoma development. Therefore, we determined differentially expressed 
genes (DEGs) comparing NHEMs and cells derived from different developmental steps of melanoma (RGP, VGP, and MET). DEGs were identified and analysed using the Deseq2 v1.34.0 package from Bioconductor. Moreover, Over Representation Analysis (ORA) and Gene Set Enrichment Analysis (GSEA) were performed to assign biological function to the determined stage dependent deregulated genes. 

In total, we demonstrated 2308 up-regulated genes in RGP melanoma cells, 1903 up-regulated genes in the VGP melanoma cells, and 1793 up-regulated genes in MET. The upregulated DEGs, such as JAG1, 
JAG2, Col5A2, LUM, and POSTN were significantly enriched in the angiogenesis process in the MET cell line.

## RNA-Sequencing data
Human melanoma cell lines Sbcl-2, WM3211, WM1366, WM793, WM1158, and WM9 (which were obtained from Dr. M. Herlyn, Wistar Institute, Philadelphia, USA) represent the radial growth phase 
RGP (Sbcl-2), vertical growth phase VGP (WM3211, WM1366, WM793), and melanoma MET (WM1158, WM9). At 37 °C and 5% CO2, the cell lines were kept in a culture medium made up of MCDB153 (Sigma-Aldrich, Steinheim, Germany) with 20% Leibovitz’s L-15 (PAA Laboratories, Coelbe, Germany), 2% FCS, 1.68mM CaCl2 (Sigma), and 5 μg/ml insulin (Sigma- Aldrich, Steinheim, Germany). NHEMs represent the normal cells, were cultured in melanocyte growth media M2 at 37 °C and 5% CO2, and were obtained from neonatal foreskin (NHEMs, PromoCell, Heidelberg, Germany) (Kappelmann-Fenzl et al., 2019).

The RNA-Seq dataset used in this study is a standard Illumina data set (Paired-end) obtained from Prof. Dr. Melanie Kappelmann-Fenzl. The RNA-Seq dataset was shared through the sFTP server from the 
supercomputer cluster server of the Deggendorf Institute of Technology. In addition, the data is publically available in the NCBI database (https://www.ncbi.nlm.nih.gov/bioproject/PRJNA839865).
All experimental working steps were performed at the University of Erlangen (FAU) at the Institute of Biochemistry previous to the data analysis performed in this study. 
The bioinformatical analyses are based on already published sequencing data of the aforementioned cell lines. The preparation of the sequencing library involved at least two biological replicates. RNA-Seq was carried out using Illumina HiSeq2000 with the paired-end module, following Illumina's paired-end RNA-Sequencing (RNA-Seq) protocols (Illumina, Inc.)(Kappelmann-Fenzl et al., 2019). 
The RNA-Seq dataset was shared through the sFTP server from the supercomputer cluster server of the Deggendorf Institute of Technology, each file in the FASTQ file format. The used data are now publicly 
available on the NCBI database (https://www.ncbi.nlm.nih.gov/bioproject/PRJNA839865).


