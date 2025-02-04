# Atopic dermatitis in time and space

This repo documents the reproducible data analysis pipelines for AD in time and space project.

## Data analysis pipeline

[![DOI](https://www.zenodo.org/badge/378928145.svg)](https://www.zenodo.org/badge/latestdoi/378928145)

Check [GitHub repo](https://github.com/tuhulab/Shiny_AD_time_space) for any update.

View publication in Journal of Investigative Dermatology: [Assessment of Spatial and Temporal Variation in the Skin Transcriptome of Atopic Dermatitis by Use of Minimally Invasive Punch Biopsies](https://www.jidonline.org/article/S0022-202X(22)02657-4/fulltext))

| rmd                               | description                                                                         |
|-----------------------------------|-------------------------------------------------------------------------------------|
| 1-transcriptome-data-cleaning.Rmd | Data cleaning and curation                                                          |
| 2-geo-upload.Rmd                  | Upload data to GEO                                                                  |
| 3-table1-tableS1.Rmd              | Table 1 (Baseline characteristics) and Table S1 (sample metadata, subject metadata) |
| 4-tableS2.Rmd                     | Table S2 (differential gene expression analysis)                                    |
| 5-figure1.Rmd                     | Figure 1 (PCA, heatmap, Venn)                                                       |
| 6-figure2.Rmd                     | Figure 2 (Across-study functional enrichment analysis)                              |
| 7-figure3.Rmd                     | Figure 3 (Variance partition analysis)                                              |
| 8-figure4.Rmd                     | Figure 4 (Space variation)                                                          |
| 9-figureS1.Rmd                    | Figure S1 (Transcriptome heatmap, cosine distance)                                  |
| 10-figureS2.Rmd                   | Figure S2 (Genome regulatory elements)                                              |
| 11-figureS3.Rmd                   | Figure S3 (Time variation)                                                          |
| 12-figureS4.Rmd                   | Figure S4 (Intraindividual variation)                                               |
| 13-figureS5.Rmd                   | Figure S5 (Time fluctuation of disease severity)                                    |
| 14-figureS6.Rmd                   | Figure S6 (Correlation heatmap of IL34, IL37, UGT3A2 and inflammatory biomarkers)   |

## Shiny application for data exploration and downloading

-   [Shiny app](https://bit.ly/34OlBal)

-   [Github](https://github.com/tuhulab/Shiny_AD_time_space)

## Data availability

-   RNA-seq data is available at GEO under the accession number [GSE193309](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE193309)
