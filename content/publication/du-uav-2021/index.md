---
# Documentation: https://wowchemy.com/docs/managing-content/

title: UAV Trajectory Planning with Probabilistic Geo-Fence via Iterative Chance-Constrained
  Optimization
subtitle: ''
summary: ''
authors:
- Bin Du
- Jun Chen
- Dengfeng Sun
- Satyanarayana Manyam
- David w. Casbeer
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-01-19T22:34:02-05:00
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
publishDate: '2021-01-20T03:34:01.985831Z'
publication_types:
- '2'
abstract: Chance-constrained optimization provides a promising framework for solving
  control and planning problems with uncertainties, due to its modeling capability
  to capture randomness in real-world applications. In this paper, we consider a UAV
  trajectory planning problem with probabilistic geo-fence, building on the chance-constrained
  optimization approach. In the considered problem, randomness of the model, such
  as the uncertain boundaries of geo-fences, is incorporated in the formulation. By
  solving the formulated chance-constrained optimization with a novel sampling based
  solution method, the optimal UAV trajectory is achieved while limiting the probability
  of collision with geo-fences to a prefixed threshold. Furthermore, to obtain a totally
  collision-free trajectory, i.e., avoiding the collision not only at the discrete
  time-steps but also red within the entire time horizon, we build on the idea of an
  iterative scheme. That is, to iterate the solving of the chance-constrained optimization
  until the collision with probabilistic geo-fence is avoided at any time within the
  time horizon. At last, we validate the effectiveness of our method via numerical
  simulations.
publication: '*IEEE Transactions on Intelligent Transportation Systems* (Accepted, January 2021)'
---
