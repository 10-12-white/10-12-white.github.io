
# Evaluating the Max-Weight Algorithm for DDoS Mitigation in a Simulated Network Environment 

## Introduction

Distributed Denial of Service (DDoS) attacks represent a substantial and persistent threat to the operational integrity and security of modern network infrastructure. These malicious attacks function by overwhelming target systems with an excessive volume of traffic, often originating from numerous compromised devices or botnets. This influx of illegitimate requests consumes critical resources, leading to service disruption, performance degradation, and potential financial losses for the targeted entity. Traditional methods employed for mitigating DDoS attacks frequently rely on reactive strategies. 

These include techniques such as traffic filtering, which identifies and blocks malicious packets based on predefined rules, and rate limiting, which restricts the number of requests a system will accept from a particular source within a given timeframe. While these methods can be effective to a certain extent, they are often implemented after an attack has already begun and may struggle to adapt to the evolving nature of sophisticated DDoS attacks. 

## Project Outline

This project aims to explore a more proactive and adaptive approach to DDoS mitigation by investigating the potential application of the max-weight algorithm. The max-weight algorithm is a well-established technique primarily utilised in the optimisation of queueing networks. Its core principle is to stabilise network queues and maximise throughput by prioritising traffic based on the current backlog of data waiting to be processed and the service rates of the network links. This project will delve into the possibility of adapting this optimisation technique, traditionally used for managing data flow, to identify and manage malicious traffic flows during a DDoS attack. The goal is to determine whether the max-weight algorithm can offer a more dynamic and adaptive defence mechanism that can proactively respond to the characteristics of an ongoing attack, potentially leading to more effective mitigation.
 
