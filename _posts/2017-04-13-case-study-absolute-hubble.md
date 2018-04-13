---
inFeed: true
description: There’s a rule of thumb I keep in mind when I approach a design problem.
dateModified: '2018-04-13T20:57:41.637Z'
datePublished: '2018-04-13T20:57:42.375Z'
title: Designing for Scale
author: []
publisher: {}
via: {}
sourcePath: _posts/2017-04-13-case-study-absolute-hubble.md
starred: false
datePublishedOriginal: '2018-04-13T20:39:20.064Z'
_type: Blurb

---
# Designing for Scale

## Case Study: Absolute Hubble

There's a rule of thumb I keep in mind when I approach a design problem.

> Every order of magnitude of object quantity has a different solution space. 

Think about your file system. When you have 1 to 10 files to manage, the pattern is large icons, 10 to 1000 files, large icons can still work, however a list is usually better. When you start getting to 1000 to 10,000 a list is okay, however, search starts to become more important. You get the picture. 

I learned this firsthand with customers who operate data centers for their organizations. IT has seen a huge change over the past decade and with virtual machines the management complexity grow. Consider enterprise organizations such as hospitals and large businesses, governments and the data centers that back them. Operating such organizations might include petabytes of storage and trillions of files.

I learned this first hand at VMware, R&D User Experience. VMware is responsible for revolutionizing IT by bringing virtualization to the consumer market. Virtualization was invented by IBM in the late 60's and is the foundation of cloud computing. Operating the infrastructure of today's modern clouds include many virtual object abstractions defined above the many physical devices, such as CPUs, drives, switches. Each of these virtual devices provide compute, storage, and networking resources.

Just as the files you use have grown, the quantity of virtual objects to be managed has also grown. It was not uncommon, at VMware for many of our customers to be reaching nearly 10,000 virtual machines and in some cases an order of magnitude above. VMware's VSphere product, which is akin to an operating system for data centers

At VMware I worked on an advanced visualization project we coined Absolute Hubble, as in the Hubble space telescope. The intention was to help cloud administrators quickly understand the relationships between the virtual objects they manage, especially for troubleshooting purposes. 

I **♥ **Complexity.

<button data-role="cta" style="">Open</button>