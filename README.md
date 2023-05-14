# Trabajo de Fin de Máster
###  Máster en Bioinformática y Biología Computacional, Universidad Autónoma de Madrid
### Curso Académido 2022-2023

TÍTULO : **Análisis de genomas bacterianos, Klebsiella pneumoniae. Estrategia de secuenciación mixta: secuencias largas y cortas.** 
   Subtítulo: **Genomic pathogenicity of OXA-48-producing Klebsiella pneumoniae clinical isolates.**

AUTORA: **Silvia García Cobos**

This repository has phython scripts used during this TFM. 

__________

PYTHON SCRIPTS:

**mlplasmid_RES_intersect.ipynb**: This script allows the combination of results from mlplasmid software (contig prediction as plasmid or chromosome) and abricate software (presence/absence of genes of interest) results. In this case we are using abricate results based on ResFinder database: antibiotic resistance genes. 
   * *input files*: mlplasmid results in csv format and abricate results using ResFinder database (or another database for antibiotic resistance genes)

**mlplasmid_vfkp_intersect.ipynb**: This script allows the combination of results from mlplasmid software (contig prediction as plasmid or chromosome) and abricate software (presence/absence of genes of interest) results. In this case we are using abricate results based on a local virulence genes database. 
   * *input files*: mlplasmid results in csv format and abricate results using local database for virulence genes (or another database for virulence genes)
   
**mlplasmid_plasREP_intersect.ipynb**: This script allows the combination of results from mlplasmid software (contig prediction as plasmid or chromosome) and abricate software (presence/absence of genes of interest) results. In this case we are using abricate results based on PlasmidFinder database: plasmid replicon genes.
   * *input files*: mlplasmid results in csv format and abricate results using PlasmidFinder database (plasmid replicon genes)

**mlplasmid07_intersect_bySample.ipynb**: This script allows the combination of results from mlplasmid software (contig prediction as plasmid or chromosome) and abricate software (presence/absence of genes of interest) results. For each database used, we can merge all genes predicted in plasmid contigs and in chromosomal contigs per isolate.
   * *input files*: mlplasmid results grouped by isolate and plasmid/chromosome prediction (threshold posterior probability >0.7 or none) for each database of interest


______
CUSTOM DATABASE for *Klebsiella pneumoniae* virulence genes:

   We created a customized local database - named vfkp - of the most relevant virulence genes for *Klebsiella pneumoniae* based on a scientific literature review and Klebsiella *spp.* curated public databases. It is included a formatted text and multifasta file to run it using abricate software. 
 
____


## Software utilizado

* [Python](https://www.python.org)
* [R](https://www.r-project.org)
* [mlplasmids](https://gitlab.com/sirarredondo/mlplasmids)
* [abricate](https://github.com/tseemann/abricate)

