---
title: "Pacer: Comprehensive Network Side-Channel Mitigation in the Cloud"
date: 2021-11-01
publishDate: 2020-07-29T00:17:36.683822Z
authors: ["Aastha Mehta", "Mohamed Alzayat", "Roberta De Viti", "Björn B Brandenburg", "Peter Druschel", "Deepak Garg"]
publication_types: ["1"]
publication_short : "USENIX Security '22"
abstract: "USENIX Security 2022 -- Network side channels (NSCs) leak secrets through packet timing and packet sizes. They are of particular concern in public IaaS Clouds, where any tenant may be able to colocate and indirectly observe a victim’s traffic shape. We present Pacer, the first system that eliminates NSC leaks in public IaaS Clouds end-to-end. It builds on the principled technique of shaping guest traffic outside the guest to make the traffic shape independent of secrets by design. However, Pacer also addresses important concerns that have not been considered in prior work -— it prevents internal side-channel leaks from affecting reshaped traffic, and it respects network flow control, congestion control and loss recovery signals. Pacer is implemented as a paravirtualizing extension to the host hypervisor, requiring modest changes to the hypervisor and the guest kernel and optional, minimal changes to applications. We present Pacer’s key abstraction of a cloaked tunnel, describe its design and implementation, and show through an experimental evaluation that Pacer imposes moderate overheads on bandwidth, client latency, and server throughput, while thwarting attacks using state-of-the-art CNN classifiers."
featured: true
url_pdf : "https://www.usenix.org/system/files/sec22fall_mehta.pdf"
url_poster : "pacer_poster.pdf"
url_code : "https://gitlab.mpi-sws.org/pacer/pacer"
publication: "31st USENIX Security Symposium (USENIX Security '22)"
---

