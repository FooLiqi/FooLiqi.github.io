---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Miniature Autonomous Blimp"
summary: ""
authors: []
tags: []
categories: []
date: 2024-09-30T18:17:47+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

With advancements in drone technology, aerial robots are increasingly being used in indoor applications such as surveillance and inspection. However, most existing aerial platforms, like quadcopters, still face challenges with safety and endurance during human interaction. To address these issues, we have developed a Miniature Autonomous Blimp that meets indoor safety requirements while offering significantly longer flight times.



<!--more-->

### Research Progress
In our previous work, we decomposed autonomous flight into a series of motion primitives. However, due to the high coupling between lateral and longitudinal movements with pitch and roll motions, undesirable oscillations were often observed. These oscillations resulted in inaccurate sensor readings, unstable video streams from onboard cameras, and a less comfortable human-robot interaction experience. To improve flight behavior and enhance the human-robot interaction experience, we established a six-degree-of-freedom (6-DOF) motion model and identified parameters related to three degrees of freedom (3-DOF) in a vertical plane. A flight controller was developed to enable constant forward and sideways velocity with reduced oscillation.

### Future Plans
Looking ahead, we plan to identify a full dynamic motion model for the blimp and update the flight controller to further enhance flight stability and precision.
Key Features and Advantages
1.	Safe Human-Robot Interaction
Traditional unmanned aerial vehicles (UAVs) require protective covers when flying indoors to prevent harm from high-speed propellers. They typically need safety nets or at least a 1-meter distance between the UAV and humans. In contrast, our blimp is equipped with a soft balloon that poses no risk to humans, even at close proximity, allowing for safe flight near people.
2.	Extended Flight Duration
Quadcopters rely on high-speed rotating propellers to generate enough lift for hovering, which results in high power consumption. In comparison, the blimp’s balloon provides enough buoyancy for hovering. Despite having a battery capacity of only 450mAh (approximately 1/10th of traditional UAV batteries), our blimp can operate for over 45 minutes, whereas regular UAVs typically fly for about 30 minutes.
3.	Expansion into Marine Research
Conducting experiments with underwater robots in the ocean is costly and involves complex setups. However, our blimp exhibits similar fluid dynamics in the air as underwater robots do in water. This makes it a useful simulator for testing underwater robot algorithms, greatly reducing the cost and complexity of experiments for scientific research.
