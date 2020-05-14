---
title: "Influenced Maximization at Community Level: A New Challenge with Non-submodularity"
collection: publications
# permalink: https://ieeexplore.ieee.org/document/8423020
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2019-06-01
venue: 'IEEE International Conference on Distributed Computing Systems, IEEE ICDCS 2019'
paperurl: 'https://ieeexplore.ieee.org/document/8884964'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Motivated by various settings, we study a new Influence Maximization problem at the Community level (IMC) which aims at finding k users to maximize the benefit of influenced communities where a community is influenced iff the number of influenced users belong to this community exceeds its predefined threshold. In general, IMC objective function is not submodular nor supermodular, thereby making it very challenging to apply existing greedy solutions of the classic influence maximization (IM) where submodular function is required. Furthermore, the major challenge in the traditional methods for any related IM problem is the inefficiency in estimating the influence spread. IMC brings this difficulty to a higher level when considering influenced communities instead of influencing each individual user. In this paper, we propose different approximation algorithms for IMC: (1) Using Sandwich approach with a tight submodular function to bound the IMC objective function, (2) Activating the top-k influencing nodes found from network sampling. Furthermore, when the activated thresholds of communities are bounded by a constant, we propose an algorithm with performance guarantee tight to the inapproximability of IMC assuming the exponential time hypothesis. Each algorithm has its own strengths in a trade-off between effectiveness and running time, which are illustrated both in theory and comprehensive experimental evaluation.

[Download paper here](https://ieeexplore.ieee.org/document/8884964)