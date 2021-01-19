---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Min–max time efficient inspection of ground vehicles by a UAV team
subtitle: ''
summary: ''
authors:
- Alexey A. Munishkin
- Dejan Milutinović
- David W. Casbeer
tags: []
categories: []
date: '2020-03-01'
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
publishDate: '2021-01-18T21:57:38.254108Z'
publication_types:
- '2'
abstract: We present a control design for N unmanned aerial vehicles (UAVs) tasked
  with an inspection of M ground moving vehicles. The location of each ground vehicle
  is known to each UAV, but the navigation and intent of each ground vehicle are unknown,
  therefore, this uncertainty has to be anticipated in each UAV’s navigation. We use
  the minimum time stochastic optimal control to navigate each UAV towards the inspection
  of each ground vehicle. Based on this control, we formulate assignments of ground
  vehicles to be inspected by UAVs as an optimization problem to inspect all ground
  vehicles in the minimum expected time. Accounting for ground vehicle uncertain trajectories,
  we update the optimal assignment by a Markov inequality rule. The rule prevents
  the possibility of indefinite updating of assignments without finishing the inspection
  of all vehicles. On the other hand, it updates an assignment if it leads to a statistically
  significant improvement of the inspection expected time. The presented approach
  is illustrated with numerical examples.
publication: '*Robotics and Autonomous Systems*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0921889019301952
doi: 10.1016/j.robot.2019.103370
---
