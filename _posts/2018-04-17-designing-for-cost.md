---
title: Design for Compute
datePublished: '2018-04-28T05:31:43.928Z'
dateModified: '2018-04-28T05:31:43.137Z'
publisher: {}
author: []
inFeed: true
hasPage: true
description: >-
  Success doesn’t have to be expensive. Upgrade your tech and reduce IT opex in
  the cloud with zero downtime because your product is too expensive to run and
  also too expensive to turn off.
via: {}
sourcePath: _posts/2018-04-17-designing-for-cost.md
starred: false
datePublishedOriginal: '2018-04-28T05:28:25.640Z'
url: design-for-savings/index.html
_type: Article

---
# Design for Compute

## Case Study: Pawn Stars

Success doesn't have to be expensive. Upgrade your tech and reduce IT opex in the cloud with zero downtime because your product is too expensive to run and also too expensive to turn off.
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