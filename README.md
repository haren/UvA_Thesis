Master's Thesis
=====================

This repository contains my Master's Thesis for the MSc in Software Engineering at the University of Amsterdam.

As the globalization of the world progresses, so does the globalization of web platforms and applications. Clients are expected to connect to the same system and generate and receive data in \textit{real time} (as close to the speed light limits as possible).

## Abstract
The host company intends to have their cloud-based system as close to the physical and hardware limits as possible. A solution that satisfies latency, resource utilization and running cost criteria is sought for.

In this research, I proposed three different architecture decompositions with varying degrees of geographical distribution. A cloud-based load test suite was designed to generate load used to benchmark 3 different architectures. Metric collection has been implemented for both client and server machines  (also real-time monitoring for the servers) and analysis of the metrics has been performed using scalability meters derived from scientific literature \cite{Models}.

Research questions concern the geographic distribution of users and their proximity to WebSocket servers. The hypothesis is that when they are close, their experienced latencies and general system performance can be improved. According to some system limitations that cannot be easily overcome (not fully asynchronous database connectivity), the hypothesis has been refuted.