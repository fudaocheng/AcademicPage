---
title: "Incremental path planning: Reservation system in V2X environment"
collection: publications
category: manuscripts
permalink: /publication/IPP
# excerpt: 'This paper is about fixing template issue #693.'
date: 2023-08-01
venue: 'Physica A: Statistical Mechanics and its Applications'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0378437123004697'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Daocheng Fu, Pinlong Cai, Yilun Lin, Song Mao, Licheng Wen, Yikang Li

Previous work assumes that traffic flow evolves over time, and paths are planned based on traffic estimation and prediction, although such an assumption is simple and efficient for single vehicles, there is a self-contradictory problem when planning paths for multiple vehicles. If multiple vehicles choose the same uncongested road based on traffic forecasts, this may lead to congestion on that road, which in turn affects the efficiency of path planning. The V2X environment offers the possibility to solve the above problems. In this paper, a new perspective is developed where the traffic flow is considered as a superposition of spatiotemporal paths. From this perspective, a novel method is proposed in which the paths are planned incrementally according to the remaining spatiotemporal resources and the travel demands, which is referred to as Incremental Path Planning (IPP). IPP plans the paths of vehicles according to a predefined priority, after a vehicle’s path is planned, the occupancy of spatiotemporal resources is updated, and the remaining resources are then passed to the next vehicle for path planning. In IPP, an incrementally updated traffic model is proposed to obtain the traffic state. Based on this model, a time-dependent path search algorithm is proposed to reduce vehicle travel times. Simulation experiments based on real data sets have demonstrated the excellent performance of IPP in both improving traffic efficiency and driving experience.

More details at [here](https://www.sciencedirect.com/science/article/abs/pii/S0378437123004697).