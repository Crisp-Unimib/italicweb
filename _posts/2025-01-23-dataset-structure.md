---
layout: post
title: Dataset Structure
subtitle: What the dataset looks like
gh-repo: Crisp-Unimib/ITALIC
gh-badge: [star, fork, follow]
cover-img: /assets/img/duomo.png
thumbnail-img: /assets/img/duomo.jpg
share-img: /assets/img/thumb.png
tags:
  [
    dataset,
    structure,
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
_ITALIC_ contains 10,000 carefully curated questions selected from an initial corpus of 2,110,643 questions.

<!-- This section provides a description of the dataset fields, and additional information about the dataset structure such as criteria used to create the splits, relationships between data points, etc. -->

Each question is formatted as a multiple-choice query, with an average question length of 87 characters and a median of 4 answer options.
The longest question is 577 characters long. The minimum number of choices per question is 2, while the maximum is 5.
The total number of tokens across the input data amounts to 499,963.

| Column     | Data Type | Description                                     |
| ---------- | --------- | ----------------------------------------------- |
| `question` | [String]  | The actual content of the question              |
| `options`  | [List]    | The options to choose from. Only one is correct |
| `answer`   | [String]  | The correct answer out of the options           |
| `category` | [String]  | The dedicated cultural section of the question  |
