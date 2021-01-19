---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Lower Bounding Linear Program for the Perimeter Patrol Optimization Problem
subtitle: ''
summary: ''
authors:
- Krishnamoorthy Kalyanam
- Myoungkuk Park
- Swaroop Darbha
- David Casbeer
- Phil Chandler
- Meir Pachter
tags: []
categories: []
date: '2014-02-01'
lastmod: 2021-01-18T16:57:44-05:00
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
publishDate: '2021-01-18T21:57:44.345477Z'
publication_types:
- '2'
abstract: In this article, a stochastic optimal control problem involving an unmanned
  aerial vehicle flying patrols around a perimeter is considered. To determine the
  optimal control policy, one has to solve a Markov decision problem, whose large
  size renders exact dynamic programming methods intractable. Therefore, a state aggregation
  based approximate linear programming method is used instead, to construct provably
  good suboptimal patrol policies. The state space is partitioned and the optimal
  cost-to-go or value function is restricted to be a constant over each partition.
  The resulting restricted system of linear inequalities embeds a family of Markov
  chains of lower dimension, one of which can be used to construct a lower bound on
  the optimal value function. In general, the construction of a lower bound requires
  the solution to a combinatorial problem. But the perimeter patrol problem exhibits
  a special structure that enables tractable linear programming formulation for the
  lower bound. This is demonstrated and numerical results that corroborate the efficacy
  of the proposed methodology are also provided.
publication: '*Journal of Guidance, Control, and Dynamics*'
url_pdf: https://arc.aiaa.org/doi/10.2514/1.60487
doi: 10.2514/1.60487
---
