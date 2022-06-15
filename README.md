# Modeling RNA Binding Protein Regulatory Interactions and Expression Networks within Retinoblastoma Single Cell RNA Sequencing (scRNA) Datasets

**_Abstract_**: Retinoblastoma (Rb), a common pediatric intraocular disease, is responsible for 2% of all childhood cancers. Genomically, Rb is primarily caused by loss-of-function mutations in the RB1 gene, a well-known tumor suppressor that is characterized by its involvement in anti-apoptosis and DNA repair. RNA Binding Proteins (RBPs) modulate several cellular pathways and structures, via post-transcriptional and post-translational regulatory interactions. Dysregulation may cause the inhibition of RBP functions and interactions which may result in a metastatic cellular environment. Past research and exploratory analysis of 20 Rb xenograft samples have reflected that aberrant RBP expression is directly associated with the development of Rb, thus suggesting the need for greater knowledge of RBP interactions within the cancer. scRNA sequencing is a genomic approach involved in producing quantitative sequence profiles from mRNA transcripts. ScanPy, a Python-based package for analyzing scRNA data, was utilized for analysis of acquired sample data with RBP-target networks constructed using the MotifMap-RNA-acquired RBP datasets. Gene enrichment analysis was also performed in order to find probabilistic cellular pathways for the discovered RBPs in the Rb samples. Overall, 215 novel Rb-related RBP-target relationships were predicted. Of these, 123 relationships were found to have RNA targets that were untranslated regions. 2 relationships [HNRNPH1-APOE, QKI-APOE], with a common target APOE, were also found where both the RBP and target were identified within the samples. Higher gene expression was also seen in the astrocyte and Paneth cells across all identified RBPs and targets. Greater significance with signaling pathways pertaining to RNA binding and migration were identified within the predicted RBP-target relationships. These observations suggest how the predictions may represent therapeutic targets against Rb.

**Necessary Dependencies Required to Install:**
1. Python (Version 3.9.5)
2. ScanPy (Version 1.8.1)
3. GSEApy (Version 0.10.5)
4. NetworkX (Versions 2.6.2)
5. SciPy (Version 1.7.0)
6. NumPy (Version 1.20.2)
7. Pandas (Version 1.2.5)
8. PyGraphviz (Version 1.7)
