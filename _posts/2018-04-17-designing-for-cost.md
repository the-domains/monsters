---
title: Design for Compute
datePublished: '2018-04-28T18:41:49.519Z'
dateModified: '2018-04-28T18:41:49.167Z'
publisher: {}
author: []
inFeed: false
hasPage: true
description: >-
  Success can be expensive. What happens when IT operating expenses are too
  expensive to run yet too expensive to turn off.
via: {}
sourcePath: _posts/2018-04-17-designing-for-cost.md
starred: false
datePublishedOriginal: '2018-04-28T05:28:25.640Z'
url: design-for-savings/index.html
_type: Blurb

---
# Design for Compute

## Case Study: Pawn Stars

Success can be expensive. What happens when IT operating expenses are too expensive to run yet too expensive to turn off.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/3cdf6f83-1992-4a5f-9fb8-d0b338b938f0.png)

---

When Fifth Column Games launched Pawn Stars, a companion game for the popular History Channel reality show, the success of their game led to millions of users with 24/7 in-app purchases and $10k+ AWS hosting costs.

Migrating a 12GB Redis cluster in flight with 0 down time? Festina lente.

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