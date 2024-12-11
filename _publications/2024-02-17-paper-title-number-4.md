---
title: "AddrMiner: A Fast, Efficient, and Comprehensive Global Active IPv6 Address Detection System"
collection: publications
category: manuscripts
permalink: /publication/2024-06-13
excerpt: 'This paper introduces AddrMiner, a fast, efficient, and comprehensive global active IPv6 address detection system.'
date: 2024-06-13
venue: 'IEEE/ACM Transactions on Networking'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10556607'
citation: 'Song, Guanglei, et al. "AddrMiner: A Fast, Efficient, and Comprehensive Global Active IPv6 Address Detection System." IEEE/ACM Transactions on Networking (2024).'

---

Fast Internet-wide scanning is essential for network situational awareness and asset evaluation. However, the vast IPv6 address space makes brute-force scanning infeasible. Despite advancements in state-of-the-art methods, they do not work in seedless regions and suffer low detection efficiency and speed in regions with known active IPv6 addresses (i.e., seed addresses). Moreover, the collected active address list (i.e., IPv6 hitlist) with low coverage cannot truly represent the active IPv6 address landscape of the Internet. This paper introduces AddrMiner, a fast, efficient, and comprehensive global active IPv6 address detection system. We design a systematic active IPv6 address detection strategy that divides the IPv6 space into two detection scenarios based on the presence or absence of seed addresses to discover active IPv6 addresses from scratch and from few to many. In the seedless regions, we present AddrMiner-N, leveraging a multi-level association policy to probe active addresses. It fills the gap of address detection in seedless regions and successfully discovers active addresses in 39,899 BGP prefixes without seed addresses, with a 1.03× higher hit rate, 30∼911× higher speed, and 2.7× broader coverage, compared to existing solutions. In the regions with seed addresses, our method AddrMiner-S dynamically generates target addresses using reinforcement learning. Compared to state-of-the-art methods, AddrMiner-S achieves an impressive 56.3% hit rate and a discovery speed of 839.0/s, which is 1.9∼2153× and 1.5∼755× of existing works, respectively. Finally, we deploy AddrMiner and discover 2.1B active IPv6 addresses, including 1.7B de-aliased active addresses and 0.4B aliased addresses, through continuous probing for three years.

