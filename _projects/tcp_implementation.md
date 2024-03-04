---
layout: page
title: low-level tcp
description: C, Computer Communications
img: assets/img/tcp.png
importance: 3
category: fun
---

[Project Link](https://github.com/mgu83/tcp-implementation)

I used C to implement a TCP-like transportation protocol without using TCP at all. The protocol consists of the sender and receiver modules. The sender module is responsible for breaking down a large file into smaller data packets and sequentially transmitting these packets over UDP to the specified receiver. The receiver module listens for incoming data packets, handles them according to their sequence numbers to ensure data is written in the correct order, and sends acknowledgments back to the sender.

The project uses a sliding window mechanism to optimize data flow based on network conditions as well as a state machine to changed the congestion window size and change packet size depending on packet loss, drop rate, throughput and etc. This allows the system to dynamically change and utilize different congestion control algorithms.