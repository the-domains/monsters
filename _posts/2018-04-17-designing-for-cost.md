---
title: Design for Savings
datePublished: '2018-04-20T01:31:17.175Z'
dateModified: '2018-04-20T01:31:16.147Z'
publisher: {}
author: []
inFeed: true
hasPage: true
description: >-
  Success doesn’t have to be expensive. Upgrade your tech to reduce IT opex in
  the cloud with zero downtime because your product is too expensive to run and
  also too expensive to turn off.
via: {}
sourcePath: _posts/2018-04-17-designing-for-cost.md
starred: false
datePublishedOriginal: '2018-04-17T06:19:32.841Z'
url: designing-for-cost/index.html
_type: Article

---
# Design for Savings

## Case Study: Pawn Stars

Success doesn't have to be expensive. Upgrade your tech to reduce IT opex in the cloud with zero downtime because your product is too expensive to run and also too expensive to turn off.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/3cdf6f83-1992-4a5f-9fb8-d0b338b938f0.png)

---

When Fifth Column Games launched Pawn Stars, a companion game for the popular History Channel reality show, the success of their game led to millions of users with 24/7 in app purchases and $10k+ AWS hosting costs.

Migrating a 12GB Redis cluster in flight

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