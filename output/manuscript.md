---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
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
  <meta name="dc.title" content="Manuscript Title" />
  <meta name="citation_title" content="Manuscript Title" />
  <meta property="og:title" content="Manuscript Title" />
  <meta property="twitter:title" content="Manuscript Title" />
  <meta name="dc.date" content="2023-02-08" />
  <meta name="citation_publication_date" content="2023-02-08" />
  <meta property="article:published_time" content="2023-02-08" />
  <meta name="dc.modified" content="2023-02-08T15:34:38+00:00" />
  <meta property="article:modified_time" content="2023-02-08T15:34:38+00:00" />
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

<!--
ERROR: the paragraph below could not be revised with the AI model due to the following error:

Incorrect API key provided: {api_key}. You can find your API key at https://platform.openai.com/account/api-keys.
-->
How can the efficiency and specificity of CRISPR-based tools be maximized? To address this problem, this paper proposes a machine learning-based approach for gRNA design for multiple CRISPR-Cas systems.
We develop a Markdown-based publishing platform, Manubot, to facilitate the efficient administration of CRISPR-based tools.
This platform provides a comprehensive set of design rules for various CRISPR-Cas systems, enabling the prediction of gRNAs with high on-target efficiency and off-target specificity.


<!--
ERROR: the paragraph below could not be revised with the AI model due to the following error:

Incorrect API key provided: {api_key}. You can find your API key at https://platform.openai.com/account/api-keys.
-->
This work investigates the design rules for CRISPR interference (CRISPRi) to understand its potential for functional interrogation, pathway manipulation, and genome-wide screens in bacteria.
To address this research problem, a state-of-art predictive machine learning model is developed to predict guide silencing efficiency in bacteria.
This model leverages the advantages of feature engineering, data integration, interpretable AI, and automated machine learning.
Results show that gene-specific effects, such as gene expression level, make a dominant contribution to the extent of depletion in multiple CRISPRi genome-wide essentiality screens in Escherichia coli.
This observation allows for the confounding gene-specific effects to be segregated using the mixed-effect random forest (MERF) model to provide a better estimate of guide efficiency.
The MERF model outperforms existing tools in the independent datasets, including small-scale fluorescence-based and miller assays.
Design rules for robust gene silencing are extracted, such as the preference for cytosine and disfavoring for guanine and thymine within and around the PAM sequence.
This work is concluded with a web-based tool, freely accessible at www.ciao.helmholtz-hiri.de, that incorporates the MERF model.


<!--
ERROR: the paragraph below could not be revised with the AI model due to the following error:

Incorrect API key provided: {api_key}. You can find your API key at https://platform.openai.com/account/api-keys.
-->
This paper presents a machine learning approach to effectively develop prediction algorithms for CRISPR-Cas systems.
The workflow includes three principle steps: accommodating the feature set for the CRISPR-Cas system or technique; optimizing a machine learning model using automated machine learning; and explaining the model using interpretable AI.
This workflow was applied to analyze three different CRISPR-Cas genome-wide screens, and the results revealed various design rules for efficient editing, target expression level as a main determinant of activation of Cas13-induced immunity, and robust antimicrobial activity across K.
pneumoniae strains.
The proposed approach provides a blueprint for the development of prediction algorithms that are robust across organisms and CRISPR-Cas techniques.

 
<!--
ERROR: the paragraph below could not be revised with the AI model due to the following error:

Incorrect API key provided: {api_key}. You can find your API key at https://platform.openai.com/account/api-keys.
-->
This thesis presents a machine learning approach to accurately predict the CRISPRi guide efficiency in bacteria.
This systematic exploration of the determinants of efficient silencing and guide designs has led to a robust model which can be applied to other bacteria and CRISPR-Cas systems.
Furthermore, the analysis of independent CRISPR-Cas screens using this model provides insights into the design rules and mechanisms of the CRISPR-Cas systems.
The results of this research demonstrate that machine learning can be successfully applied to gain a deeper understanding and broader application of CRISPR-Cas systems.





## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

