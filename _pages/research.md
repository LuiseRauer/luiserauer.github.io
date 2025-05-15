---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

A new approach to correcting extraction bias in microbiome data
------
When investigating the microbiome, one of the first laboratory steps also introduces the most bias - lysing bacterial cells to extract their DNA. Yet, some bacteria break open more easily than others, which severely skews observed microbial compositions before sequencing even begins. We found that cell shape and Gram stain may help to fix this problem. Check out the full [publication in Microbiome](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-024-01998-4) and the [analysis code on Github](https://github.com/LuiseRauer/Extraction-bias-correction), where we also investigated the sources of sequence errors, chimera formation, and (cross-)contamination.  

Computational contaminant removal for microbiome data
------
Contaminants can spoil any microbiome sequencing experiment, but particularly those of sparsely inhabited body regions like the skin. Our tool MicrobIEM computationally reduces contaminants and can be used through a graphical user interface with interactive figures. Check out our [benchmarking published in BMC Biology](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-023-01737-5), try out the [tool online](https://env-med.shinyapps.io/microbiem/), or give feedback on the [source code on Github](https://github.com/LuiseRauer/MicrobIEM).

Open science, reproducibility, and bias quantification in microbiome research
------
With a plethora of methods available for generating microbiome data, are microbiome results actually comparable? In this meta-analysis of microbiome studies, we are investigating the status of [FAIR principles](https://www.go-fair.org/fair-principles/), the reproducibility of methods sections in scientific papers, and how laboratory choices affect final microbiome conclusions. Check out the first results of our [pilot study on Github](https://github.com/LuiseRauer/Mock-meta-analysis/blob/main/Mock-meta-analysis_pilot-results_2022-09-29.pdf). Collaborators and feedback welcome!

Skin microbiome and host cofactors in atopic dermatitis
------
Patients with atopic dermatitis (AD) usually have a reduced microbial diversity and overabundance of *Staphylococcus aureus* on their skin. We found that host cofactors, like IgE levels and race, may be key to the relation between microbiome composition and AD severity. And what does "low diversity" actually mean? Check out our full answer as [published in JEADV](https://onlinelibrary.wiley.com/doi/full/10.1111/jdv.18776) and corresponding [data analyses in R on Github](https://github.com/LuiseRauer/Anti-IL22-baseline). 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

