# Bioinformatics & Multi-Omics Resources

![Bioinformatics & Multi-Omics Resources](DatanalRs/data.png)

A curated directory of web platforms, databases, R packages, statistical methods, and interactive applications for bioinformatics, cancer genomics, transcriptomics, immuno-oncology, single-cell analysis, proteomics, metabolomics, microbiome research, and multi-omics integration.

Resources are organized by their primary research application to help researchers identify suitable tools, datasets, and analytical workflows.

## Table of Contents

1. Cancer Genomics and Gene-Expression Analysis
2. Tumor Immunology and Immunotherapy
3. RNA-seq and Differential Expression Analysis
4. Gene Sets, Pathways, Enrichment, and Networks
5. Single-Cell and Spatial Omics
6. Proteomics and Multi-Omics Integration
7. Metabolomics and Microbiome Analysis
8. Drug Response, Survival, and Translational Research
9. Microbiome and Metagenomics Resources
10. R Packages for Data Visualization and Statistical Analysis
11. Tutorials, Workflows, and Additional Bioinformatics Tools
12. Notes on Responsible Use and Citation

---

## 1. Cancer Genomics and Gene-Expression Analysis

| Resource | Description | Website |
|---|---|---|
| Human Protein Atlas | Explores human protein expression across tissues, cells, and organs. | [Open resource](https://www.proteinatlas.org/) |
| cBioPortal | Explores cancer genomics, mutations, copy-number alterations, and clinical data. | [Open resource](https://www.cbioportal.org/) |
| Lung Cancer Explorer (LCE) | Compares gene-expression patterns across lung cancer datasets and patient groups. | [Open resource](https://lce.biohpc.swmed.edu/lungcancer/dataset.php) |
| GEPIA | Analyzes gene expression using TCGA and GTEx data, including tumor-versus-normal comparisons. | [Open resource](http://gepia.cancer-pku.cn/) |
| UCSC Xena | Explores and compares genomic, transcriptomic, and clinical datasets. | [Open resource](https://xenabrowser.net/) |
| GENT2 | Examines gene-expression profiles across normal and tumor tissues. | [Open resource](http://gent2.appex.kr/gent2/) |
| GSCA | Integrates genomic, pharmacogenomic, and immunogenomic analyses for cancer research. | [Open resource](https://guolab.wchscu.cn/GSCA/#/) |
| TCGA Analyzer | Supports analysis of The Cancer Genome Atlas datasets. | [Open resource](http://tcganalyzer.mu.edu.tr/) |
| OncoDB | Explores abnormal gene expression and differentially expressed genes across cancers. | [Open resource](https://oncodb.org/index.html) |
| DriverDBv4 | Investigates cancer driver genes and integrated genomic features. | [Open resource](http://driverdb.bioinfomics.org/cancer/) |
| MammOnc-DB | Supports breast cancer research using RNA-seq, epigenetic, and proteomics data. | [Open resource](https://resource.path.uab.edu/MammOnc-Home.html) |
| CancerSCEM 2.0 | Provides single-cell expression maps across human cancer types. | [Open resource](https://ngdc.cncb.ac.cn/cancerscem/index) |
| CancerSEA | Characterizes functional states of cancer cells using single-cell expression data. | [Open resource](http://biocc.hrbmu.edu.cn/CancerSEA) |
| Cancer Genetics Web | Directory of cancer genetics information and research resources. | [Open resource](https://www.cancer-genetics.org/) |

## 2. Tumor Immunology and Immunotherapy

| Resource | Description | Website |
|---|---|---|
| TIMER | Analyzes tumor-infiltrating immune cells and their associations with genomic and clinical features. | [Open resource](http://timer.cistrome.org/) |
| TIDE | Studies T-cell dysfunction, immune exclusion, and potential immunotherapy resistance using gene-expression signatures. | [Open resource](http://tide.dfci.harvard.edu/query/) |
| xCell | Estimates relative enrichment of cell types from gene-expression profiles. | [Open resource](https://comphealth.ucsf.edu/app/xcell) |
| xCellView | Visualizes xCell results using heatmap-oriented displays. | [Open resource](https://comphealth.ucsf.edu/app/xcellview/) |
| TIMEDB | Explores tumor immune microenvironment composition estimated from bulk gene-expression data. | [Open resource](https://timedb.deepomics.org/) |
| ImmuCellAI | Estimates immune-cell abundance; verify the appropriate species and analysis mode. | [Open resource](https://guolab.wchscu.cn/ImmuCellAI-mouse/#!/analysis) |
| TISIDB | Explores interactions between tumors and the immune system using heterogeneous datasets. | [Open resource](http://cis.hku.hk/TISIDB/index.php) |
| ImmunoCheckDB | Supports evaluation of cancer immunotherapy interventions using meta-analysis and multi-omics profiling. | [Open resource](https://smuonco.shinyapps.io/ImmunoCheckDB/) |
| Immune Escape Map | Explores cancer immune-escape mechanisms and related genes. | [Open resource](https://ccsm.uth.edu/IEscapeMap/gene_search_result.cgi?page=page&type=quick_search&quick_search=3458) |
| ROCplot | Investigates biomarker associations with treatment response, including immunotherapy-related analyses. | [Open resource](https://rocplot.com/immune) |
| OStme | Supports consensus survival analysis of tumor microenvironment components across cancer datasets. | [Open resource](https://bioinfo.henu.edu.cn/Immune/Immune.html) |
| PCIG | Applies immunogenomics to investigate immune-response characteristics in cancer. | [Open resource](https://pcig.vhio.net/) |
| ImmGen / MyGeneSet | Provides immune-cell gene-expression resources and gene-set exploration tools. | [Open resource](https://rstats.immgen.org/MyGeneSet_New/index.html) |
| CellMarker 2.0 | Provides reference markers for cell-type identification across tissues and cell populations. | [Open resource](http://bio-bigdata.hrbmu.edu.cn/CellMarker/CellMarker_download.html) |
| TISCH | Explores single-cell transcriptomic profiles of the tumor microenvironment. | [Open resource](http://tisch.comp-genomics.org/) |

## 3. RNA-seq and Differential Expression Analysis

### Web applications and workflows

| Resource | Description | Website |
|---|---|---|
| RNAseqEasy | User-friendly RNA-seq analysis application integrating differential expression, GO enrichment, co-expression analysis, and visualization. | [Launch application](https://salvillas.github.io/RNAseqEasy/) |
| RNAseqEasy source code | Source code and development resources for RNAseqEasy. | [GitHub repository](https://github.com/salvillas/RNAseqEasy) |
| NASQAR2 | Shiny interface for interactive differential expression analysis using DESeq2. | [Open application](http://nasqar2.abudhabi.nyu.edu/deseq2shiny/) |
| Bioconductor RNA-seq Workflow | Covers exploratory analysis and differential expression analysis. | [Workflow](https://www.bioconductor.org/packages/devel/workflows/vignettes/rnaseqGene/inst/doc/rnaseqGene.html) |
| RNA-seq Analysis in R — Shulin Cao | Practical tutorial covering an RNA-seq analysis workflow in R. | [Tutorial](https://rstudio-pubs-static.s3.amazonaws.com/462299_a9bc385f89b94b0aa95de0f3b7040b04.html) |
| Bulk RNA-Seq Codex — Multiome Academy | Tutorial series covering experimental design, differential expression, pathway analysis, and cell-type deconvolution. | [Search for resource](https://www.google.com/search?q=The+Bulk+RNA-Seq+Codex+Multiome+Academy) |
| LINCS Tools | Tools for exploring and analyzing LINCS datasets. | [Open resource](https://lincsproject.org/LINCS/tools) |

### R packages

| Package | Description | Website |
|---|---|---|
| DESeq2 | Differential expression analysis of sequencing count data. | [Bioconductor](https://bioconductor.org/packages/DESeq2/) |
| edgeR | Statistical analysis of differential gene expression using count data. | [Bioconductor](https://bioconductor.org/packages/edgeR/) |
| PQLseq | Differential analysis of RNA-seq and bisulfite sequencing data accounting for relatedness and population structure. | [CRAN](https://cran.r-project.org/web/packages/PQLseq/index.html) |
| PCAtools | Principal component analysis, visualization, and interpretation. | [Documentation](https://bioconductor.org/packages/devel/bioc/vignettes/PCAtools/inst/doc/PCAtools.html) |
| CMplot | Visualization of genome-wide association results, including Manhattan plots. | [GitHub](https://github.com/YinLiLin/CMplot) |

## 4. Gene Sets, Pathways, Enrichment, and Networks

| Resource | Description | Website |
|---|---|---|
| InteractiVenn | Interactive comparison of multiple gene or feature lists using Venn diagrams. | [Open resource](https://www.interactivenn.net/) |
| GenesetDB | Meta-database of gene sets and gene-set enrichment resources. | [Open resource](https://genesetdb.auckland.ac.nz/about.html) |
| Bader Lab Gene Sets | Gene-set collections for enrichment and pathway analysis. | [Download gene sets](https://download.baderlab.org/EM_Genesets/current_release/) |
| SimplifyEnrichment | R/Bioconductor package for clustering and visualizing related functional-enrichment terms. | [Documentation](https://www.bioconductor.org/packages/devel/bioc/vignettes/simplifyEnrichment/inst/doc/simplifyEnrichment.html) |
| InnateDB Gene Lists | Gene lists related to Gene Ontology processes, immune systems, and innate immunity. | [Open resource](https://www.innatedb.com/redirect.do?go=resourcesGeneLists) |
| ConsensusPathDB | Integrates molecular interaction networks and pathways across multiple biological domains. | [Open resource](http://cpdb.molgen.mpg.de/MCPDB) |
| Enrichment Analysis Scripts | Scripts for pathway and Gene Ontology enrichment analysis. | [GitHub](https://github.com/hamidghaedi/Enrichment-Analysis) |
| MultiSLIDE | Query-driven visualization of quantitative single- and multi-omics data using pathways and networks. | [GitHub](https://github.com/soumitag/multiSLIDE) |
| HumanBase | Predicts tissue-specific gene expression, function, regulation, and molecular interactions. | [Open resource](https://hb.flatironinstitute.org/) |
| Biomedical Knowledge Mining Toolkit | Workflow-oriented guidance for identifier mapping, enrichment analysis, knowledge integration, visualization, and biological interpretation. | [Online book](https://yulab-smu.top/biomedical-knowledge-mining-book/) |
| APPIC | Atlas of Protein–Protein Interactions in Cancer; visualizes and analyzes interactions across cancer subtypes. | [Open application](https://appic.brown.edu/) |

A typical functional interpretation workflow is:

**Experimental data → Identifier mapping → Enrichment analysis → Knowledge-source exploration → Evidence integration → Visualization → Biological interpretation**

## 5. Single-Cell and Spatial Omics

| Resource | Description | Website |
|---|---|---|
| ICARUS v3 | Interactive environment for single-cell data analysis. | [Open application](https://launch.icarus-scrnaseq.cloud.edu.au/app/ICARUS_v3) |
| Single Cell Toolkit (SCTK) | Supports single-cell RNA-seq quality control, normalization, integration, clustering, annotation, pathway analysis, and export. | [Open application](https://sctk.bu.edu/app/SingleCellTK) |
| STellaris | Web server for spatial mapping of single-cell omics data. | [Example gene search](https://spatial.rhesusbase.com/search/results?idType=Symbol&species=Human&geneName=HSP90AA1) |
| Single-cell RNA-seq Analysis Tutorial | Practical guidance for analyzing single-cell RNA-seq data in R. | [GitHub tutorial](https://github.com/quadbio/scRNAseq_analysis_vignette/blob/master/Tutorial.md) |
| TACCO | Computational toolkit connecting transcriptome and pathway alterations with clinical outcomes in cancer. | [Open resource](https://tacco.life.nctu.edu.tw/) |

## 6. Proteomics and Multi-Omics Integration

| Resource | Description | Website |
|---|---|---|
| FragPipe-Analyst | Web-based analysis and visualization for proteomics datasets, especially FragPipe workflows. | [Open resource](https://fragpipe-analyst.org/) |
| Multiomics2Targets | Integrates multi-omics analysis, pathway enrichment, kinase enrichment, target prioritization, and signaling reconstruction. | [Open resource](https://multiomics2targets.maayanlab.cloud/) |
| Pan-cancer Proteogenomics / Druggable Target Analysis | Integrates CPTAC proteomics and public datasets to investigate drug targets, protein dependencies, and candidate antigens. | [Open resource](https://targets.linkedomics.org/) |
| NCI Proteomics Resources | Directory of proteomics tools and databases from the Office of Cancer Clinical Proteomics Research. | [Open resource](https://proteomics.cancer.gov/) |
| UALCAN Proteomics | Explores protein-expression data and cancer-related proteomics analyses. | [Open resource](https://ualcan.path.uab.edu/analysis-prot.html) |
| RforProteomics | Introduction to proteomics data analysis using R and Bioconductor. | [Workflow](https://bioconductor.org/packages/release/data/experiment/vignettes/RforProteomics/inst/doc/RforProteomics.html) |
| RforProteomics Visualization | Publication on proteomics data visualization using R and Bioconductor. | [Article](https://onlinelibrary.wiley.com/doi/full/10.1002/pmic.201400392) |
| Bioconductor Proteomics Workflow | Resources for mass spectrometry and proteomics analysis. | [Workflow](http://master.bioconductor.org/packages/release/workflows/vignettes/proteomics/inst/doc/proteomics.html) |
| Bacterial Proteomics in R | Tutorial for analyzing microbial proteomics data in R. | [Tutorial](https://microsud.github.io/Bacterial-Proteomics-in-R/tutorial_main_doc.html) |
| mixDIABLO | Multi-omics integration and biomarker discovery using latent-variable methods. | [Open resource](http://mixomics.org/mixdiablo/) |
| timeOmics | Integration and analysis of longitudinal multi-omics data. | [Publication](https://doi.org/10.1093/bioinformatics/btab664) |

## 7. Metabolomics Resources

| Resource | Description | Website |
|---|---|---|
| MetaboAnalyst | Metabolomics data processing, statistical analysis, visualization, and biological interpretation. | [Open resource](https://www.metaboanalyst.ca/MetaboAnalyst/ModuleView.xhtml) |
| MBROLE 2.0 | Maps metabolites to biological roles and pathway annotations. | [Open resource](https://csbg.cnb.csic.es/mbrole2/result.php) |
| PathBank | Pathway resource for metabolite and pathway interpretation. | [Open resource](https://pathbank.org/) |
| Mediator | Supports metabolite annotation and metabolomics-related information searches. | [Open resource](https://ceumass.eps.uspceu.es/mediator/browse_search.xhtml) |
| Metabolomics Centre | Directory of metabolomics software and databases. | [Open directory](https://metabolomicscentre.ca/software-databases/software-data-analysis/) |
| MIMOSA2 | Integrates microbial metabolic networks with microbiome–metabolome data. | [Publication](https://doi.org/10.1093/bioinformatics/btac003) |

## 8. Drug Response, Survival, and Translational Research

| Resource | Description | Website |
|---|---|---|
| CPADS | Comprehensive pan-cancer drug-sensitivity analysis resource. | [Open application](https://smuonco.shinyapps.io/CPADS/) |
| SensitivitySeq | Resource focused on drug-sensitivity prediction. | [Open resource](http://sensitivityseq.com/) |
| Survival Genie 2.0 | Survival analysis and visualization across datasets and analysis groups. | [Open application](https://bhasinlab.bmi.emory.edu/SurvivalGenie2/home) |
| shinyDeepDR | Deep-learning approach for predicting cancer drug response from mutation and gene-expression data. | [Open application](https://shiny.crc.pitt.edu/shinydeepdr/) |
| HCDT Drug-Target Files | Downloadable drug-target data files. | [Open resource](http://hainmu-biobigdata.com/hcdt2/download.php) |

## 9. Microbiome and Metagenomics Resources

### 9.1 Web servers and interactive applications

| Resource | Description | Website |
|---|---|---|
| GutMeta | Human gut whole-genome shotgun metagenomics profiling, analysis, and visualization. | [Open resource](https://gutmeta.deepomics.org/) |
| Nephele | Web-based microbiome analysis platform. | [Open platform](https://nephele.niaid.nih.gov/index) |
| animalcules | Interactive Shiny application for microbiome analysis. | [Documentation](https://compbiomed.github.io/animalcules-docs/) |
| Biome-Shiny | Graphical interface for microbiome visualization using the microbiome R ecosystem. | [GitHub](https://github.com/Biodata-PT/Biome-Shiny) |
| ShinyPhyloseq | Web interface for exploring phyloseq datasets. | [Open application](http://joey711.github.io/shiny-phyloseq/) |
| EasyMicroPlot | Microbiome downstream analysis and visualization for clinical studies. | [Publication](https://doi.org/10.3389/fgene.2021.803627) |
| EzMAP | Easy Microbiome Analysis Platform. | [Publication](https://doi.org/10.1186/s12859-021-04106-7) |
| Explore Metabar | Interactive application for exploring metabarcoding and microbiome data. | [Open application](https://shiny.migale.inrae.fr/app/exploremetabar) |
| Bioinformagic | Directory of interactive bioinformatics tools. | [Open directory](https://bioinformagic.io/tools) |

### 9.2 Processing and quality control

| Package or tool | Description | Website |
|---|---|---|
| DADA2 | Amplicon sequence processing, error correction, and exact sequence variant inference. | [Documentation](https://benjjneb.github.io/dada2/) |
| decontam | Identifies and removes contaminants from marker-gene and metagenomic data. | [GitHub](https://github.com/benjjneb/decontam) |
| DECIPHER | Tools for biological sequence analysis and classification in R. | [Website](http://www2.decipher.codes/index.html) |
| qiime2R | Imports QIIME 2 artifacts and associated data into R. | [GitHub](https://github.com/jbisanz/qiime2R) |
| qiimer | R tools complementing QIIME workflows. | [GitHub](https://github.com/kylebittinger/qiimer) |
| metabaRpipe | Workflow for processing 16S amplicon sequencing data. | [GitHub](https://github.com/fconstancias/metabaRpipe) |
| microDecon | Removes contamination from metabarcoding datasets. | [GitHub](https://github.com/donaldtmcknight/microDecon) |
| AMR | R package for working with antimicrobial resistance data. | [Documentation](https://msberends.github.io/AMR/) |

### 9.3 Differential abundance and statistical analysis

| Method or package | Description | Website |
|---|---|---|
| ANCOM-BC | Differential abundance analysis for compositional microbiome data. | [GitHub](https://github.com/FrederickHuangLin/ANCOMBC) |
| ALDEx2 | Differential abundance analysis accounting for sampling variation and compositionality. | [Bioconductor](https://bioconductor.org/packages/ALDEx2/) |
| adaANCOM | Phylogeny-informed differential abundance analysis. | [Publication](https://doi.org/10.1093/bioinformatics/btab543) |
| benchdamic | Benchmarking differential abundance methods for microbiome studies. | [Bioconductor](https://bioconductor.org/packages/benchdamic/) |
| corncob | Models microbial abundance and dysbiosis using beta-binomial regression. | [GitHub](https://github.com/bryandmartin/corncob) |
| dacomp | Differential abundance testing for compositional count data. | [GitHub](https://github.com/barakbri/dacomp) |
| LinDA | Log-ratio regression for differential abundance analysis. | [GitHub](https://github.com/zhouhj1994/LinDA) |
| LOCOM | Logistic regression method for differential abundance in compositional microbiome data. | [Publication](https://doi.org/10.1073/pnas.2122788119) |
| MaAsLin2 | Multivariable association analysis using linear models. | [GitHub](https://github.com/biobakery/Maaslin2) |
| metagenomeSeq | Statistical methods for differential abundance analysis of microbial marker-gene surveys. | [Publication](http://www.nature.com/nmeth/journal/v10/n12/full/nmeth.2658.html) |
| MicrobiomeStat | Statistical methods for microbiome compositional data. | [CRAN](https://cran.r-project.org/web/packages/MicrobiomeStat/index.html) |
| SIAMCAT | Statistical inference and machine learning for microbial-community associations with host phenotypes. | [Bioconductor](https://bioconductor.org/packages/SIAMCAT/) |
| ZIBBSeqDiscovery | Zero-inflated beta-binomial modelling for microbiome data. | [Publication](https://onlinelibrary.wiley.com/doi/abs/10.1002/sta4.185) |

### 9.4 Microbial diversity, ecology, and visualization

| Package or method | Description | Website |
|---|---|---|
| ampvis2 | Visualization of amplicon sequencing data. | [Documentation](https://madsalbertsen.github.io/ampvis2/) |
| phyloseq | Microbiome data import, management, analysis, and visualization. | [Website](https://joey711.github.io/phyloseq/) |
| vegan | Community ecology, ordination, and diversity analysis in R. | [GitHub](https://github.com/vegandevs/vegan) |
| microViz | Microbiome data analysis and visualization. | [Documentation](https://david-barnett.github.io/microViz/) |
| MicrobiotaProcess | Microbiome analysis, visualization, and biomarker discovery. | [GitHub](https://github.com/YuLab-SMU/MicrobiotaProcess) |
| MicrobiomeExplorer | Analysis and visualization of microbial communities. | [Publication](https://doi.org/10.1093/bioinformatics/btaa838) |
| Metacoder | Manipulation and visualization of taxonomic diversity data. | [Publication](https://doi.org/10.1371/journal.pcbi.1005404) |
| microshades | Improves color accessibility and organization in microbiome visualizations. | [Publication](https://doi.org/10.1128/mra.00795-22) |
| labdsv | Ordination and multivariate ecological analysis. | [CRAN documentation](https://cran.r-project.org/web/packages/labdsv/labdsv.pdf) |
| DivNet | Estimates diversity while accounting for ecological associations among taxa. | [GitHub](https://github.com/adw96/DivNet) |
| Adaptive gPCA | Structured dimensionality reduction. | [Publication](https://arxiv.org/abs/1702.00501) |

### 9.5 Microbial networks and associations

| Method or package | Description | Website |
|---|---|---|
| NetCoMi | Constructs and compares microbiome association networks in R. | [GitHub](https://github.com/stefpeschel/NetCoMi) |
| SPIEC-EASI | Infers sparse microbial ecological networks while addressing compositionality. | [Publication](https://doi.org/10.1371/journal.pcbi.1004226) |
| igraph | Network analysis and visualization in R. | [Website](https://igraph.org/r/) |
| C3NA | Cross-taxonomy network analysis for compositional microbial data. | [Publication](https://doi.org/10.1186/s12859-022-05027-9) |
| mina | Microbial community diversity and network analysis. | [GitHub](https://github.com/Guan06/mina) |
| MDiNE | Estimates differential co-occurrence networks in microbiome studies. | [Publication](https://doi.org/10.1093/bioinformatics/btz824) |
| BEEM | Estimates Lotka–Volterra models from time-course microbiome sequencing data. | [GitHub](https://github.com/lch14forever/BEEM) |

### 9.6 Functional profiling and multi-omics integration

| Method or package | Description | Website |
|---|---|---|
| ggpicrust2 | Pathway annotation, differential analysis, and visualization of PICRUSt2-derived functional profiles. | [GitHub](https://github.com/cafferychen777/ggpicrust2) |
| Tax4Fun | Predicts functional profiles from 16S rRNA gene data. | [Publication](https://pubmed.ncbi.nlm.nih.gov/25957349/) |
| Tax4Fun2 | Predicts habitat-specific functional profiles from 16S rRNA gene sequences. | [Publication](https://doi.org/10.1186/s40793-020-00358-7) |
| MicrobiomeProfiler | Microbiome functional enrichment analysis in R and Shiny. | [GitHub](https://github.com/YuLab-SMU/MicrobiomeProfiler) |
| FuncDiv | Contributional diversity analysis of joint taxonomic and functional data. | [GitHub](https://github.com/gavinmdouglas/FuncDiv) |

### 9.7 Longitudinal and time-series microbiome analysis

| Method or package | Description | Website |
|---|---|---|
| MetaLonDA | Detects differential abundance across longitudinal studies. | [GitHub](https://github.com/aametwally/MetaLonDA) |
| SplinectomeR | Supports group comparisons in longitudinal microbiome studies. | [Publication](https://doi.org/10.3389/fmicb.2018.00785) |
| MTA | Microbial trend analysis for longitudinal group comparisons and classification. | [GitHub](https://github.com/chanw0/MTA) |
| OmicsLonDA | Identifies temporal biomarkers in longitudinal omics data. | [Publication](https://doi.org/10.1093/bioinformatics/btac403) |
| bootLong | Block bootstrap methods for longitudinal microbiome data. | [Website](https://pratheepaj.github.io/bootLong/) |
| BiomeHorizon | Visualization of microbiome time-series data. | [Publication](https://doi.org/10.1128/msystems.01380-21) |
| tidyMicro | Microbiome analysis and visualization using tidyverse principles. | [Publication](https://doi.org/10.1186/s12859-021-03967-2) |

### 9.8 Microbiome reference databases and datasets

| Resource | Description | Website |
|---|---|---|
| HMP16SData | Human Microbiome Project 16S datasets distributed through Bioconductor. | [Bioconductor](https://bioconductor.org/packages/release/data/experiment/html/HMP16SData.html) |
| HMP2Data | Human Microbiome Project 2 datasets. | [Bioconductor](https://bioconductor.org/packages/release/data/experiment/html/HMP2Data.html) |
| microbiomeDataSets | Microbiome datasets distributed through ExperimentHub. | [Bioconductor](https://bioconductor.org/packages/devel/data/experiment/html/microbiomeDataSets.html) |
| curatedMetagenomicData | Curated human metagenomic datasets accessible through ExperimentHub. | [Website](https://waldronlab.io/curatedMetagenomicData/) |
| MicrobiomeHD | Collection of human gut microbiome studies in health and disease. | [Preprint](http://www.biorxiv.org/content/early/2017/05/08/134031) |

## 10. R Packages for Data Visualization and Statistical Analysis

| Package | Description | Website |
|---|---|---|
| ggplot2 | Grammar of Graphics implementation for data visualization in R. | [Website](https://ggplot2.tidyverse.org/) |
| ggvegan | ggplot-based versions of plots produced by vegan. | [GitHub](https://github.com/gavinsimpson/ggvegan) |
| ggord | Creates ordination plots using ggplot2. | [Website](https://fawda123.github.io/ggord/) |
| cowplot | Combines plots and adds annotations to ggplot2 figures. | [Website](https://wilkelab.org/cowplot/) |
| ggridges | Creates ridgeline plots for comparing distributions. | [Website](https://wilkelab.org/ggridges/) |
| ggtext | Enhanced text rendering and plot annotations. | [Website](https://wilkelab.org/ggtext/) |
| ggpubr | Simplifies the creation of publication-ready statistical plots. | [Tutorials](http://www.sthda.com/english/articles/24-ggpubr-publication-ready-plots/) |
| ggraph | Network and graph visualization using a grammar-of-graphics approach. | [Website](https://ggraph.data-imaginist.com/) |
| gganimate | Animates ggplot2 visualizations, including time-series dynamics. | [Website](https://gganimate.com/) |
| ggforce | Extends ggplot2 with additional geometries and zoomed-in plot regions. | [Website](https://ggforce.data-imaginist.com/) |
| factoextra | Extracts and visualizes multivariate analysis results. | [Website](https://rpkgs.datanovia.com/factoextra/index.html) |
| ggcorrplot | Visualizes correlation matrices using ggplot2. | [Website](https://rpkgs.datanovia.com/ggcorrplot/) |
| tidyverse | Collection of R packages for data manipulation, analysis, and visualization. | [Website](https://www.tidyverse.org/) |
| ggplot2 Extensions Gallery | Directory of extensions for ggplot2. | [Gallery](https://exts.ggplot2.tidyverse.org/gallery/) |
| ggtree | Visualizes and annotates phylogenetic trees. | [GitHub](https://github.com/YuLab-SMU/ggtree) |
| patchwork | Combines multiple ggplot2 plots into a single layout. | [Website](https://patchwork.data-imaginist.com/) |
| pheatmap | Generates heatmaps with clustering and annotation support. | [CRAN documentation](https://cran.r-project.org/web/packages/pheatmap/pheatmap.pdf) |
| gggenes | Draws gene maps and gene-cluster diagrams. | [Website](https://wilkox.org/gggenes/) |
| gggenomes | Comparative genomics visualization. | [Website](https://thackl.github.io/gggenomes/) |
| TreeHeatmap | Visualizes heatmaps alongside hierarchical tree structures. | [GitHub](https://github.com/fionarhuang/TreeHeatmap) |
| fastverse | Collection of high-performance packages for statistical computing and data manipulation. | [Website](https://sebkrantz.github.io/fastverse/) |
| DataExplorer | Automated exploratory data analysis for analytics and predictive modelling. | [Website](https://boxuancui.github.io/DataExplorer/) |

## 11. Additional Bioinformatics Tools and Directories

| Resource | Description | Website |
|---|---|---|
| WANG LAB | GitHub organization containing genomic analysis pipelines and related resources. | [GitHub organization](https://github.com/wang-lab) |
| Bioinformagic | Searchable directory of interactive bioinformatics tools, including filtering by research domain and analysis type. | [Open directory](https://bioinformagic.io/tools) |

## 12. Notes on Responsible Use and Citation

- **Citation and attribution:** If you use, reproduce, or adapt scripts, code, packages, methods, or workflows listed here, please cite the original developers and authors and acknowledge their contributions. Follow the relevant publication, repository, and software citation guidelines.
- **Verify official documentation:** Check each resource's documentation for supported input formats, statistical assumptions, software requirements, and recommended workflows.
- **Record versions and access dates:** For reproducible research, document software versions, database releases, access dates, and analysis settings.
- **Validate results independently:** Treat computational predictions and enrichment results as evidence that may require independent statistical or experimental validation.
- **Check licensing and data policies:** Confirm whether each resource permits redistribution, commercial use, or use with sensitive clinical data.
- **Protect sensitive data:** Do not upload identifiable or restricted data unless the platform's privacy, security, and data-governance policies explicitly permit it.
- **Check maintenance status:** Websites, APIs, software dependencies, and application availability can change over time.

---

*This page is a curated starting point for bioinformatics and multi-omics research, not an endorsement of every listed resource. Descriptions are concise guides; consult the official websites and original publications for authoritative information.*

*Please acknowledge the original developers and authors when using their tools, scripts, datasets, and methods.*
