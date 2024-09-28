---
title: "An improved LOS Guidance and Sail-Rudder Cooperative Controller for the Path Tracking of Unmanned Sailboats"
authors:
- Hongde Qin
- Peilong Xu
- admin
- Yifan Xue
date: "2024-04-10T00:00:00Z"
doi: "10.1109/TIV.2024.3386964"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Unmanned sailboats are driven only by wind, making them good platforms for the synchronous observation of air-sea interfaces over a large range. Compared with traditional unmanned ships, the unmanned sailboat involves simultaneous sail and rudder control for path tracking in unpredictable marine environments. The system is characterized by strong coupling and nonlinearity, creating challenges for the design of controllers. This paper combines line-of-sight (LOS) guidance with the introduction of a sideslip angle observer and model predictive control. A high-precision path tracking strategy suitable for cooperative sail and rudder control for unmanned sailboats is proposed. First, considering the lateral error easily caused by the large sideslip angle of sailboats, a full-path fixed-time guidance strategy with double fixed-time sideslip angle observers (DFSO) is proposed. Second, different from the previous strategy of decoupling the sail and rudder to control the speed and heading, the proposed cooperative control framework uses Lyapunov-based model predictive control (LMPC). The sailing speed and heading angle are both accounted for in the objective function, and the stability is verified by Lyapunov theory. Finally, the feasibility and superiority of this proposed method are confirmed by numerical simulation experiments involving the path tracking of a four degree of freedom sailboat model integrated with wind and waves in an ocean environment. IEEE

# Summary. An optional shortened abstract.
summary: 

tags: []
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10496218
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
slides: ""
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
