# Identification-of-Blood-based-Biomarkers-for-Early-Stage-Parkinson-s-Disease



## Abstract 

Parkinson’s disease (PD) affects millions of people worldwide and causes symptoms such as bradykinesia and disrupted speech. Parkinson’s disease is known to be characterized by the mass death of dopaminergic neurons in the substantia nigra region. In the status quo, PD is often diagnosed at late stages because obvious motor symptoms appear after the disease has progressed far. It is advantageous to diagnose PD before the onset of motor symptoms because treatments are often more effective at early stages. While motor symptoms usually manifest when over 50% of dopaminergic neurons in the substantia nigra are already lost, molecular signatures of PD may be present at early stages in patient blood. This study aimed to analyze several gene expression studies’ data for commonly differentially expressed genes (DEGs) in the blood of early stage PD patients. 147 DEGs were identified in at least two out of three datasets and passed cut-off criteria. A protein interaction network for the DEGs was constructed and various tools were used to identify network characteristics and hub genes. PANTHER analysis revealed that the biological process “cellular response to glucagon stimulus” was overrepresented by almost 21 times among the DEGs and “lymphocyte differentiation” by 5.98 times. Protein catabolic processes and protein kinase functions were also overrepresented. ESR1, CD19, SMAD3, FOS, CXCR5, and PRKACA may be potential biomarkers and warrant further study. Overall, the findings of the present study provide insights on molecular mechanisms of PD and provide greater confidence on which genes are differentially expressed in PD. The results also are additional evidence for the role of the immune system in PD, a topic that is gaining interest in the PD research community.


## Clinical Trial

This study was using pre-existing gene expression data available freely from the NCBI Gene Expression Omnibus.

### Data Availability

The data is publicly available from the respective Gene Expression Omnibus studies from which they were retrieved. I do not claim credit for the data. Other researchers obtained that data and credit goes to them. 

- Supplemental STRING network: https://version-11-0b.string-db.org/cgi/network?networkId=bns9q9ZNmuqR 

- List of 147 Differentially Expressed Genes https://docs.google.com/spreadsheets/d/1kAj7B2oXeNSK-Bha7Xo14IRv_Z1xTGCcdwOxRYdWem8/edit?usp=sharing 

- Venn Diagram Results https://docs.google.com/spreadsheets/d/1g4-k2lGj78hG1rLhMsQbK77MQ-TBe9QQNAADhLfFDlI/edit?usp=sharing

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE6613

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=gse54536

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=gse72267



## IMPORTANT NOTE

- We will be using the Gene Expression Omnibus to access and analyze data.

- The Gene Expression Omnibus can be accessed here: https://www.ncbi.nlm.nih.gov/geo/

- If you were not able to understand, check out this excellent resource: https://biochem.slu.edu/bchm628/handouts/2013/GEO_Tutorial_2012.pdf

- Finally, You must define the EXPERIMENTAL/DISEASE group FIRST and the CONTROL/WILD-TYPE group SECOND.

- GEO2R also recently updated its user interface. Most features are the same except the colors are now blue and purple instead of red and blue. Also, it conveniently generates charts.

**Thank you.**



## What is the Gene Expression Omnibus?

- The Gene Expression Omnibus, or GEO, is an online website where scientists upload data from their experiments. 
- You can find gene expression, microRNA expression, and many other types of DNA/RNA data. 
- The data is all freely accessible.

## Finding a Dataset

1. Number of samples (25+ is good, too much is not good, such as 5000. It takes too long to run and GEO2R will time out)

2. Organism

3. Type of "thing" analyzed: tissue, blood, etc.

4. Treatment? Make sure the changed variable between control and experimental is what you want. If you're finding diagnostic biomarkers for lung cancer, you want a dataset that's just control samples and lung cancer samples. You don't want control samples and lung cancer samples treated with a drug, for example.

5. ANALYZE with GEO2R button! Very important. The dataset must have this!



## Bioinformatics Tools Used:

- GEO2R, 

- [StringDB](https://string-db.org) 

- [PantherDB](http://geneontology.org)

- [Researching Individual Genes](https://scholar.google.com) 
