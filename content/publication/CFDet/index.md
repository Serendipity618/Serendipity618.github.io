---
title: "Achieving Counterfactual Explanation for Sequence Anomaly Detection"

authors:
  - admin
  - Depeng Xu
  - Shuhan Yuan
  - Xintao Wu

date: "2024-08-22T00:00:00Z"
publishDate: "2024-08-22T00:00:00Z"

publication_types: ["paper-conference"]

publication: "In *European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML PKDD 2024)*"
publication_short: "In *ECML PKDD*"

abstract: |
  We propose **CFDet**, a counterfactual explanation framework for sequence anomaly detection. CFDet identifies anomalous entries by generating minimal and plausible modifications that alter a model’s prediction from anomalous to normal. Experiments on BGL, Thunderbird, and CERT datasets demonstrate that CFDet produces high-fidelity explanations and consistently outperforms attention-based, Shapley value, and gradient-based baselines.

summary: "Counterfactual explanations for sequence anomaly detection, providing interpretable insights."

tags:
  - Anomaly Detection
  - Counterfactual Explanation
  - Sequence Modeling

featured: true

hugoblox:
  ids:
    doi: "https://link.springer.com/chapter/10.1007/978-3-031-70371-3_2"

links:
  - type: pdf
    url: "https://par.nsf.gov/servlets/purl/10579795"
  - type: code
    url: "https://github.com/Serendipity618/CFDet"

image:
  caption: "CFDet framework illustration"
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---

### Citation

```bibtex
@inproceedings{cheng2024cfdet,
  title     = {Achieving Counterfactual Explanation for Sequence Anomaly Detection},
  author    = {Cheng, He and Xu, Depeng and Yuan, Shuhan and Wu, Xintao},
  booktitle = {Machine Learning and Knowledge Discovery in Databases. Research Track (ECML PKDD 2024)},
  series    = {Lecture Notes in Artificial Intelligence},
  volume    = {14948},
  pages     = {19--35},
  publisher = {Springer},
  year      = {2024},
  doi       = {10.1007/978-3-031-70371-3_2}
}
