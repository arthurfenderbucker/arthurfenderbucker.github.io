---
title: "GRAPPA: Generalizing and Adapting Robot Policies
via Online Agentic Guidance"
collection: publications
permalink: /publications/GRAPPA_Generalizing_and_Adapting_Robot_Policies
via_Online_Agentic_Guidance
excerpt: ''
# date: 2023
venue: 'preprint | RSS 2025 (under review)'
# paperurl: 'https://arxiv.org/pdf/2011.05437.pdf'
authors: '<b>Arthur Bucker</b>, Pablo Ortega-Kral, Jonathan Francis, Jean Oh'
img: "/images/publications/grappa.png"
width: '17%'
pdf: 'https://arxiv.org/pdf/2409.08264'
# video: '' 

---
<!-- <iframe width="560" height="315" src="Grounding Robot Policies with Visuomotor Language Guidance" title="" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

<img src="/images/publications/grappa_main.png"/>


<b>Arthur Bucker</b>, Pablo Ortega-Kral, Jonathan Francis, Jean Oh

Robot learning approaches such as behavior cloning and reinforcement learning have shown great promise in synthesizing robot skills from human demonstrations in specific environments. However, these approaches often require taskspecific demonstrations or designing complex simulation environments, which limits the development of generalizable and robust policies for unseen real-world settings. Recent advances in the use of foundation models for robotics (e.g., LLMs, VLMs) have shown great potential in enabling systems to understand the semantics in the world from large-scale internet data. However, it remains an open challenge to use this knowledge to enable robotic systems to understand the underlying dynamics of the world, to generalize policies across different tasks, and to adapt policies to new environments. To alleviate these limitations, we propose an agentic framework for robot self-guidance and self-improvement, which consists of a set of role-specialized conversational agents, such as a high-level advisor, a grounding agent, a monitoring agent, and a robotic agent. Our framework iteratively grounds a base robot policy to relevant objects in the environment and uses visuomotor cues to shift the action distribution of the policy to more desirable states, online, while remaining agnostic to the subjective configuration of a given robot hardware platform. We demonstrate that our approach can effectively guide manipulation policies to achieve significantly higher success rates, both in simulation and in real-world experiments, without the need for additional human demonstrations or extensive exploration.

[pdf](/files/GRAPPA.pdf)
<!-- [Webpage](https://sites.google.com/view/motorcortex/home) -->
<!-- [Code](https://github.com/arthurfenderbucker/motor_cortex) -->

