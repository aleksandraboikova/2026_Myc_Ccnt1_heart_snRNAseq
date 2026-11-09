# A transient modified mRNA encoding Myc and Cyclin T1 improves cardiac function after myocardial injury

Myc is an evolutionarily conserved transcription factor that is necessary for the restoration of tissues in multiple regenerative species. The adult mammalian heart lacks regenerative capacity and cardiomyocytes fail to divide following damage-induced signalling. Transgenic expression of Myc and Cyclin T1 can drive substantial adult cardiomyocyte proliferation to replace lost cardiomyocytes. Here, using transgenic models and a prototypical mRNA therapeutic we show that Myc and Cyclin T1 require transient induction for cardiomyocyte proliferation that leads to myocardial repair and functional recovery after myocardial infarction in mice. This research provides a strategy to translate Myc-Cyclin T1 co-expression for cardiac regeneration to address serious unmet needs in the treatment of cardiovascular disease.

Mouse whole heart single-nucleus RNA sequencing data analysis included:

1. Preprocessing of cellranger output filtered barcode matrices into Seurat objects (Seurat) followed by QC and doublet removal (DoubletFinder)
2. Integration, clustering and annotation of cell populations
3. Cardiomyocyte subset analysis - differential gene expression analysis, cell cycle scoring, gene list enrichment analysis (clusterProfiler), pseudotime trajectory inference (Monocle3)
4. Differential cell-cell communication analysis with NicheNet and CellChat

Data availability:
All sequencing datasets generated and used in this study, have been deposited in European Nucleotide Archive (www.ebi.ac.uk/ena) under accession code PRJEB52314 and GEO accessions GSE248286 and GSE297340. Further information and requests for resources and reagents should be directed to Dr Catherine Wilson (chw39@cam.ac.uk).

Citation:

Boikova, A., Quaife-Ryan, G.A., Batho, C.A.P. et al. A transient modified mRNA encoding Myc and cyclin T1 improves cardiac function after myocardial injury. Nat Cardiovasc Res (2026). https://doi.org/10.1038/s44161-026-00910-7
