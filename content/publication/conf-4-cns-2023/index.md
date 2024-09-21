---
title: "When Good Turns Evil: Encrypted 5G/4G Voice Calls Can Leak Your Identities"
authors:
  - admin
  - Tian Xie
  - Guan-Hua Tu
  - Chunyi Peng
  - Chi-Yu Li
  - Andrew Hou
  - Sihan Wang
  - Yiwen Hu
  - Min-Yue Chen
  - Li Xiao
  - Xiaoming Liu
  
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-10-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "2023 IEEE Conference on Communications and Network Security"
publication_short: "CNS '23"

abstract: 5G/4G voice calls are always encrypted for security and privacy. However, in this work, we unveil several vulnerabilities which can unintentionally leak 5G/4G call state information, despite encryption protection. They stem from recent call optimization techniques standardized in the 3GPP specifications and adopted by mobile network operators. While these techniques are effective to enhance 5G/4G call quality and efficiency, they unfortunately expose extra call information, which can be exploited to precisely infer call states and launch side-channel attacks. By leveraging precise call states, we devise a Cross-domain Identity Linkage attack, CrossIL, which aims to infer mobile users’ user identities and cellular identities, thereby enabling powerful cyberattacks or privacy inferences against high-value victims. We have experimentally validated these vulnerabilities and assessed the attack damages with three major U.S. carriers. Our experimental result shows that the success rate on the identity inference ranges from 89\% to 98\%. Finally, we propose and evaluate a cellular-friendly solution.

# Summary. An optional shortened abstract.
summary: This study uncovers vulnerabilities in 5G/4G call optimization techniques that, despite encryption, can leak call state information, enabling side-channel attacks like Cross-domain Identity Linkage (CrossIL) with identity inference success rates of up to 98\%.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10288900/
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