# Awesome Human-centered Machine Translation

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of works on **Human-centered Machine Translation** categorized along several dimensions (i.e., *factors*,  *contexts*, *user types*, and *work types*). This list originates from our paper:

> Beatrice Savoldi, Alan Ramponi, Matteo Negri, and Luisa Bentivogli. 2025. **Translation in the Hands of Many: Centering Lay Users in Machine Translation Interactions**. In *Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing*, Suzhou, China. Association for Computational Linguistics. [[cite]](#paperclip-citation) [[paper]](https://arxiv.org/abs/2502.13780)

✨ **Contributions.** Feel free to suggest additional works by submitting a pull request — instructions available [here](contributing.md) ✨

### :paperclip: Citation

Please cite our paper [[Savoldi et al., EMNLP 2025]](https://arxiv.org/abs/2502.13780) if you find this curated list useful in your research:
```
@inproceedings{savoldi-2025-translationhands,
    title = "Translation in the Hands of Many: Centering Lay Users in Machine Translation Interactions",
    author = "Savoldi, Beatrice and Ramponi, Alan and Negri, Matteo and Bentivogli, Luisa",
    booktitle = "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://arxiv.org/abs/2502.13780"
}
```


# Index

- [**By Factors**](#by-factors)
    - [:point_up_2: **Usability**](#point_up_2-usability)
    - [:heavy_check_mark: **Trust**](#heavy_check_mark-trust)
    - [:book: **Literacy**](#book-literacy)
- [**By Contexts**](#by-contexts)
    - [:closed_book: **Education**](#closed_book-education)
    - [:hospital: **Medical/health**](#hospital-medical-health)
    - [:white_circle: **Generic/unspecified**](#white_circle-generic-unspecified)
- [**Related Surveys**](#related-surveys)

Each work is further characterized along the following dimensions:

- **Work type(s)**: ![Experimental](https://img.shields.io/badge/experimental-darkgreen), ![Position](https://img.shields.io/badge/position-purple), ![Survey](https://img.shields.io/badge/survey-blue), ![Frameworks](https://img.shields.io/badge/frameworks-orange), or ![Learning](https://img.shields.io/badge/learning-brown) resources
- **User type(s)**: ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) users, *specific* users (e.g., ![Physicians](https://img.shields.io/badge/physicians-yellow)), or *domain experts* (e.g., ![Translation students](https://img.shields.io/badge/translation&nbsp;students-magenta))
- **Factor(s)**: :point_up_2: (usability), :heavy_check_mark: (trust), and :book: (literacy)
- **Context(s)**: :closed_book: (education), :hospital: (medical/health), :white_circle: (generic/unspecified)


## By Factors

### :point_up_2: Usability

| Work | Work type(s) | User type(s) | Context(s) |
| ---- | ------------ | ------------ | ---------- |
| Evaluation and Usability of Back Translation for Intercultural Communication [[Shigenobu, UI-HCII 2007]](https://link.springer.com/chapter/10.1007/978-3-540-73289-1_31) | ![Experimental](https://img.shields.io/badge/experimental-darkgreen) | ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) | :white_circle: |

- Evaluation and Usability of Back Translation for Intercultural Communication [[Shigenobu, UI-HCII 2007]](https://link.springer.com/chapter/10.1007/978-3-540-73289-1_31) ![Experimental](https://img.shields.io/badge/experimental-darkgreen) ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) :white_circle:

### :heavy_check_mark: Trust

| Work | Work type(s) | User type(s) | Context(s) |
| ---- | ------------ | ------------ | ---------- |
| Physician Detection of Clinical Harm in Machine Translation: Quality Estimation Aids in Reliance and Backtranslation Identifies Critical Errors [[Mehandru et al., EMNLP 2023]](https://aclanthology.org/2023.emnlp-main.712/) | ![Experimental](https://img.shields.io/badge/experimental-darkgreen) | ![Physicians](https://img.shields.io/badge/physicians-yellow) | :hospital: |
| Machine translation believability [[Martindale et al., HCINLP 2021]](https://aclanthology.org/2021.hcinlp-1.14/) | ![Experimental](https://img.shields.io/badge/experimental-darkgreen) | ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) | :white_circle: |
| Evaluation and Usability of Back Translation for Intercultural Communication [[Shigenobu, UI-HCII 2007]](https://link.springer.com/chapter/10.1007/978-3-540-73289-1_31) | ![Experimental](https://img.shields.io/badge/experimental-darkgreen) | ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) | :white_circle: |
| Beyond General Purpose Machine Translation: The Need for Context-specific Empirical Research to Design for Appropriate User Trust [[Deng et al., TRAIT 2022]](https://arxiv.org/abs/2205.06920) | ![Position](https://img.shields.io/badge/position-purple) | ![Clinicians](https://img.shields.io/badge/clinicians-yellow) | :hospital: |

- Physician Detection of Clinical Harm in Machine Translation: Quality Estimation Aids in Reliance and Backtranslation Identifies Critical Errors [[Mehandru et al., EMNLP 2023]](https://aclanthology.org/2023.emnlp-main.712/) ![Experimental](https://img.shields.io/badge/experimental-darkgreen) ![Physicians](https://img.shields.io/badge/physicians-yellow) :hospital:
- Machine translation believability [[Martindale et al., HCINLP 2021]](https://aclanthology.org/2021.hcinlp-1.14/) ![Experimental](https://img.shields.io/badge/experimental-darkgreen) ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) :white_circle:
- Evaluation and Usability of Back Translation for Intercultural Communication [[Shigenobu, UI-HCII 2007]](https://link.springer.com/chapter/10.1007/978-3-540-73289-1_31) ![Experimental](https://img.shields.io/badge/experimental-darkgreen) ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) :white_circle:
- Beyond General Purpose Machine Translation: The Need for Context-specific Empirical Research to Design for Appropriate User Trust [[Deng et al., TRAIT 2022]](https://arxiv.org/abs/2205.06920) ![Position](https://img.shields.io/badge/position-purple) ![Clinicians](https://img.shields.io/badge/clinicians-yellow) :hospital:

### :book: Literacy

| Work | Work type(s) | User type(s) | Context(s) |
| ---- | ------------ | ------------ | ---------- |
| Towards a Framework for Machine Translation Literacy [[Bowker and Ciro, 2019]](https://www.emerald.com/books/monograph/10805/chapter-abstract/80421929/Towards-a-Framework-for-Machine-Translation?redirectedFrom=fulltext) | ![Frameworks](https://img.shields.io/badge/frameworks-orange) | ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) | :white_circle: |
| DataLitMT – teaching data literacy in the context of machine translation literacy [[Hackenbuchner and Krüger, 2023]](https://aclanthology.org/2023.eamt-1.28/) | ![Frameworks](https://img.shields.io/badge/frameworks-orange) ![Learning](https://img.shields.io/badge/learning-brown) | ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) ![Translation students](https://img.shields.io/badge/translation&nbsp;students-magenta) | :closed_book: |

- Towards a Framework for Machine Translation Literacy [[Bowker and Ciro, 2019]](https://www.emerald.com/books/monograph/10805/chapter-abstract/80421929/Towards-a-Framework-for-Machine-Translation?redirectedFrom=fulltext) ![Frameworks](https://img.shields.io/badge/frameworks-orange) ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) :white_circle:
- DataLitMT – teaching data literacy in the context of machine translation literacy [[Hackenbuchner and Krüger, 2023]](https://aclanthology.org/2023.eamt-1.28/) ![Frameworks](https://img.shields.io/badge/frameworks-orange) ![Learning](https://img.shields.io/badge/learning-brown) ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) ![Translation students](https://img.shields.io/badge/translation&nbsp;students-magenta) :closed_book:


## By Contexts

### :closed_book: Education

| Work | Work type(s) | User type(s) | Factor(s) |
| ---- | ------------ | ------------ | ---------- |
| DataLitMT – teaching data literacy in the context of machine translation literacy [[Hackenbuchner and Krüger, 2023]](https://aclanthology.org/2023.eamt-1.28/) | ![Frameworks](https://img.shields.io/badge/frameworks-orange) ![Learning](https://img.shields.io/badge/learning-brown) | ![Lay/generic](https://img.shields.io/badge/lay&#47;generic-grey) ![Translation students](https://img.shields.io/badge/translation&nbsp;students-magenta) | :book: |

### :hospital: Medical/health

### :white_circle: Generic/unspecified


## Related Surveys

- An Interdisciplinary Approach to Human-Centered Machine Translation [[Carpuat et al., 2025]](https://arxiv.org/abs/2506.13468)


🚧 **Coming soon!** This repository is under construction and will be populated shortly.