---
title: "Reshaping Robot Trajectories Using Natural Language Commands: A Study of Multi-Modal Data Alignment Using Transformers"
collection: publications
permalink: /publications/NL_trajectory_reshaper
excerpt: ''
# date: 2020-11-10
venue: 'NeurIPS 2020 workshop on Tackling Climate Change with Machine Learning & EGU2021 (Proposal paper)'
# paperurl: 'https://arxiv.org/pdf/2011.05437.pdf'
authors: '<b>Arthur Bucker</b>, Luis Figueredo, Sami Haddadin, Ashish Kapoor , Shuang Ma , Rogerio Bonatti'
img: "/images/publications/reshaping.png"
width: '17%'
pdf: 'https://arxiv.org/pdf/2203.13411.pdf'
# video: '' 

---

*<b>Arthur Bucker</b>, Luis Figueredo, Sami Haddadin, Ashish Kapoor, Shuang Ma, Rogerio Bonatti*

Natural language is the most intuitive medium for us to interact with other people when expressing commands and instructions. However, using language is seldom an easy task when humans need to express their intent towards robots, since most of the current language interfaces require rigid templates with a static set of action targets and commands. In this work, we provide a flexible language-based interface for human-robot collaboration, which allows a user to reshape existing trajectories for an autonomous agent. We take advantage of recent advancements in the field of large language models (BERT and CLIP) to encode the user command, and then combine these features with trajectory information using multi-modal attention transformers. We train the model using imitation learning over a dataset containing robot trajectories modified by language commands, and treat the trajectory generation process as a sequence prediction problem, analogously to how language generation architectures operate. We evaluate the system in multiple simulated trajectory scenarios, and show a significant performance increase of our model over baseline approaches. In addition, our real-world experiments with a robot arm show that users significantly prefer our natural language interface over traditional methods such as kinesthetic teaching or cost-function programming. Our study shows how the field of robotics can take advantage of large pre-trained language models towards creating more intuitive interfaces between robots and machines.

[pdf](https://arxiv.org/pdf/2203.13411.pdf)
[Project webpage](https://arthurfenderbucker.github.io/NL_trajectory_reshaper/)



### IROS 2022 video
<iframe width="560" height="315" src="https://www.youtube.com/embed/GCopdDd9CVw" title="Reshaping Robot Trajectories Using Natural Language Commands: A Study of Multi-Modal Data Alignment Using Transformers" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>