---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Pursuit of a Moving Target with Known Constant Speed on a Directed Acyclic
  Graph under Partial Information
subtitle: ''
summary: ''
authors:
- Krishnamoorthy Kalyanam
- David W. Casbeer
- Meir Pachter
tags: []
categories: []
date: '2016-01-01'
lastmod: 2021-01-18T16:57:43-05:00
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
publishDate: '2021-01-18T21:57:43.026954Z'
publication_types:
- '2'
abstract: We consider the optimal control of a “blind” pursuer searching for an evader
  moving on a road network with fixed speed toward a set of goal locations. To aid
  the pursuer and provide feedback information, certain roads in the network have
  been instrumented with unattended ground sensors (UGSs) that detect the evader's
  motion. When the pursuer arrives at an instrumented node, the UGS therein informs
  the pursuer whether and when the evader visited that node. The pursuer is also made
  aware of the evader's speed. Moreover, the embedded graph comprised of the UGSs
  as vertices and connecting roads as edges is restricted to being a directed acyclic
  graph (DAG). The pursuer's motion is not restricted to the road network. In addition,
  the pursuer can choose to wait/loiter for an arbitrary time at any UGS location/node.
  At time 0, the evader's entry into the road network is registered at UGS 1, the
  entry node to the graph. The pursuer also arrives at the entry node after some delay
  $d$ and is thus informed about the presence of the intruder/evader in the network,
  whereupon the chase is on---the pursuer is tasked with capturing the evader. Capture
  entails the pursuer and evader being co-located at an UGS location. If this happens,
  the UGS is triggered, and this information is instantaneously relayed to the pursuer,
  thereby enabling capture. On the other hand, if the evader reaches one of the exit
  nodes of the graph without being captured, he is deemed to have escaped. We provide
  an algorithm that computes the maximum initial delay $d$ for which capture is guaranteed.
  The algorithm also returns the corresponding optimal pursuit policy.
publication: '*SIAM Journal on Control and Optimization*'
url_pdf: https://epubs-siam-org.wrs.idm.oclc.org/doi/10.1137/140994216
doi: 10.1137/140994216
---
