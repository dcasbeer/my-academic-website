---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A sequential partial information bomber-defender shooting problem
subtitle: ''
summary: ''
authors:
- Krishnamoorthy Kalyanam
- David Casbeer
- Meir Pachter
tags: []
categories: []
date: '2020-01-01'
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
publishDate: '2021-01-18T21:57:39.568231Z'
publication_types:
- '2'
abstract: A bomber carrying homogenous weapons sequentially engages ground targets
  capable of retaliation. Upon reaching a target, the bomber may fire a weapon at
  it. If the target survives the direct fire, it can either return fire or choose
  to hold fire (play dead). If the former occurs, the bomber is immediately made aware
  that the target is alive. If no return fire is seen, the true status of the target
  is unknown to the bomber. After the current engagement, the bomber, if still alive,
  can either re‐engage the same target or move on to the next target in the sequence.
  The bomber seeks to maximize the expected cumulative damage it can inflict on the
  targets. We solve the perfect and partial information problems, where a target always
  fires back and sometimes fires back respectively using stochastic dynamic programming.
  The perfect information scenario yields an appealing threshold based bombing policy.
  Indeed, the marginal future reward is the threshold at which the control policy
  switches and furthermore, the threshold is monotonic decreasing with the number
  of weapons left with the bomber and monotonic nondecreasing with the number of targets
  left in the mission. For the partial information scenario, we show via a counterexample
  that the marginal future reward is not the threshold at which the control switches.
  In light of the negative result, we provide an appealing threshold based heuristic
  instead. Finally, we address the partial information game, where the target can
  choose to fire back and establish the Nash equilibrium strategies for a representative
  two target scenario.
publication: '*Naval Research Logistics (NRL)*'
url_pdf: https://onlinelibrary-wiley-com.wrs.idm.oclc.org/doi/full/10.1002/nav.21892
doi: 10.1002/nav.21892
---
