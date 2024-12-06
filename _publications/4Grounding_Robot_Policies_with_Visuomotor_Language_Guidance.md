---
title: "Grounding Robot Policies with Visuomotor Language Guidance"
collection: publications
permalink: /publications/Grounding_Robot_Policies_with_Visuomotor_Language_Guidance
excerpt: ''
# date: 2023
venue: 'preprint | ICLR 2025 (under review)'
# paperurl: 'https://arxiv.org/pdf/2011.05437.pdf'
authors: '<b>Arthur Bucker</b>, Pablo Ortega-Kral, Jonathan Francis, Jean Oh'
img: "/images/publications/grounding.png"
width: '17%'
pdf: 'https://arxiv.org/pdf/2409.08264'
# video: '' 

---
<!-- <iframe width="560" height="315" src="Grounding Robot Policies with Visuomotor Language Guidance" title="" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

<img src="/images/publications/grounding_main_figure.png"/>


<b>Arthur Bucker</b>, Pablo Ortega-Kral, Jonathan Francis, Jean Oh

Recent advances in the fields of natural language processing and computer vision have shown great potential in understanding the underlying dynamics of the world from large-scale internet data. However, translating this knowledge into robotic systems remains an open challenge, given the scarcity of human-robot interactions and the lack of large-scale datasets of real-world robotic data. Previous robot learning approaches such as behavior cloning and reinforcement learning have shown great capabilities in learning robotic skills from human demonstrations or from scratch in specific environments. However, these approaches often require task-specific demonstrations or designing complex simulation environments, which limits the development of generalizable and robust policies for new settings. Aiming to address these limitations, we propose an agent-based framework for grounding robot policies to the current context, considering the constraints of a current robot and its environment using visuomotor-grounded language guidance. The proposed framework is composed of a set of conversational agents designed for specific roles—namely, high-level advisor, visual grounding, monitoring, and robotic agents. Given a base policy, the agents collectively generate guidance at run time to shift the action distribution of the base policy towards more desirable future states. We demonstrate that our approach can effectively guide manipulation policies to achieve significantly higher success rates both in simulation and in real-world experiments without the need for additional human demonstrations or extensive exploration.

[pdf](https://arxiv.org/pdf/2410.06473)
[Webpage](https://sites.google.com/view/motorcortex/home)
[Code](https://github.com/arthurfenderbucker/motor_cortex)

