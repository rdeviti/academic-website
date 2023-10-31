---
title: CoVault - A Secure Analytics Platform

#event: MIT CSAIL Security Seminar
#event_url: http://css.csail.mit.edu/security-seminar/details.html#Jun2823

locations: 
- location: (upcoming) University of Oxford, Oxford, UK
  date: '2023-11-16'
- location: (upcoming) Imperial College London, London, UK
  date: '2023-11-13'
- location: Harvard University, Cambridge, MA, US
  date: '2023-07-05'
- location: Brown University, Providence, RI, US
  date: '2023-06-30'
- location: MIT CSAIL Security Seminar @ MIT, Cambridge, MA, US
  date: '2023-06-28'
- location: Northeastern University, Boston, MA, US
  date: '2023-06-26'
- location: ETH Zürich, Zürich, CH
  date: '2022-09-22'

#address:
#  street: 32 Vassar Street
#  city: Cambridge
#  region: MA
#  postcode: '02139'
#  country: United States

summary: 
abstract: 'Many types of analytics on personal data can be made differentially private, thus alleviating concerns about the privacy of individuals. However, no analytics platform currently exists that can technically prevent data leakage and misuse with minimal trust assumptions; as a result, analytics that would be in the public interest are not done in privacy-conscious societies. To bridge this gap, we present secure selective analytics (SSA), where data sources can a priori restrict the use of their data to a pre-defined set of privacy-preserving analytics queries performed by a specific group of analysts, and for a limited period. Furthermore, we show that a scalable SSA platform can be built in a strong threat model based on minimal trust.
In this talk, I will present CoVault, an SSA platform that relies on a minimal trust implementation of functional encryption (FE), using a combination of secret sharing, secure multi-party computation (MPC), and trusted execution environments (TEEs). CoVault tolerates the compromise of a subset of TEE implementations as well as side channels. Despite the high cost of MPC, we show that ConSeal scales to very large databases using MapReduce-based query parallelization.'

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with `#`.
date: '2023-06-28T16:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
# all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: link
    icon_pack: fa
    name: Details
    url: http://css.csail.mit.edu/security-seminar/details.html#Jun2823
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#  - example
---
