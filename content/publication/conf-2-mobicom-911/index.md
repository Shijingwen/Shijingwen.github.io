---
title: 'Uncovering insecure designs of cellular emergency services (911)'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yiwen Hu*
  - Min-Yue Chen*
  - Guan-Hua Tu
  - Chi-Yu Li
  - Sihan Wang
  - admin
  - Tian Xie
  - Li Xiao
  - Chunyi Peng
  - Zhaowei Tan
  - Songwu Lu

# Author notes (optional)
author_notes:
  - 'Yiwen Hu'
  - 'Min-Yue Chen'

date: '2022-10-14T00:00:00Z'
doi: '10.1145/3495243.3560534'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *MobiCom '22 Proceedings of the 28th Annual International Conference on Mobile Computing And Networking*
publication_short: In *MobiCom '22*

abstract: Cellular networks that offer ubiquitous connectivity have been the major medium for delivering emergency services. In the U.S., mobile users can dial an emergency call with 911 for emergency uses in cellular networks, and the call can be forwarded to public safety answer points (PSAPs), which deal with emergency service requests. According to regulatory authority requirements for the cellular emergency services, anonymous user equipment (UE), which does not have a SIM (Subscriber Identity Module) card or a valid mobile subscription, is allowed to access them. Such support of emergency services for anonymous UEs requires different operations from conventional cellular services, and can therefore increase the attack surface of the cellular infrastructure. In this work, we are thus motivated to study the insecurity of the cellular emergency services and then discover four security vulnerabilities from them. Threateningly, they can be exploited to launch not only free data service attacks against cellular carriers, but also data DoS/overcharge and denial of cellular emergency service (DoCES) attacks against mobile users. All vulnerabilities and attacks have been validated experimentally as practical security issues in the networks of three major U.S. carriers. We finally propose and prototype standard-compliant remedies to mitigate the vulnerabilities.

# Summary. An optional shortened abstract.
summary: Mobicom '22 - Cellular emergency services, especially for anonymous users, increase the attack surface, leading to vulnerabilities enabling free data usage, DoS, and denial of emergency services.

tags:
  - Mobile Security

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3495243.3560534'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Techsafety**](https://www.techsafety.org/blog/2016/8/25/need-to-call-911-theres-an-app-for-that)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
