---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Intruder Isolation on a General Road Network Under Partial Information
subtitle: ''
summary: ''
authors:
- H. Chen
- K. Kalyanam
- W. Zhang
- D. Casbeer
tags:
- '"aerospace control"'
- '"autonomous aerial vehicles"'
- '"computational complexity"'
- '"continuous movement"'
- '"decision tree"'
- '"decision trees"'
- '"Decision trees"'
- '"DP"'
- '"dynamic programming"'
- '"Dynamic programming"'
- '"Dynamic programming (DP)"'
- '"game theory"'
- '"Games"'
- '"general road network"'
- '"IIP"'
- '"intruder isolation problem"'
- '"intruder location"'
- '"isolation problem"'
- '"mobile robots"'
- '"numerical analysis"'
- '"numerical implementations"'
- '"optimal control"'
- '"Optimal control"'
- '"partial information"'
- '"passing intruder"'
- '"pursuit evasion (PE)"'
- '"Roads"'
- '"Search problems"'
- '"telerobotics"'
- '"UAV"'
- '"UGS ranking scheme"'
- '"UGSs"'
- '"unattended ground sensors"'
- '"unmanned aerial vehicle"'
- '"unmanned aerial vehicle (UAV)"'
- '"Unmanned aerial vehicles"'
categories: []
date: '2017-01-01'
lastmod: 2021-01-18T16:57:42-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-01-18T21:57:42.700685Z'
publication_types:
- '2'
abstract: The intruder isolation problem (IIP) involves using an unmanned aerial vehicle
  (UAV) to isolate an intruder traveling along a road network. The UAV has no visibility
  of the intruder and can obtain the information only about the intruder's location
  from unattended ground sensors (UGSs) preinstalled on the road network. An UGS detects
  a passing intruder and records the time of passage. It can also upload the time-stamped
  information to the UAV directly overhead. This paper focuses on finding the optimal
  sequence of UGSs for the UAV to visit and the corresponding waiting time around
  each UGS to achieve isolation for the two variants of the IIP. This task is challenging
  due to the continuous movement of the intruder along the road network and the partial
  information scenario. To address these challenges, we propose an unfolding strategy
  to transform the road network to a decision tree, which describes all possible routes
  that the intruder may select to follow. Based on the decision tree, the optimal
  solution to the isolation problem is computed via dynamic programming (DP). To alleviate
  the computational complexity of DP, an UGS ranking scheme is proposed. Numerical
  implementations based on a real road network are presented to demonstrate the effectiveness
  of the proposed solution approach.
publication: '*IEEE Transactions on Control Systems Technology*'
doi: 10.1109/TCST.2016.2550423
---
