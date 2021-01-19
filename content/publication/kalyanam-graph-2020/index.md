---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Graph search of a moving ground target by a UAV aided by ground sensors with
  local information
subtitle: ''
summary: ''
authors:
- Krishna Kalyanam
- David Casbeer
- Meir Pachter
tags: []
categories: []
date: '2020-05-01'
lastmod: 2021-01-18T16:57:39-05:00
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
publishDate: '2021-01-18T21:57:39.733925Z'
publication_types:
- '2'
abstract: The optimal control of a UAV searching for a target moving, with known constant
  speed, on a road network and heading toward one of many goal locations is considered.
  To aid the UAV, some roads in the network are instrumented with unattended ground
  sensors (UGSs) that detect the target’s motion and record the time it passes by
  the UGS. When the UAV flies over an UGS location, this time stamped information,
  if available, is communicated to it. At time 0, the target enters the road network
  and selects a path leading to one of the exit nodes. The UAV also arrives at the
  same entry UGS after some delay and is thus informed about the presence of the target
  in the network. The UAV has no on-board sensing capability and so, capture entails
  the UAV and target being colocated at an UGS location. If this happens, the UGS
  is triggered and this information is instantaneously relayed to the UAV, thereby
  enabling capture. On the other hand, if the target reaches an exit node without
  being captured, he is deemed to have escaped. We transform the road network, which
  is restricted to a directed acyclic graph, into a time tree whose node is a tuple
  comprising the UGS location and evader arrival time at that location. For a given
  initial delay, we present a recursive forward search method that computes the minimum
  capture time UAV pursuit policy, under worst-case target action. The recursion scales
  poorly in the problem parameters, i.e., number of nodes in the time tree and number
  of evader paths. We present a novel branch and bound technique and a pre-processing
  step that is experimentally shown to reduce the computational burden by at least
  two orders of magnitude. We illustrate the applicability of the proposed pruning
  methods, which result in no loss in optimality, on a realistic example road network.
publication: '*Autonomous Robots*'
url_pdf: https://doi.org/10.1007/s10514-019-09900-0
doi: 10.1007/s10514-019-09900-0
---
