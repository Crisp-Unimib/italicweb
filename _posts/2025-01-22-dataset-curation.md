---
layout: post
title: Dataset Curation
subtitle: A detailed description of the dataset curation process
gh-repo: Crisp-Unimib/ITALIC
gh-badge: [star, fork, follow]
cover-img: /assets/img/colosseo.png
thumbnail-img: /assets/img/colosseo.jpg
share-img: /assets/img/thumb.png
tags:
  [
    dataset,
    curation,
    italian,
    culture,
    commonsense,
    reasoning,
    linguistic,
    proficiency,
  ]
author: CRISP Research
---

{: .box-success}
The corpus comprises questions and tasks from real-world exams, professional assessments, and domain-specific challenges.
Given that the data originates from institutional sources, it is expected to maintain a high standard of quality and accuracy, as domain experts crafted it for public evaluations.

<!-- Motivation for the creation of this dataset. -->

### Source Data

<!-- This section describes the source data (e.g. news text and headlines, social media posts, translated sentences, ...). -->

#### Data Collection and Processing

<!-- This section describes the data collection and processing process such as data selection criteria, filtering and normalization methods, tools and libraries used, etc. -->

The initial data was sourced from various files in PDF, HTML, DOC, and other formats published by official bodies that announce individual competitive public examinations.

Please consult the full paper for a detailed description of our curation process.

<center><img src="./img/assets/workflow.svg" width="350" height="350" /></center>

#### Who are the source data producers?

<!-- This section describes the people or systems who originally created the data. It should also include self-reported demographic or identity information for the source data creators if this information is available. -->

The dataset includes tests for admission to the Carabinieri, Penitentiary Police, Italian Army, State Police, Forestry Corps, Firefighters, Air Force, Navy, Guardia di Finanza, Italian ministries, teachers of the Italian school system of all levels, principals of the Italian school system of all levels, nurses of the national health system, and managers of the public administration from 2008 to 2024 available freely on the website of each institutional body.

#### Personal and Sensitive Information

<!-- State whether the dataset contains data that might be considered personal, sensitive, or private (e.g., data that reveals addresses, uniquely identifiable names or aliases, racial or ethnic origins, sexual orientations, religious beliefs, political opinions, financial or health data, etc.). If efforts were made to anonymize the data, describe the anonymization process. -->

The dataset does not contain confidential information.
It is also free from content that could be considered offensive, insulting, threatening, or distressing. Since it solely comprises data from standardised tests and does not involve human subjects or personal data, an ethical review process was not required.

## Bias, Risks, and Limitations

<!-- This section is meant to convey both technical and sociotechnical limitations. -->

Potential risks of misuse include using the benchmark results to justify or argue against the need to develop native LLMs specifically tailored for the Italian language.
This possibility should be considered to avoid misinterpretations or unintended consequences when leveraging the evaluation outcomes.

### Maintenance

_ITALIC_ is designed to be robust and fully operational upon release, with no need for routine maintenance. However, as language and cultural norms evolve, periodic updates will be required to ensure the benchmark remains relevant. A new dataset version will be created and made available in such cases.
