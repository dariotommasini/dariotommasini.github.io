---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Research
---

Below are a few research projects that I have or am currently working on!


1. **Evolution of the vertebrate visual system**  
    In my first project as a graduate student in Prof. Karthik Shekhar’s lab, I pursued the evolutionary origin of the tetrapod double cone, an unorthodox photoreceptor found only in certain tetrapods. These cells are called “double cones” because they are composed of two different cone photoreceptors – a principal and accessory member. Notably, we were able to i) isolate double cones in single-cell data, ii) identify novel markers for the principal and accessory members, and iii) align photoreceptors across five vertebrates that span the emergence and loss of double cones. Based on this computational analysis, we concluded that the principal member likely evolved from red cones, while the origin of the accessory member is less clear. I highlighted this work at the 2024 Berkeley Neuroscience Conference as a 5 minute lightning talk and at the 2024 Berkeley Vision Science Retreat as a 15 minute platform talk. 
    
    [Tommasini D, Yoshimatsu T, Baden T, and Shekhar K. Comparative transcriptomic insights into the evolutionary origin of the tetrapod double cone. BioRxiv. 2024.](https://www.biorxiv.org/content/10.1101/2024.11.04.621990v1)
    
    ![Double cone evolution figure](files/research-dc.png)
<!--<img src="image.png" alt="Description" width="500" height="300">-->
<!--<img src="files/research-dc.png" alt="Double cone evolution figure" width="500">-->
    <br>
    <br>
2. **Generation of open-source bioinformatic tools for the scientific community**  
    As an undergraduate researcher at UCLA in Prof. Brent Fogel's lab, I realized that we could extract more information from gene expression data by leveraging the multidimensionality of experimental designs. In other words, datasets with multiple time points and tissues present the opportunity to perform multiple sub-level analyses that can then be integrated together to draw more sophisticated conclusions about the underlying transcriptional networks. Since the existing software implementation, WGCNA, was not designed for this sort of analysis, I developing multiWGCNA, an R package for deep mining gene co-expression networks in multi-trait expression data. Having demonstrated that multiWGCNA reveals interesting biological phenomena in mouse models of multiple sclerosis and Alzheimer’s disease, we published my software and findings in *BMC Bioinformatics*. To ensure that these methods are more accessible to others, I submitted my package to Bioconductor – the official repository for bioinformatic software in R. These efforts will advance data analysis methods and benefit the broader neuroscientific community by making bioinformatic tools more accessible to researchers and clinicians. I have also made a commitment to keeping this software package up-to-date and to provide users with technical support. 
    
    [Tommasini D, Fogel BL. multiWGCNA: an R package for deep mining gene co-expression networks in multi-trait expression data. BMC Bioinformatics 24, 115 (2023).](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05233-z)
        <br>
    Available on [Bioconductor](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05233-z) and [GitHub](https://github.com/fogellab/multiWGCNA)
    
    ![multiWGCNA figure](files/research-mw.png)
    <br>
    <br>
3. **Analysis of gene expression patterns associated with neurological diseases**  
    Neurological diseases differentially target specific brain regions. As an undergraduate researcher at UCLA in Prof. Brent Fogel’s lab, I investigated whether this phenomenon had a transcriptional basis. We focused primarily on oligodendrocytes (OLs), the myelinating cells of the CNS. By weighted gene co-expression network analysis (WGCNA), we found that oligodendrocyte (OL) transcriptional networks were dysregulated in various neurological diseases in a region-specific manner, e.g. cerebelllar OLs in ataxia. We then used statistical approaches to identify candidate transcription factors and microRNAs that could be regulating these expression patterns. We validated these candidates *in silico* using published data and *in vitro* using a human OL cell line. We also discovered that OL gene expression forms a gradient along the rostrocaudal axis of the mouse forebrain, which is intriguing since gradients of regulatory proteins pattern this axis during embryonic development.

    [Tommasini D, Fox R, Ngo KJ, Hinman JD, Fogel BL. Alterations in oligodendrocyte transcriptional networks reveal region-specific vulnerabilities to neurological disease. iScience. 2023 Mar 8;26(4):106358.](https://doi.org/10.1016/j.isci.2023.106358)
    
    ![Oligodendrocyte figure](files/research-ol.jpg)
    <br>
    <br>
4. **Identification of a novel class of mobile genetic elements in bacteria**  
    As a Biological Research and Development intern at Sandia National Laboratories, I studied prophages – bacterial viruses that can insert their genomes within bacterial chromosomes. My advisors, Dr. Kelly Williams (PI) and Dr. Catherine Mageeney (postdoc), discovered a small “satellite” prophage inserted within a larger “helper” prophage in the chromosome of a pathogenic E. coli strain. Using bioinformatics, we discovered that the satellite is just one member of a novel clade of phylogenetically-related prophages that insert themselves within the late operon of other prophages. These experiments led us to propose that this is a novel parasitic relationship between prophages. Interestingly, this family of satellites preferentially targets helper late genes, leveraging the machinery of the helper prophage to excise and replicate. 

    [Tommasini, D, Mageeney, CM, Williams, KP (2023). Helper-embedded satellites from an integrase clade that repeatedly targets prophage late genes. NAR Genom Bioinform, 5, 2:lqad036.](https://doi.org/10.1093/nargab/lqad036)

    ![Helper embedded satellite figure](files/research-he.png)
    <br>
    <br>
