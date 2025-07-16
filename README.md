# RNAseqAnalysis-NaisCommunis

Este repositorio contiene el análisis transcriptómico de *Nais communis*.

## Objetivo: Explorar perfiles y patrones de expresión génica y procesos biologicos asociados al proceso de regeneracion axial.

## Herramientas utilizadas: 

- R y Bioconductor
- Trinity para ensamble de novo de transcriptoma
- Blast+ y Trinotate para anotacion funcional de genes
- EdgeR y NOISeq para análisis de expresión diferencial
- ClusterProfiler y topGO para análisis de ontología génica

## Archivos principales

- `NAIco.Rmarkdown.AF.Rmd`: documento Rmarkdown con el pipeline.
- `NAIco_v2_t1.trinity.out.transcripts.fasta`: archivo fasta del transcriptoma ensamblado de Nais communis
- `GSF1048-OT-NC-D1_S26_R1_001.qtrim.fq`: documento Rmarkdown con el pipeline
- `GSF1048-OT-NC-D2_S27_R1_001.qtrim.fq`: documento Rmarkdown con el pipeline
- `GSF1048-OT-NC-D3_S28_R1_001.qtrim.fq`: documento Rmarkdown con el pipeline

## Resultados esperados

Comparacion de desempeño de los paquetes usados para analisis de expresion diferencial, identificación de genes clave, enriquecimiento de procesos biológicos, visualizaciones claras y reproducibles.

## Autora

Andrea C. Famá, tesista de Licenciatura en Ciencias Biologicas.

