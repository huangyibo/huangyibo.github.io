---
title: "Towards Fully Disaggregated Recommendation Model Serving"
collection: publications
permalink: /publication/2025-08-08-paper-flexemr
excerpt: '<u><b>Yibo Huang</b></u>, Yiming Qiu, Zhenning Yang, Yi Dai, Dingming Wu, Fan Lai, Jiarong Xing, Ang Chen'
date: 2025-10-12
venue: '16th ACM SIGOPS Asia-Pacific Workshop on Systems (APSys 2025)'
venuename: 'ACM APSys 2025'
paperurl: 'https://dl.acm.org/doi/10.1145/3725783.3764389'
codestar: '<a class="github-button" href="https://github.com/huangyibo/SnowRDMA" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-show-count="true" aria-label="Star huangyibo/SnowRDMA on GitHub">Star</a>'
codeurl: https://github.com/huangyibo/SnowRDMA
---

**Citation:**

```bib
@inproceedings{10.1145/3725783.3764389,
author = {Huang, Yibo and Qiu, Yiming and Yang, Zhenning and Dai, Yi and Wu, Dingming and Lai, Fan and Xing, Jiarong and Chen, Ang},
title = {Towards Fully Disaggregated Recommendation Model Serving},
year = {2025},
isbn = {9798400715723},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3725783.3764389},
doi = {10.1145/3725783.3764389},
abstract = {Serving embedding-based recommendation (EMR) models requires a mix of GPUs, CPUs, and DRAM. Current systems typically provision these resources on monolithic servers with a fixed ratio across resource types, leading to inefficient resource utilization and inflated operational costs. To solve this problem, we propose FlexEMR, a system architecture that fully disaggregates these resources, and interconnects them via an optimized RDMA network. This design enables independent scaling of resources, enhances failure isolation, improves overall resource efficiency, and reduces operational costs. We achieve this by introducing two classes of techniques to address the networking challenges introduced by disaggregation: (1) optimizing embedding lookup communication by leveraging workload locality, and (2) improving network transport through a high-performance, multithreaded RDMA engine. We detail our design considerations and share early performance insights, highlighting the potential of FlexEMR for enabling fully disaggregated EMR model serving.},
booktitle = {Proceedings of the 16th ACM SIGOPS Asia-Pacific Workshop on Systems},
pages = {38–45},
numpages = {8},
keywords = {deep learning recommendation models, AI inference systems, disaggregation, RDMA, hardware-software co-design},
location = {Lotte Hotel World, Emerald Hall, Seoul, Republic of Korea},
series = {APSys '25}
}
```
