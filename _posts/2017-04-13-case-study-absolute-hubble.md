---
inFeed: true
description: >-
  Out with the old and in with the new. There’s a simple rule of thumb for
  designing solutions to problems of scale.
dateModified: '2018-04-20T01:28:26.241Z'
datePublished: '2018-04-20T01:28:27.870Z'
title: Design for Scale
author: []
publisher: {}
via: {}
sourcePath: _posts/2017-04-13-case-study-absolute-hubble.md
hasPage: true
starred: false
datePublishedOriginal: '2018-04-13T20:39:20.064Z'
url: designing-for-scale/index.html
_type: Article

---
# Design for Scale

## Case Study: Absolute Hubble

Out with the old and in with the new. There's a simple rule of thumb for designing solutions to problems of scale.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/3d4b14a3-9fc6-49b1-8b90-2b76f260cca5.jpg)

---

Think about your file system. When you have 1 to 10 files to manage, the pattern is large icons, 10 to 1000 files, large icons can still work, however a list is usually better. When you start getting to 1000 to 10,000 a list is okay, however, search starts to become more important. As numbers are upwards of a million or a billion, AI may be appropriate.

What's the secret? For every order of magnitude, there is a different appropriate design solution.

I learned this firsthand at VMware, R&D User Experience, the company responsible for commercializing virtualization which is the foundation of cloud computing, and has led to a revolution in IT and business operations. Today, the infrastructure of modern clouds include many virtual object abstractions defined above the physical devices, such as CPUs, hard drives, and network devices. Each of these virtual devices provide compute, storage, and networking resources. Consider enterprise organizations such as hospitals and large businesses, governments---all customers of VMware---and the data centers that back them.

Just as the files you use have grown, the quantity of virtual objects to be managed has also grown. VMware some customers were managing upwards of 10,000 virtual objects. Absolute Hubble, as in the Hubble space telescope was a project that explored design patterns for managing such complexity. The intention was to help datacenter administrators quickly understand---and troubleshoot---the relationships between the virtual objects they manage.
![Absolute Hubble simplifies troubleshooting workflows by traversing and visualizing the relationships between virtual objects in a datacenter. This interface combines design patterns for managing scale including elastic lists, search, and consolidated nodes. Furthermore, this interface is focused upon monitoring unhealthy trends, which administrators are most concerned with provide the highest level of service to their business. ](https://the-grid-user-content.s3-us-west-2.amazonaws.com/caca9843-cc94-4aa7-977e-74bc76505e0e.jpg)

Absolute Hubble simplifies troubleshooting workflows by traversing and visualizing the relationships between virtual objects in a datacenter. This interface combines design patterns for managing scale including elastic lists, search, and consolidated nodes. Furthermore, this interface is focused upon monitoring unhealthy trends, which administrators are most concerned with provide the highest level of service to their business.

I'm curious to hear about the design challenges you currently face. Reach out below and I'd be happy to schedule a time to chat and learn more.
[Say hello][0]

I **♥ **complexity.

[0]: http://tiny.cc/hello-daniel