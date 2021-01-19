---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Tightly Bounding the Shortest Dubins Paths Through a Sequence of Points
subtitle: ''
summary: ''
authors:
- Satyanarayana G. Manyam
- Sivakumar Rathinam
- David Casbeer
- Eloy Garcia
tags: []
categories: []
date: '2017-12-01'
lastmod: 2021-01-18T16:57:41-05:00
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
publishDate: '2021-01-18T21:57:41.702010Z'
publication_types:
- '2'
abstract: This article addresses an important path planning problem for robots and
  Unmanned Aerial Vehicles (UAVs), which is to find the shortest path of bounded curvature
  passing through a given sequence of target points on a ground plane. Currently,
  no algorithm exists that can compute an optimal solution to this problem. Therefore,
  tight lower bounds are vital in determining the quality of any feasible solution
  to this problem. Novel tight lower bounding algorithms are presented in this article
  by relaxing some of the heading angle constraints at the target points. The proposed
  approach requires us to solve variants of an optimization problem called the Dubins
  interval problem between two points where the heading angles at the points are constrained
  to be within a specified interval. These variants are solved using tools from optimal
  control theory. Using these approaches, two lower bounding algorithms are presented
  and these bounds are then compared with existing results in the literature. Computational
  results are presented to corroborate the performance of the proposed algorithms;
  the average reduction in the difference between upper bounds and lower bounds is
  80 % to 85 % with respect to the trivial Euclidean lower bounds.
publication: '*Journal of Intelligent & Robotic Systems*'
url_pdf: https://doi.org/10.1007/s10846-016-0459-4
doi: 10.1007/s10846-016-0459-4
---
