---
title: "Energy-efficient and Priority-aware Task Scheduling for Dynamic Vehicular Edge Computing"
collection: Research project
type: "Research project"
permalink: /talks/MEPPO
venue: "Xi'an Jiaotong-Liverpool University"
date: 2023-10-01
location: "Suzhou, China"
---

###  Introduction:

The increasing complexity of vehicles has led to a growing demand for in-vehicle services that rely on multiple sensors. 
In the Vehicular Edge Computing (VEC) paradigm, energy-efficient task scheduling is critical to achieving optimal completion time and energy consumption. 
Although extensive research has been conducted in this field, challenges remain in meeting the requirements of time-sensitive services and adapting to dynamic traffic environments. 

In this context, a novel algorithm called Multi-action and Environment-adaptive Proximal Policy Optimization algorithm (MEPPO) is designed based on the conventional PPO algorithm and then a joint task scheduling and resource allocation method is proposed based on the designed MEPPO algorithm. 
In specific, the method involves three core aspects. 
Firstly, task scheduling strategy is designed to generate task offloading decisions and priority assignment decisions for the tasks utilizing PPO algorithm, which can further reduce the completion time of service requests. 
Secondly, transmit power allocation scheme is designed considering the expected transmission distance among vehicles and edge servers, which can minimize transmission energy consumption by adjusting the allocated transmit power dynamically. 
Thirdly, the proposed MEPPO-based scheduling method can make scheduling decisions for vehicles with different numbers of tasks by manipulating the state space of the PPO algorithm, which makes the proposed method be adaptive to real-world dynamic VEC environment. 
At last, the effectiveness of the proposed method is demonstrated through extensive simulation and on-site experiments.

###  Main challenges:

- Assignment of the execution priority for the tasks.
- Transmit power allocation to reduce energy consumption.
- Changing number of tasks and vehicles in dynamic vehicular edge computing scenarios.


###  Contributions:

- The term of task scheduling is re-defined, including task offloading and priority assignment.
- The transmit power is allocated considering the communication distances between vehicles and edge servers.
- An Environment-adaptive Proximal Policy Optimization algorithm is designed based on the PPO algorithm, which is trained under a large number of tasks.

The architecture of the proposed task scheduling method:

![image](/images/MEPPO.png)

###  Outcomes:

**Peisong Li**, Ziren Xiao, Xinheng Wang*, Kaizhu Huang, Yi Huang, and Honghao Gao*. "EPtask: Deep Reinforcement Learning based Energy-efficient and Priority-aware Task Scheduling for Dynamic Vehicular Edge Computing." *IEEE Transactions on Intelligent Vehicles*, 2023. (JCR Q1, IF=8.2)
