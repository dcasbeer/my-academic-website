---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Pursuit of a moving target with bounded speed on a directed acyclic graph under
  partial information
subtitle: ''
summary: ''
authors:
- Krishnamoorthy Kalyanam
- David Casbeer
- Meir Pachter
tags: []
categories: []
date: '2016-11-01'
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
publishDate: '2021-01-18T21:57:42.865333Z'
publication_types:
- '2'
abstract: The optimal control of a ‘blind’ airborne pursuer searching for an evader
  moving on a road network with positive bounded speed toward a set of goal vertices
  is considered. To aid the pursuer and provide feedback information, certain roads
  in the network have been instrumented with unattended ground sensors (UGSs) that
  detect evader motion. When the pursuer arrives at an instrumented node, the UGS
  therein informs the pursuer if and when the evader visited the node. The pursuer
  is aware of the bounds on the evader’s speed. Moreover, the embedded graph with
  the UGSs as vertices and connecting roads as edges is restricted to be a directed
  acyclic graph (DAG). At time $0$, the evader’s entry into the road network is registered
  at UGS $1$, the entry node. The pursuer also arrives at the entry node after some
  delay $d&gt;0$ and is thus informed about the presence of the intruder/evader in
  the network, whereupon the chase is on. Capture entails the pursuer and evader being
  co-located at an UGS location. However, if the evader reaches an exit node of the
  graph without being captured, it is deemed to have escaped. We compute the maximum
  initial delay $d$ and the ensuing pursuit policy, for which capture is guaranteed.
publication: '*IMA Journal of Mathematical Control and Information*'
url_pdf: https://doi.org/10.1093/imamci/dnw061
doi: 10.1093/imamci/dnw061
---
