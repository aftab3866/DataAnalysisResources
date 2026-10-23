## Bioinformatics & Multi-Omics Resources
![Bioinformatics & Multi-Omics Resources](DatanalRs/data.png)

---
title: "Bioinformatics and Multi-Omics Analysis Resources"
author: "Aftab Alam"
date: "`r format(Sys.Date(), '%B %Y')`"
output:
  html_document:
    toc: true
    toc_depth: 2
    toc_float: true
    theme: cosmo
    df_print: paged
---

<style>
.resource-intro {
  padding: 1rem 1.2rem;
  margin: 1rem 0 1.5rem;
  border-left: 4px solid #2b7a78;
  background: #f4f8f8;
  border-radius: 4px;
}
.resource-table { width: 100%; }
.resource-table th { background: #edf3f5; }
.resource-table td, .resource-table th { padding: 8px; vertical-align: top; }
.resource-note { color: #555; font-size: 0.92em; }
</style>

<div class="resource-intro">
This curated directory brings together web platforms, databases, R packages, and interactive applications for bioinformatics, cancer genomics, transcriptomics, immuno-oncology, single-cell analysis, proteomics, metabolomics, pathway analysis, and microbiome research.

Resources are grouped by their main use to make them easier to find. Availability, supported data formats, and features may change; please consult each resource's official documentation before using it in a research workflow.
</div>

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE, message = FALSE, warning = FALSE)
resources <- data.frame(
  Category = character(),
  Resource = character(),
  Description = character(),
  Website = character(),
  stringsAsFactors = FALSE
)
add_resource <- function(category, resource, description, url) {
  data.frame(Category = category, Resource = resource,
             Description = description, Website = url,
             stringsAsFactors = FALSE)
}
```

## Cancer genomics and gene-expression analysis

| Resource | Description | Website |
|---|---|---|
| Human Protein Atlas | Swedish-based resource mapping human proteins across cells, tissues, and organs using antibody-based and omics technologies. | [Open resource](https://www.proteinatlas.org/) |
| cBioPortal for Cancer Genomics | Explore, visualize, analyze, and download large-scale cancer genomics datasets, including molecular and clinical data. | [Open resource](https://www.cbioportal.org/) |
| Lung Cancer Explorer (LCE) | Explore and compare gene-expression patterns across lung cancer datasets, patient groups, and tissue types. | [Open resource](https://lce.biohpc.swmed.edu/lungcancer/dataset.php) |
| GEPIA | Interactive gene-expression analysis using data from TCGA and GTEx, including tumor-versus-normal comparisons. | [Open resource](http://gepia.cancer-pku.cn/) |
| UCSC Xena / Xena Browser | Explore and compare functional-genomics and phenotype datasets, including gene expression, mutations, copy-number alterations, and clinical variables. | [Open resource](https://xenabrowser.net/) |
| GENT2 | Explore gene-expression profiles across normal and tumor tissues. | [Open resource](http://gent2.appex.kr/gent2/) |
| GSCA — Gene Set Cancer Analysis | Integrated platform for gene-set analysis in cancer, bringing together genomic, pharmacogenomic, and immunogenomic data. | [Open resource](https://guolab.wchscu.cn/GSCA/#/) |
| TCGA Analyzer | Web resource for analysis of The Cancer Genome Atlas (TCGA) data. Check the site for current functionality and availability. | [Open resource](http://tcganalyzer.mu.edu.tr/) |
| OncoDB | Online resource for exploring abnormal gene-expression patterns and differentially expressed genes across cancers. | [Open resource](https://oncodb.org/index.html) |
| DriverDBv4 | Resource for investigating human cancer driver genes and performing multivariate analyses. | [Open resource](http://driverdb.bioinfomics.org/cancer/) |
| MammOnc-DB | Breast-cancer research platform for exploring RNA-seq, epigenetic, and mass-spectrometry proteomics data, with a focus on treatment and metastasis. | [Open resource](https://resource.path.uab.edu/MammOnc-Home.html) |
| CancerSCEM 2.0 | Database of single-cell expression maps across multiple human cancer types. | [Open resource](https://ngdc.cncb.ac.cn/cancerscem/index) |
| CancerSEA | Resource describing functional states of cancer cells using single-cell expression data across tumor types. | [Open resource](http://biocc.hrbmu.edu.cn/CancerSEA) |
| TISCH | Tumor Immune Single-cell Hub for exploring single-cell transcriptomic profiles of the tumor microenvironment. | [Open resource](http://tisch.comp-genomics.org/) |
| Cancer Genetics Web | Directory of cancer genetics information and related resources for health professionals and researchers. | [Open resource](https://www.cancer-genetics.org/) |

## Tumor immunology and immunotherapy

| Resource | Description | Website |
|---|---|---|
| TIMER | Analyze tumor-infiltrating immune cells across cancer types and explore associations with genomic, clinical, and tumor features. | [Open resource](http://timer.cistrome.org/) |
| TIDE | Uses gene-expression signatures to study T-cell dysfunction, immune exclusion, and potential resistance to cancer immunotherapy. | [Open resource](http://tide.dfci.harvard.edu/query/) |
| xCell | Estimates relative enrichment of cell types from gene-expression profiles. | [Open resource](https://comphealth.ucsf.edu/app/xcell) |
| xCell Heatmap / xCellView | Heatmap-oriented visualization for xCell results. | [Open resource](https://comphealth.ucsf.edu/app/xcellview/) |
| TIMEDB | Database of tumor immune microenvironment cell-type composition estimated from bulk gene-expression profiles, with analysis and visualization features. | [Open resource](https://timedb.deepomics.org/) |
| ImmuCellAI-mouse / Human | Estimates immune-cell abundance and supports comparisons between sample groups using statistical tests. Confirm the species and analysis mode on the website. | [Open resource](https://guolab.wchscu.cn/ImmuCellAI-mouse/#!/analysis) |
| TISIDB | Portal integrating heterogeneous data to explore interactions between tumors and the immune system. | [Open resource](http://cis.hku.hk/TISIDB/index.php) |
| ImmunoCheckDB | Resource for evaluating cancer immunotherapy interventions using meta-analysis and multi-omics profiling. | [Open resource](https://smuonco.shinyapps.io/ImmunoCheckDB/) |
| Immune Escape Map | Knowledgebase for exploring cancer immune-escape mechanisms and related genes. | [Open resource](https://ccsm.uth.edu/IEscapeMap/gene_search_result.cgi?page=page&type=quick_search&quick_search=3458) |
| ROCplot | Resource for exploring biomarker associations with treatment response, including immunotherapy-related analyses. | [Open resource](https://rocplot.com/immune) |
| OStme | Online consensus survival-analysis resource for tumor microenvironment components across pan-cancer datasets. | [Open resource](https://bioinfo.henu.edu.cn/Immune/Immune.html) |
| PCIG | Platform using immunogenomics to investigate characteristics of the immune response in cancer. | [Open resource](https://pcig.vhio.net/) |
| ImmGen / MyGeneSet | ImmGen provides immune-cell gene-expression resources; MyGeneSet supports exploration and analysis of submitted gene sets. | [ImmGen MyGeneSet](https://rstats.immgen.org/MyGeneSet_New/index.html) |
| CellMarker 2.0 | Reference resource for cell-type markers across tissues and cell populations. | [Open resource](http://bio-bigdata.hrbmu.edu.cn/CellMarker/CellMarker_download.html) |

## Differential expression, gene sets, pathways, and networks

| Resource | Description | Website |
|---|---|---|
| InteractiVenn | Compare multiple gene or feature lists using interactive Venn diagrams. | [Open resource](https://www.interactivenn.net/) |
| GenesetDB | Meta-database of gene sets and related gene-set enrichment analysis resources. | [Open resource](https://genesetdb.auckland.ac.nz/about.html) |
| Gene set files — Bader Lab | Download regularly updated gene-set collections for enrichment and pathway analysis. Check release dates and identifiers before analysis. | [Open resource](https://download.baderlab.org/EM_Genesets/current_release/) |
| SimplifyEnrichment | R/Bioconductor package for clustering and visualizing related functional-enrichment terms using similarity-based methods. | [Documentation](https://www.bioconductor.org/packages/devel/bioc/vignettes/simplifyEnrichment/inst/doc/simplifyEnrichment.html) |
| Gene Ontology / InnateDB gene lists | Access gene lists related to Gene Ontology biological processes, including immune-system and innate-immunity topics. | [Open resource](https://www.innatedb.com/redirect.do?go=resourcesGeneLists) |
| ConsensusPathDB | Integrates molecular interaction networks and pathways, including protein, genetic, metabolic, signaling, regulatory, and drug-target interactions. | [Open resource](http://cpdb.molgen.mpg.de/MCPDB) |
| Pathway and GO enrichment scripts | GitHub repository containing scripts for pathway and Gene Ontology enrichment analysis. | [GitHub repository](https://github.com/hamidghaedi/Enrichment-Analysis) |
| MultiSLIDE | Open-source, query-driven visualization of quantitative single- and multi-omics data using pathways and networks to connect genes, pathways, and molecular interactions. | [GitHub repository](https://github.com/soumitag/multiSLIDE) |
| HumanBase | Data-driven predictions of tissue-specific gene expression, function, regulation, and molecular interactions. | [Open resource](https://hb.flatironinstitute.org/) |
| MyGeneSet | Web interface for exploring immune-cell gene-expression data and related gene-set analyses. | [Open resource](https://rstats.immgen.org/MyGeneSet_New/index.html) |
| PCAtools | R/Bioconductor package and documentation for principal component analysis, visualization, and interpretation. | [Documentation](https://bioconductor.org/packages/devel/bioc/vignettes/PCAtools/inst/doc/PCAtools.html) |

## Single-cell and spatial omics

| Resource | Description | Website |
|---|---|---|
| ICARUS v3 | Interactive environment for single-cell data analysis; review the application documentation for supported input formats and workflows. | [Open app](https://launch.icarus-scrnaseq.cloud.edu.au/app/ICARUS_v3) |
| Single Cell Toolkit (SCTK) | Toolkit and Shiny interface for single-cell RNA-seq import, quality control, doublet detection, normalization, integration, dimensionality reduction, clustering, marker analysis, cell annotation, pathway analysis, and export. | [Open app](https://sctk.bu.edu/app/SingleCellTK) |
| STellaris | Web server for spatial mapping of single-cell omics data using spatial transcriptomics datasets. | [Gene search example](https://spatial.rhesusbase.com/search/results?idType=Symbol&species=Human&geneName=HSP90AA1) |
| TACCO | Computational toolkit for connecting transcriptome and pathway alterations with clinical outcomes in cancer. | [Open resource](https://tacco.life.nctu.edu.tw/) |

## RNA-seq and interactive analysis applications

| Resource | Description | Website |
|---|---|---|
| NASQAR2 | Shiny interface around DESeq2 for interactive differential gene-expression analysis of RNA-seq count data, including visualization and exploration. | [Open app](http://nasqar2.abudhabi.nyu.edu/deseq2shiny/) |
| WANG LAB | GitHub organization with genomic analysis pipelines and related resources. Explore the repositories for details on each workflow. | [GitHub organization](https://github.com/wang-lab) |
| Bioinformagic tools | Directory of interactive bioinformatics tools with filtering by scientific domain, analysis type, and input data type. | [Open directory](https://bioinformagic.io/tools) |

## Proteomics and multi-omics integration

| Resource | Description | Website |
|---|---|---|
| FragPipe-Analyst | Web-based analysis and visualization resource for proteomics datasets, especially workflows associated with FragPipe. | [Open resource](https://fragpipe-analyst.org/) |
| Multiomics2Targets | Integrates multi-omics analysis with pathway enrichment, kinase enrichment, cell-surface protein prioritization, and signaling-pathway reconstruction. | [Open resource](https://multiomics2targets.maayanlab.cloud/) |
| Pan-cancer proteogenomics / Druggable Target Analysis | Integrates CPTAC pan-cancer proteomics with other public data to investigate known and candidate drug targets, protein dependencies, and potential antigens. | [Open resource](https://targets.linkedomics.org/) |
| Proteomics tools — NCI | Directory of proteomics resources from the Office of Cancer Clinical Proteomics Research. | [Open resource](https://proteomics.cancer.gov/) |
| UALCAN Proteomics | Portal for exploring protein-expression data, including cancer-related proteomics analyses. | [Open resource](https://ualcan.path.uab.edu/analysis-prot.html) |
| DriverDBv4 | Also useful for cancer driver-gene research and integrated genomic analysis. | [Open resource](http://driverdb.bioinfomics.org/cancer/) |

## Metabolomics and microbiome analysis

| Resource | Description | Website |
|---|---|---|
| MetaboAnalyst | Web platform for metabolomics data processing, statistical analysis, visualization, and biological interpretation. | [Open resource](https://www.metaboanalyst.ca/MetaboAnalyst/ModuleView.xhtml) |
| MBROLE 2.0 | Maps metabolites to biological roles and KEGG-related pathway annotations. | [Open resource](https://csbg.cnb.csic.es/mbrole2/result.php) |
| PathBank | Pathway resource useful for pathway analysis and metabolite-pathway interpretation. | [Open resource](https://pathbank.org/) |
| Mediator | Resource for metabolite annotation and searching metabolomics-related information. | [Open resource](https://ceumass.eps.uspceu.es/mediator/browse_search.xhtml) |
| Metabolomics Centre — software and databases | Directory of software and databases for metabolomics research and data analysis. | [Open directory](https://metabolomicscentre.ca/software-databases/software-data-analysis/) |
| Nephele | Web-based microbiome analysis platform. Review the current site for available workflows and accepted data types. | [Open platform](https://nephele.niaid.nih.gov/index) |
| GutMeta | Resource associated with microbiome analysis; check the website for current data and tools. | [Open resource](https://gutmeta.deepomics.org/) |
| Explore Metabar | Interactive application for exploring metabarcoding/microbiome data; consult the app for current input requirements. | [Open app](https://shiny.migale.inrae.fr/app/exploremetabar) |

## Drug response, survival, and translational analysis

| Resource | Description | Website |
|---|---|---|
| CPADS | Comprehensive pan-cancer analysis resource focused on drug sensitivity. | [Open app](https://smuonco.shinyapps.io/CPADS/) |
| SensitivitySeq | Resource focused on drug-sensitivity prediction. Review the current website for model details and supported inputs. | [Open resource](http://sensitivityseq.com/) |
| Survival Genie 2.0 | Web platform for survival analysis and visualization across datasets and analysis groups. | [Open app](https://bhasinlab.bmi.emory.edu/SurvivalGenie2/home) |
| shinyDeepDR | Deep-learning approach for predicting cancer drug response using mutation and gene-expression data. | [Open app](https://shiny.crc.pitt.edu/shinydeepdr/) |
| HCDT drug-target files | Download resource for drug-target files. Check the source page for file descriptions and release information. | [Open resource](http://hainmu-biobigdata.com/hcdt2/download.php) |

## General directories and reference resources

| Resource | Description | Website |
|---|---|---|
| Cancer Genetics Web | General directory of cancer genetics and related information resources. | [Open resource](https://www.cancer-genetics.org/) |
| Immunological Genome Project (ImmGen) | Reference resource for immune-cell gene-expression data and analysis tools. | [Open resource](http://rstats.immgen.org/MyGeneSet_New/index.html) |
| CellMarker 2.0 | Cell-marker reference database for identifying markers associated with different cell types. | [Open resource](http://bio-bigdata.hrbmu.edu.cn/CellMarker/CellMarker_download.html) |

## Notes for responsible use

- **Check the original source.** Web tools and databases can change, move, or become unavailable.
- **Record versions and access dates.** For reproducible research, document the database release, software version, date accessed, and analysis settings.
- **Validate results independently.** Treat web predictions and enrichment results as hypotheses that may require statistical and experimental validation.
- **Check licensing and data policies.** Confirm whether the resource permits redistribution, commercial use, or use with sensitive clinical data.
- **Avoid uploading identifiable or restricted data** unless the platform's privacy, security, and data-governance terms explicitly permit it.

---

*This page is a curated collection of external resources, not an endorsement of every tool. Descriptions are brief guides; consult the linked official websites for authoritative details.*
