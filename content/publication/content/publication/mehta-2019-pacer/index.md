---
title: "Pacer: Comprehensive Network Side-Channel Mitigation in the Cloud"
date: 2021-02-01
publishDate: 2020-07-29T00:17:36.683822Z
authors: ["Aastha Mehta", "Mohamed Alzayat", "Roberta De Viti", "Björn B Brandenburg", "Peter Druschel", "Deepak Garg"]
publication_types: ["1"]
publication_short : "USENIX Security '22"
abstract: "USENIX Security Symposium 2022 -- An important concern for many Cloud customers is data confidentiality. Of particular concern are potential data leaks via side channels, which arise when mutually untrusted parties contend on resources such as CPUs, caches, and network elements. In this paper, we present a principled solution for mitigating side channels that arise from shared network elements in a public Cloud. Our solution, Pacer, shapes the outbound traffic of a Cloud tenant to make it independent of the tenant's secrets by design. At the same time, Pacer permits traffic variations based on public (non-secret) aspects of the tenants' computation, thus enabling efficient sharing of network resources. Implementing Pacer requires modest changes to the guest OS and the hosting hypervisor, and only minimal changes to guest applications. Pacer allows guests to protect their secrets with bandwidth overhead close to the minimum possible given a workload partitioning based on public information. For instance, Pacer can hide a requested static document from a real document corpus in one of two size clusters at an average throughput and bandwidth overhead of 6.8% and 150%, respectively."
featured: true
url_pdf : "https://www.usenix.org/system/files/sec22fall_mehta.pdf"
url_poster : "pacer_poster.pdf"
publication: "31st USENIX Security Symposium (USENIX Security '22)"
---

