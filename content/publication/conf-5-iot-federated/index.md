---
title: "Handling Data Heterogeneity in Federated Learning via Knowledge Fusion"
authors:
- Xu Zhou
- Xinyu Lei
- Cong Yang
- Yichun Shi
- Xiao Zhang
- admin
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-09-27T00:00:00Z"
doi: "10.1109/JIOT.2023.3319986"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Internet of Things Journal "
publication_short: "JIOT"

abstract: Federated learning (FL) supports distributed training of a global machine learning model across multiple Internet of Things (IoT) devices with the help of a central server. However, data heterogeneity across different IoT devices leads to the client model drift issue and results in model performance degradation and poor model fairness. To address the issue, we design federated learning with global–local knowledge fusion (FedKF) scheme in this article. The key idea in FedKF is to let the server return the global knowledge to be fused with the local knowledge in each training round so that the local model can be regularized toward the global optima. Therefore, the client model drift issue can be mitigated. In FedKF, we first propose the active–inactive model aggregation technique that supports a precise global knowledge representation. Then, we propose a data-free knowledge distillation (KD) approach to enable each client model to learn the global knowledge (embedded in the global model) while each client model can still learn the local knowledge (embedded in the local data set) simultaneously, thereby realizing the global–local knowledge fusion process. The theoretical analysis and intensive experiments demonstrate the superiority of FedKF over previous solutions.

# Summary. An optional shortened abstract.
summary: FedKF addresses model drift in federated learning by fusing global and local knowledge during training, improving performance and fairness through techniques like active–inactive model aggregation and data-free knowledge distillation.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10265259
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
