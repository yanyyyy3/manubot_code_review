---
title: Improved prediction of bacterial CRISPRi guide efficiency through data integration and automated machine learning
keywords:
- CRISRPi
- machine learning
- guide efficiency
- bacteria
- data integration
- automated machine learning
lang: en-US
date-meta: '2023-02-08'
author-meta:
- John Doe
- Jane Roe
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Improved prediction of bacterial CRISPRi guide efficiency through data integration and automated machine learning" />
  <meta name="citation_title" content="Improved prediction of bacterial CRISPRi guide efficiency through data integration and automated machine learning" />
  <meta property="og:title" content="Improved prediction of bacterial CRISPRi guide efficiency through data integration and automated machine learning" />
  <meta property="twitter:title" content="Improved prediction of bacterial CRISPRi guide efficiency through data integration and automated machine learning" />
  <meta name="dc.date" content="2023-02-08" />
  <meta name="citation_publication_date" content="2023-02-08" />
  <meta property="article:published_time" content="2023-02-08" />
  <meta name="dc.modified" content="2023-02-08T16:39:39+00:00" />
  <meta property="article:modified_time" content="2023-02-08T16:39:39+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="John Doe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Jane Roe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
was automatically generated
on February 8, 2023.
</em></small>



## Authors



+ **John Doe**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [johndoe](https://twitter.com/johndoe)
    · ![Mastodon icon](images/mastodon.svg){.inline_icon}
    [\@johndoe@mastodon.social](https://mastodon.social/@johndoe)
    <br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [janeroe](https://github.com/janeroe)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>


::: {#correspondence}
✉ — Correspondence possible via GitHub Issues
or email to
Jane Roe \<jane.roe@whatever.edu\>.


:::


## Abstract {.page_break_before}

This paper proposes a novel approach to improve the prediction of bacterial CRISPRi guide efficiency through data integration and automated machine learning.
We combine the existing gRNA design rules with the features generated from the machine learning algorithms to form a hybrid prediction model.
This hybrid model is then trained with a large-scale dataset to optimize the gRNA selection.
Our results demonstrate that the hybrid model significantly outperforms the state-of-the-art models in predicting bacterial CRISPRi guide efficiency.

This work presents a novel machine learning model that improves the prediction of CRISPRi guide efficiency in bacteria.
By leveraging feature engineering, data integration, interpretable AI, and automated machine learning, the model is able to systematically investigate the influential factors that attribute to the extent of depletion in CRISPRi genome-wide essentiality screens in Escherichia coli.
This approach allows for the segregation of confounding gene-specific effects and provides a better estimate of guide efficiency, resulting in improved performance compared to existing tools.
Additionally, the model is able to extract design rules for robust gene silencing, such as the preference for cytosine and disfavoring for guanine and thymine within and around the PAM sequence.
This research is made freely accessible through a web-based tool at www.ciao.helmholtz-hiri.de.

This paper presents a machine learning approach to improve the prediction of bacterial CRISPRi guide efficiency.
The workflow includes three steps: 1) accommodating the feature set for the CRISPR-Cas system or technique; 2) optimizing a machine learning model using automated machine learning; and 3) explaining the model using interpretable AI.
The approach was applied to analyze three CRISPR-Cas genome-wide screens, revealing design rules for robust antimicrobial activity across different organisms and providing a predictive algorithm for gRNA design.
The results demonstrate that the proposed approach can effectively predict guide efficiency across different CRISPR-Cas systems, enabling the development of more reliable prediction algorithms.
 
This thesis presents a machine learning approach for accurately predicting CRISPRi guide efficiency in bacteria, which provides insights into the determinants of efficient silencing and guide designs.
The approach was systematically explored and developed into a robust model for use in other bacteria and CRISPR-Cas systems.
Applying the approach in the analysis of independent CRISPR-Cas screens reveals not only the design rules but also the mechanisms of the CRISPR-Cas systems.
The results demonstrate that machine learning can be applied to gain a deeper understanding and broader application of CRISPR-Cas systems.




## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

