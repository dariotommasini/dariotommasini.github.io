---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Research
---

Below are a few research projects that I have or am currently working on!


1. **Development and evolution of the vertebrate visual system**  
    In my first project as a graduate student in Prof. Karthik Shekhar’s lab, I pursued the evolutionary origin of the tetrapod double cone, an unorthodox photoreceptor found only in certain tetrapods. These cells are called “double cones” because they are composed of two different cones – a principal and an accessory member. I led this project by developing and applying comparative transcriptomic methods like those described in Aim 1. Notably, I was able to i) isolate double cones in single-cell data, ii) pinpoint novel markers for the principal and accessory members, and iii) align photoreceptors across five vertebrates that span the emergence and loss of double cones. Based on this computational analysis, we concluded that both members of the double cone likely evolved from red cones, and provided a potential mechanism for their origin. I highlighted this work at the 2024 Berkeley Neuroscience Conference as a 5 minute lightning talk and at the 2024 Berkeley Vision Science Retreat as a 15 minute platform talk. 
    
    Tommasini D, Yoshimatsu T, Baden T, and Shekhar K. Comparative transcriptomic insights into the evolutionary origin of the tetrapod double cone. BioRxiv. 2024. 

2. **Generation of open-source bioinformatic tools for the scientific community**  
As an undergraduate researcher at UCLA, I realized that we could extract more information from gene expression data by leveraging the multidimensionality of experimental designs. In other words, datasets with multiple time points and tissues present the opportunity to perform multiple sub-level analyses that can then be integrated together to draw more sophisticated conclusions about the underlying transcriptional networks. Since the existing software implementation, WGCNA, was not designed for this sort of analysis, I developing multiWGCNA, an R package for deep mining gene co-expression networks in multi-trait expression data. Having demonstrated that multiWGCNA reveals interesting biological phenomena in mouse models of multiple sclerosis and Alzheimer’s disease, we published my software and findings in BMC Bioinformatics. To ensure that these methods are more accessible to others, I submitted my package to Bioconductor – the official repository for bioinformatic software in R. These efforts will advance data analysis and benefit the broader neuroscientific community by making bioinformatic tools more accessible to researchers and clinicians. I have also made a commitment to keeping this software package up-to-date and to provide users with technical support. As of now, I have closed over 20 issues on GitHub, where I have helped various users apply multiWGCNA to their data. 

    Tommasini D, Fogel BL. multiWGCNA: an R package for deep mining gene co-expression networks in multi-trait expression data. BMC Bioinformatics 24, 115 (2023). 
    
3. **Identifying gene expression patterns associated with neurological diseases**  
    It is well-established that neurological diseases differentially target specific brain regions. As an undergraduate researcher in Prof. Brent Fogel’s lab at UCLA, I investigated whether this phenomenon had a transcriptional basis. We used a statistical approach to identify candidate transcription factors and microRNAs that could be driving these expression patterns. We validated these candidates in silico using published data and in vitro using a human oligodendrocyte cell line. We also discovered that oligodendrocyte gene expression forms a gradient along the rostrocaudal axis of the mouse forebrain, which is intriguing since gradients of regulatory proteins pattern this axis during embryonic development.

    Tommasini D, Fox R, Ngo KJ, Hinman JD, Fogel BL. Alterations in oligodendrocyte transcriptional networks reveal region-specific vulnerabilities to neurological disease. iScience. 2023 Mar 8;26(4):106358.

4. **Identification of a novel class of mobile genetic elements in bacteria**  
    As a Biological Research and Development intern at Sandia National Laboratories, I studied prophages – bacterial viruses that can insert their genomes within bacterial chromosomes. My advisors, Dr. Kelly Williams (PI) and Dr. Catherine Mageeney (postdoc), discovered a small “satellite” prophage inserted within a larger “helper” prophage in the chromosome of a pathogenic E. coli strain. Using bioinformatics, we discovered that the satellite is just one member of a novel clade of phylogenetically-related prophages that insert themselves within the late operon of other prophages. These experiments led us to propose that this is a novel parasitic relationship between bacterial viruses.

    Tommasini, D, Mageeney, CM, Williams, KP (2023). Helper-embedded satellites from an integrase clade that repeatedly targets prophage late genes. NAR Genom Bioinform, 5, 2:lqad036.
