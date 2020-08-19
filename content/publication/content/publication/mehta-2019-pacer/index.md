---
title: "Pacer: Network Side-Channel Mitigation in the Cloud"
date: 2019-01-01
publishDate: 2020-07-29T00:17:36.683822Z
authors: ["Aastha Mehta", "Mohamed Alzayat", "Roberta De Viti", "Björn B Brandenburg", "Peter Druschel", "Deepak Garg"]
publication_types: ["3"]
abstract: "An important concern for many Cloud customers is data confidentiality. Of particular concern are potential data leaks via side channels, which arise when mutually untrusted parties contend on resources such as CPUs, caches, and network elements. In this paper, we present a principled solution for mitigating side channels that arise from shared network elements in a public Cloud. Our solution, Pacer, shapes the outbound traffic of a Cloud tenant to make it independent of the tenant's secrets by design. At the same time, Pacer permits traffic variations based on public (non-secret) aspects of the tenants' computation, thus enabling efficient sharing of network resources. Implementing Pacer requires modest changes to the guest OS and the hosting hypervisor, and only minimal changes to guest applications. Pacer allows guests to protect their secrets with bandwidth overhead close to the minimum possible given a workload partitioning based on public information. For instance, Pacer can hide a requested static document from a real document corpus in one of two size clusters at an average throughput and bandwidth overhead of 6.8% and 150%, respectively."
featured: false
url_pdf : "https://arxiv.org/pdf/1908.11568.pdf"
url_poster : "pacer_poster.pdf"
publication: "*arXiv preprint arXiv:1908.11568*"
---

