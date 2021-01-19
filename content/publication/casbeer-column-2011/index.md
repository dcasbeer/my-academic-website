---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Column generation for a UAV assignment problem with precedence constraints
subtitle: ''
summary: ''
authors:
- David W Casbeer
- Raymond W Holsapple
tags: []
categories: []
date: '2011-08-01'
lastmod: 2021-01-18T16:57:36-05:00
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
publishDate: '2021-01-18T21:57:36.552794Z'
publication_types:
- '2'
abstract: We apply column generation with branch-and-price optimization to a multi-target,
  multi-task assignment problem, with precedence constraints. Column generation transforms
  the nonlinear program with separable costs and constraints into a linear program.
  This reformulation divides the original problem into a number of smaller problems,
  where one of these smaller problems accounts for the coupling constraints between
  agents and must be known by every agent. All other divisions consider local constraints
  affecting only one agent; these smaller problems are known by only one corresponding
  agent. Because of this reformulation, the assignment problem can be solved in a
  distributed manner. A theorem is proven which details the central analytical result
  of the paper, allowing a nonlinear program to be reformulated as a linear program.
  Simulation results for a multi-target, single-task assignment problem, as well as
  a multi-target, multi-task assignment problem with precedence constraints are presented.
  Published 2011. This article is a US Government work and is in the public domain
  in the USA.
publication: '*International Journal of Robust and Nonlinear Control*'
doi: https://doi-org.wrs.idm.oclc.org/10.1002/rnc.1722
---
