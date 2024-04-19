---
layout: plain
title: Publications
# description: >
#   This is the `list` layout for showing blog posts, which shows just the title and groups them by year of publication.
#   Check out the `blog` layout for comparison.
sitemap: false
---
Hereunder are three of my previous publications that you may want to check out.
Don't hesitate to have a look at [my scholar profile](https://scholar.google.com/citations?user=odZdKOYAAAAJ)
to see my full list of publications.

## [2024: Towards SSH3: How HTTP/3 Improves Secure Shells](https://arxiv.org/pdf/2312.08396.pdf)
In this article, we revisit the design of the SSH protocol and analyze how HTTP, QUIC and TLS can
be used as modern alternatives for the SSH Transport and Authentication protocols.
This project led to a popular [Github repository](https://github.com/francoismichel/ssh3) (>3k stars)
an [APNIC blogpost](https://blog.apnic.net/2024/02/02/towards-ssh3-how-http-3-improves-secure-shells/)
and an [Internet Draft](https://www.ietf.org/archive/id/draft-michel-ssh3-00.html).

## [2023: My Thesis: Revisiting The Loss Recovery of QUIC](https://ncs.uclouvain.be/assets/pdf/michel-phd.pdf)
The QUIC proposes a reliable stream abstraction by retransmitting the content of lost packets.
This may not be sufficient for latency-sensitive applications over high-delay networks.
This thesis extends the loss recovery mechanism of the QUIC protocol, relying on Forward Erasure Correction
(FEC) under tight latency constraints and using regular retransmissions otherwise.
The thesis proposes significant latency improvements of QUIC transfers in emulated environments and
over real networks such as the Starlink network.

## [2022: A First Look At Starlink Performance](https://dl.acm.org/doi/abs/10.1145/3517745.3561416)
We published the first article evaluating the performance of the Starlink network under different
use-cases and requirements. Besides throughput, we analyzed the latency over an idle link, bufferbloat
over a utilized link and packet losses and loss patterns caused by the wireless medium.
You can checkout [the presentation video](https://dl.acm.org/doi/10.1145/3517745.3561416#sec-supp) and the
related [APNIC blogpost](https://blog.apnic.net/2022/11/28/fact-checking-starlinks-performance-figures/).
