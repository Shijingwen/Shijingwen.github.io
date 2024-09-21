---
title: "Taming the Insecurity of Cellular Emergency Services (9–1-1): From Vulnerabilities to Secure Designs"
authors:
  - Min-Yue Chen*
  - Yiwen Hu*
  - Guan-Hua Tu
  - Chi-Yu Li
  - Sihan Wang
  - admin
  - Tian Xie
  - Li Xiao
  - Chunyi Peng
  - Zhaowei Tan
  - Songwu Lu
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*JIEEE/ACM TRANSACTIONS ON NETWORKING"
publication_short: "TON"

abstract: Cellular networks, vital for delivering emergency services, enable mobile users to dial emergency calls (e.g., 9–1-1 in the U.S.), which are forwarded to public safety answer points (PSAPs). Regulatory requirements allow anonymous user equipment (UE) without a SIM card or valid mobile subscription to access these services. However, supporting emergency services for anonymous UEs introduces different operations, expanding the attack surface of cellular infrastructure. In this study, we explore the insecurity of cellular emergency services, identifying six security vulnerabilities. These vulnerabilities can be exploited for free data service attacks against carriers and data DoS/overcharge and denial of cellular emergency service (DoCES) attacks against mobile users. Experimental validation in networks of three major U.S. carriers and two major Taiwan carriers demonstrates the global impact of our findings. Finally, we propose and prototype standard-compliant remedies to mitigate these vulnerabilities.

# Summary. An optional shortened abstract.
summary: Cellular emergency services for anonymous users introduce vulnerabilities that allow free data, DoS, and denial of service attacks, validated in U.S. and Taiwan networks, with proposed standard-compliant remedies.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.computer.org/csdl/journal/nt/2024/04/10479537/1VCTwTN01OM
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