---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Bioinformatic contaminant removal for microbiome data
------
Contaminants can spoil any microbiome sequencing experiment, but particularly those of sparsely-inhabited body regions like the skin. Our tool MicrobIEM bioinformatically reduces contaminants, and can be used through a graphical user interface with interactive figures. Try it out [online](https://env-med.shinyapps.io/microbiem/) or give us feedback on the [source code on Github](https://github.com/LuiseRauer/MicrobIEM).

Correcting extraction bias and chimera formation in microbiome data
------
When generating microbiome data, one of the first laboratory steps is also one of the most biased ones - lysing bacterial cells to extract their DNA. During the ensuing DNA amplification step, DNA strands of different bacteria can get attached to each other and form chimeras. Both of these biases - extraction bias and chimera formation - can severely distort the measured bacterial communities. But what drives chimera formation? And can we correct extraction bias computationally by bacterial cell morphologies? In our [preprint](https://www.biorxiv.org/content/10.1101/2023.07.06.547990v1), we investigate the conditions that lead to increased chimera formation, computationally correct extraction bias, and track down contamination and cross-contamination. Feedback is welcome! 

Open science, reproducibility and biases in microbiome research
------
With a plethora of methods available for generating microbiome data, are microbiome results actually comparable? In this meta-analysis of microbiome studies, we are investigating the reproducibility of methods sections in scientific papers, and how laboratory choices affect your final microbiome conclusions. Check out some first results on [Github](https://github.com/LuiseRauer/Mock-meta-analysis/blob/main/Mock-meta-analysis_pilot-results_2022-09-29.pdf). 

Skin microbiome and host co-factors in atopic dermatitis
------
Patients with atopic dermatitis (AD) usually have a reduced microbial diversity and overabundance of Staphylococcus aureus on their skin. We found that host cofactors, like IgE levels and race, may be key to the relation between microbiome composition and AD severity. And what does "low diversity" actually mean? Check out our full answer as [published in JEADV](https://onlinelibrary.wiley.com/doi/full/10.1111/jdv.18776) and corresponding [data analyses in R on Github](https://github.com/LuiseRauer/Anti-IL22-baseline). 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

