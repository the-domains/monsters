---
inFeed: true
description: >-
  Migrating a 12GB database in flight because your product is too expensive run
  and too expensive to turn off. 
dateModified: '2018-04-17T06:27:41.653Z'
datePublished: '2018-04-17T06:27:42.717Z'
title: Designing for Cost
author: []
publisher: {}
via: {}
hasPage: true
sourcePath: _posts/2018-04-17-designing-for-cost.md
starred: false
datePublishedOriginal: '2018-04-17T06:19:32.841Z'
url: designing-for-cost/index.html
_type: Article

---
# Designing for Cost

## Case Study: Pawn Stars

Migrating a 12GB database in flight because your product is too expensive run and too expensive to turn off. ![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/3cdf6f83-1992-4a5f-9fb8-d0b338b938f0.png)

---

TBWritten

* Popular game 10k/month to run
* Redis cluster many many GB
* Pawnstars, History Channel 
* Zero downtime or players will be unhappy and sales lost
* Redis is in memory and to turn it off means to lose all memory 
* Moving many GB is slow
* transfer to new hardware options (cheaper) at aws with zero downtime
* Coordinate without failure
* From complex to easy.
[Say hello][0]

**I ♥ complexity**

[0]: http://tiny.cc/hello-daniel