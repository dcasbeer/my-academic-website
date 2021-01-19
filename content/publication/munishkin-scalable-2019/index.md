---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Scalable Markov chain approximation for a safe intercept navigation in the
  presence of multiple vehicles
subtitle: ''
summary: ''
authors:
- Alexey A. Munishkin
- Araz Hashemi
- David W. Casbeer
- Dejan Milutinović
tags: []
categories: []
date: '2019-03-01'
lastmod: 2021-01-18T16:57:38-05:00
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
publishDate: '2021-01-18T21:57:38.415920Z'
publication_types:
- '2'
abstract: This paper studies a safe intercept navigation which accounts for the uncertainty
  of other vehicles’ trajectories, avoids collisions and any other positions in which
  vehicle safety is compromised. Since the number of vehicles can vary with time,
  it is important that the navigation strategy can quickly adjust to the current number
  of vehicles, i.e, that it scales well with the number of vehicles. The scalable
  strategy is based on a stochastic optimal control problem formulation of safe navigation
  in the presence of a single vehicle, denoted as the one-on-one vehicle problem.
  It is shown that safe navigation in the presence of multiple vehicles can be solved
  exactly as an auxiliary Markov decision problem. This allows us to approximate the
  solution based on the one-on-one vehicle optimal control solution and achieve scalable
  navigation. Our work is illustrated by a numerical example of safely navigating
  a vehicle in the presence of four other vehicles and by a robot experiment.
publication: '*Autonomous Robots*'
url_pdf: https://doi.org/10.1007/s10514-018-9739-0
doi: 10.1007/s10514-018-9739-0
---
