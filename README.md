# AAGMEx_Aging_Network

This directory contains the MEGENA co-expression networks networks for adipose, muscle, and plasma metabolites of the AAGMEx cohort. The donor sex, BMI, and ethnic groups were adjusted before network construction. 

Author: Peng Xu

Email: peng.xu@mssm.edu

Draft date: March 22, 2023

## Description

The co-expression networks for different tissues were uniformly processed by the MEGENA pipeline. The gene expressions were generated from the normalized microarray datasets from the AAGMEx cohort. Metabolome was profiled by untargeted liquid chromatography-mass spectrometry.

For each tissue, three files were shared for the network results.

AAGMEx_{tissue}.network.tsv: The MEGENA co-expression network for each tissue.

AAGMEx_{tissue}.bigtable.tsv: The module summary information for the co-expression network.

AAGMEx_{tissue}.module.tsv: The module genes for the co-expression network.

AAGMEx_metabolite.expression.tsv: normalized metabolite expression of plasma in the AAGMEx cohort.


## Citation

## News

3/22/2023: First version released.

