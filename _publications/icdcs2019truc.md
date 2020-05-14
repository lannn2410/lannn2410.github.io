---
title: "Optimal Transactions Placement for Scalable Blockchain Sharding"
collection: publications
# permalink: https://ieeexplore.ieee.org/document/8423020
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2019-06-01
venue: 'IEEE International Conference on Distributed Computing Systems, IEEE ICDCS 2019'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8884909'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
A major challenge in blockchain sharding protocols is that more than 95% transactions are cross-shard. Not only those cross-shard transactions degrade the system throughput but also double the confirmation time, and exhaust an already scarce network bandwidth. Are cross-shard transactions imminent for sharding schemes? In this paper, we propose a new sharding paradigm, called OptChain, in which cross-shard transactions are minimized, resulting in almost twice faster confirmation time and throughput. By treating transactions as a stream of nodes in an online graph, OptChain utilizes a lightweight and on-the-fly transaction placement method to group both related and soon-related transactions into the same shards. At the same time, OptChain maintains a temporal balance among shards to guarantee the high parallelism. Our comprehensive and large-scale simulation using Oversim P2P library confirms a significant boost in performance with up to 10 folds reduction in cross-shard transactions, more than twice reduction in confirmation time, and 50% increase in throughput. When combined with Omniledger sharding protocol, OptChain delivers a 6000 transactions per second throughput with 10.5s confirmation time.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/8884909)