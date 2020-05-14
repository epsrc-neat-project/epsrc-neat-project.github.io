---
layout: default
title: About
---

<p style='text-align: justify;'>Data centre networks are poorly equipped to rapidly spot and address failures [1,2,3], resulting in countless well-documented application performance degradation or outages [1,4,5,6,7]. This is because the investigation process is performed in centralised commodity servers (collectors) that do not have per-packet visibility, but instead aggregated and sampled statistics from the data plane [1,3]. The NEAT project will address this deficiency by moving traffic analysis directly into switches that have per-packet visibility. Exploiting advances in programmable hardware, e.g. P4 [8], NEAT will rethink data plane operation and will transform switches from just packet forwarder with limited monitoring capabilities to more intelligent systems capable of analysing traffic and exporting only relevant results. This will enable the level of fine-grained data plane visibility required to allow operators to rapidly identify and adapt to changes in network conditions, which hurts applications.</p>

---

References:
1. Zhu et al., Packet-Level Telemetry in Large Datacenter Networks, ACM SIGCOMM 2015
2. Zhuo et al., Understanding and Mitigating Packet Corruption in Data Center Networks, ACM SIGCOMM 2017
3. Tilmans et al., Stroboscope: Declarative Network Monitoring on a Budget, USENIX NSDI 2018
4. Hoose, Monitoring and Troubleshooting, One Engineer’s rant, NANOG 2019
5. Maltz, Keeping Cloud-Scale Networks Healthy, 2016
6. Zhu et al., Congestion Control for Large-Scale RDMA Deployments, ACM SIGCOMM 2015
7. Cardwell et al., BBR: Congestion-Based Congestion Control, ACM Queue 2016
8. Bosshart et al., P4: Programming Protocol-independent Packet Processors, ACM Computer Communication Review 2014
