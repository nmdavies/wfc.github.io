---
layout: page
title: Projects
permalink: /projects/
---

**Project 1: Sibling GWAS**

Leads: Laurence Howe, Ben Brumpton, Gib Hemani, Neil Davies

There is increasing evidence that genetic effects on social phenotypes are substantially attenuated after controlling for family fixed effects in samples of siblings. For example, [Lee et al., 2018](https://www.nature.com/articles/s41588-018-0147-3) found that the effects of the genome-wide significant SNPs for years of education attenuated by around one half. Consistent with this, [Kong et al (2018)](https://science.sciencemag.org/content/359/6374/424) found substantial evidence that non-inherited genetic variants were associated with outcomes in offspring. These findings suggest that genetic effects estimated in GWAS for some (particularly social) phenotypes may be biased. In this project, we will conduct GWA on samples of siblings using a within family model (i.e. including a family fixed effect). This analysis will be conducted across a broad range of available phenotypes (e.g. education, cognitive performance, BMI, height, CRP, etc) to investigate the prevalence of “within family” bias in established GWAS of unrelated individuals. This project will focus on a sibling design, but there are plans to expand future projects to include mother-father-offspring trio designs.

Research question: Do total, between and within family SNP-phenotype associations differ?

We are conducting GWAS of 25 phenotypes using data from studies with siblings and relevant phenotypes. A full description of the analysis can be found in the [statistical analysis plan](https://docs.google.com/document/d/1A9HbwdVEnSul7eSeTdYfLtH1rkjTv5VMYVBs0wfZnxQ/edit?usp=sharing). The end of the SAP lists the studies that are contributing to the analysis, study eligibility requirements and the phenotypes that are currently included in the study.

**Code**

The analysis is being run independently by analysts for each study. Laurence Howe has written an automated pipeline that is available on his [GitHub page](https://github.com/LaurenceHowe/SiblingGWAS). This automates most of the process of running the analysis, creating the study summary data and packages summary associations (SNP-phenotype associations) up for upload to University of Bristol servers. We will meta-analyze the summary data across the studies, and make summary data publicly available.

We have finished a first draft of this paper and submitted to bioRxiv, you can find the full paper [here](http://) , and a blog post describing our findings [here](http://). We plan to update the analysis to include additional studies as part of the revise and resubmit process. If you are interested in being involved in this project, and have samples of genotyped siblings, please contact [Neil Davies](mailto:neil.davies@bristol.ac.uk) and [Laurence Howe](mailto:laurence.howe@bristol.ac.uk).

**Project 2: MZ GWAS of variance**

Leads: Elham Assray, Teemu Palviainen, Neil Davies, Laurence Howe, Jaakko Kaprio

The majority of genome-wide association studies (GWAS) to date have focused on identifying genetic markers associated with phenotype means. Contrastingly, much less is understood about genetic markers which influence phenotypic variation (variance quantitative trait loci; vQTL). The association of such markers with phenotypic variation may reflect interactions with environmental factors, as is thought to be the case for the adiposity influencing variant near/in FTO, or may capture biological mechanisms of an allele leading directly to higher variability. Therefore, identification of vQTL could improve understanding of underlying biology as well as the interplay between genetics and the environment.

Previous research into vQTLs has largely focused on obesity-related traits and predominantly used non-family based methods; for example, two recent studies (Young, Wauthier et al. 2018, Wang, Zhang et al. 2019) using UK Biobank data. An orthogonal approach to identify vQTL is to use a family-based method where we evaluate if there are genetic effects on phenotypic differences between monozygotic (MZ) twins. MZ twins share the same genotype at the vast majority of the genome but will often have discernible phenotypic differences. This MZ twin approach for identifying vQTL has been used previously for lipids on a sample of around 2,000 twin-pairs (Surakka, Whitfield et al. 2012) and in emotional symptoms in a sample of around 1,000 twin-pairs (Keers, Coleman et al. 2016). In this more recent study, the authors showed that a polygenic score created using the results of the GWAS moderated the effects of parenting and treatment response in two further samples. 

We propose to extend previous work with a larger sample size and with the inclusion of additional phenotypes. This will involve a collaborative meta-analysis GWAS of associations between genetic variation and phenotypic differences between monozygotic twins for a variety of physical and psychological phenotypes (e.g. height, body mass index, lipids, depression and anxiety and educational attainment). A full description of the analysis can be found in the [statistical analysis plan](https://uob-my.sharepoint.com/:w:/g/personal/ecnmd_bristol_ac_uk/EVJS4V21nbhImJuYIeMUk44BH6qCt678F10g4dTVq0UDNA?e=P3ZdlD).

**Code**
Github repository containing an example pipeline with relevant scripts can be found [here](https://github.com/LaurenceHowe/MZTwins-vQTL). As with the sibling GWAS, this automates most of the process of running the analysis, creating the study summary data and packages summary associations (SNP-phenotype associations) up for upload to KCL/University of Helsinki servers. Again, we will meta-analyze the summary data across the studies, and make summary data publicly available.


