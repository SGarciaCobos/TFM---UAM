# Trabajo de Fin de Máster
###  Máster en Bioinformática y Biología Computacional, Universidad Autónoma de Madrid
### Curso Académido 2022-2023

TÍTULO : **Análisis de genomas bacterianos, Klebsiella pneumoniae. Estrategia de secuenciación mixta: secuencias largas y cortas.** 
   Subtítulo: **Genomic pathogenicity of OXA-48-producing Klebsiella pneumoniae clinical isolates.**

AUTORA: **Silvia García Cobos**

Este repositorio contiene los scripts utilizados en el trabajo de fin de máster.

PYTHON SCRIPTS:

**mlplasmid_RES_intersect.ipynb**: This script allows the combination of results from mlplasmid software (contig prediction as plasmid or chromosome) and abricate software (presence/absence of genes of interest) results. In this case we are using abricate results based on ResFinder database: antibiotic resistance genes. 

**mlplasmid_vfkp_intersect.ipynb**: This script allows the combination of results from mlplasmid software (contig prediction as plasmid or chromosome) and abricate software (presence/absence of genes of interest) results. In this case we are using abricate results based on a local virulence genes database. 

**mlplasmid_plasREP_intersect.ipynb**: This script allows the combination of results from mlplasmid software (contig prediction as plasmid or chromosome) and abricate software (presence/absence of genes of interest) results. In this case we are using abricate results based on PlasmidFinder database: plasmid replicon genes.

**mlplasmid07_intersect_bySample.ipynb**: This script allows the combination of results from mlplasmid software (contig prediction as plasmid or chromosome) and abricate software (presence/absence of genes of interest) results. For each database used, we can merge all genes predicted in plasmid contigs and in chromosomal contigs per isolate.


