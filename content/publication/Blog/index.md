---
title: "Backdoor Attack against Log Anomaly Detection Models (Blog)"

authors:
  - admin
  - Depeng Xu
  - Shuhan Yuan

author_notes: []

date: '2025-04-25T00:00:00Z'
publishDate: '2025-04-25T00:00:00Z'

publication_types: ['paper-conference']

publication: In *Companion Proceedings of the ACM Web Conference 2025*
publication_short: In *WWW 2025*

abstract: |
  We propose **Blog**, a backdoor attack framework targeting log anomaly detection models. Blog embeds carefully crafted triggers into training logs, enabling adversaries to manipulate model predictions at inference while preserving benign performance. Experiments reveal that state-of-the-art log anomaly detection systems are highly vulnerable to this attack, underscoring the need for more robust defenses.

summary: "Blog demonstrates how backdoor attacks compromise log anomaly detection models, highlighting vulnerabilities in widely used systems."

tags:
  - Anomaly Detection
  - Backdoor Attacks
  - Log Data

featured: true

hugoblox:
  ids:
    doi: 10.1145/3701716.3715533

links:
  - type: pdf
    url: "https://dl.acm.org/doi/10.1145/3701716.3715533"

image:
  caption: "Blog framework illustration"
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to import the citation into your reference manager.
{{% /callout %}}

---

### Citation

```bibtex
@inproceedings{cheng2025blog,
  title     = {Backdoor Attack against Log Anomaly Detection Models},
  author    = {Cheng, He and Xu, Depeng and Yuan, Shuhan},
  booktitle = {Companion Proceedings of the ACM Web Conference 2025},
  pages     = {915--918},
  publisher = {ACM},
  year      = {2025},
  doi       = {10.1145/3701716.3715533}
}
