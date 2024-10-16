# Transcriptomics-study-of-differential-genes-to-identify-novel-genes-and-pathways


 A revolutionary type of therapy that emphasises on the complex genetics of disorders has
 developed as a result of the growth of research on autoimmune diseases and the
 microenvironment. In this study rheumatoid arthritis (RA) and systemic lupus erythematosus
 (SLE) were examined for their shared gene expression characteristics using GEO2R tool by
 using the gene expression dataset GS17755, which is accessible through the Gene Expression
 Omnibus database that is collected on the basis of Gene expression profiling of blood cells
 from patients with autoimmune diseases and healthy individuals using DNA microarray
 analysis. GEO2R tool was used to find the Differential expression genes between both of the
 disorders Systemic lupus erthematosus and rheumotoid arthritis to identify the upregulated
 and downregulated genes expression and differences in expressoion and further to classify
 them at functionally Functional and molecular pathway analysis was done using the enrichr
 web server and finally string and cytoscape is used for futher analysis of networks. A total of
 954 DEGs associated with RA of which 517 genes were overexpressed or upregulated and
 436 genes downregulated and and a total of 454 DEGs assosciated to SLE were
 found of which 186 genes were up-regulated and 268 genes were downregulated


 
  ### Differential gene expression(DGE ) analysis :

 Differential gene expression(DGE ) analysis makes it feasible to assess and quantify gene
 expression in cells. The main objective of differential expression study is to identify the
 novel genes that are expressed differently under various situations. The biological processes
 impacted by the condition that are of significance can be better understood by looking at
 these genes..Fig. 2.5: General work-flow for the analysis The general methodology for DGE
 analysis: Most available tools follow these steps but are not necessary



 
 ### Dataset:

 Dataset (GSE17755) utilized in this study was obtained through the Gene Expression
 Omnibus database which had collected on the basis of Gene expression profiling of blood
 cells from patients with autoimmune diseases and healthy individuals using DNA microarray
 analysis. The DNA microarray, Hitachisoft AceGene Human Oligo Chip 30K 1 Chip
 Version, and the widely used GPL1291 platform were used to create this dataset.
 The GEO dataset GSE17755 is loaded into the tool which basically contains 244 samples of
 patients with autoimune diseases

 
 ### Observation:


Finding DEGs in the two groups of samples under comparison was the first step using the
 shortlisted table from the GEO2R tool, there were 954 DEGs identifid in case of RA and 454
 genes in case of SLE. Data obtained was sorted with respect to p-value less than 0.05. The
 data was again filtered with p-adj(adjusted value less than 0.05. The genes obtained were the
 differentially genes that were 954 and 454 in number Further filtering was done with respect
 to log2fold change data was filtered with a threshold of 0.5 .From the statistical analysis of
 above results gives 436 down-regulated and 517 up-regulated genes (954 in total)in case of
 RAand 268 down-regulated and 186 up-regulated genes (454 in total) in case of SLE
 Firstly the samples are defined Control and RA according to the data in GEO2R tool in
 which we can't define samples more than 10.After deciding groups of samples i.e Control Vs
 RAand Control Vs SLE analysis was done with significant parameters.Results obtained from
 here were shown as table in which top 250 genes basically ranked by significant values.
 Different types of plots or graphical representation of DEGs was obtained from the GEO2R
 tool which are used to depiction the significant genes .The outcomes of a differential gene
 expression investigation are frequently displayed using volcano plots, a sort of scatter plot.
 They can be used to swiftly determine whether genes' expression has been considerably
 changed by a perturbation and to compare how similarly two groups of biological samples
 have expressed certain genes globally. The scatter figure shows the significant value vs fold
change calculated by the GEO2R tool during differential expression analysis, with each point
 representing a gene






 
