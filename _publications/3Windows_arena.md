---
title: "Windows Agent Arena"
collection: publications
permalink: /publications/Windows_Agent_Arena
excerpt: ''
# date: 2023
venue: 'Neurips 2024 Workshop on Safe & Trustworthy Agents (SATA) | Neurips 2024 Workshop on Open-World Agents | 2025 (under review)'
# paperurl: 'https://arxiv.org/pdf/2011.05437.pdf'
authors: 'Rogerio Bonatti, Dan Zhao, Francesco Bonacci, Dillon Dupont, Sara Abdali, Yinheng Li, Yadong Lu, Justin Wagle, Kazuhito Koishida, <b>Arthur Bucker</b>, Lawrence Jang, Zack Hui'
img: "/images/publications/windows_arena.png"
width: '17%'
pdf: 'https://arxiv.org/pdf/2409.08264'
video: 'https://microsoft.github.io/WindowsAgentArena/static/videos/mosaic.mp4' 

---
<iframe width="560" height="315" src="https://microsoft.github.io/WindowsAgentArena/static/videos/mosaic.mp4" title="Windows Arena" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Rogerio Bonatti, Dan Zhao, Francesco Bonacci, Dillon Dupont, Sara Abdali, Yinheng Li, Yadong Lu, Justin Wagle, Kazuhito Koishida, <b>Arthur Bucker</b>, Lawrence Jang, Zack Hui

Large language models (LLMs) show remarkable potential to act as computer agents, enhancing human productivity and software accessibility in multi-modal tasks that require planning and reasoning. However, measuring agent performance in realistic environments remains a challenge since: (i) most benchmarks are limited to specific modalities or domains (e.g. text-only, web navigation, Q&A, coding) and (ii) full benchmark evaluations are slow (on order of magnitude of days) given the multi-step sequential nature of tasks. To address these challenges, we introduce the Windows Agent Arena: a reproducible, general environment focusing exclusively on the Windows operating system (OS) where agents can operate freely within a real Windows OS and use the same wide range of applications, tools, and web browsers available to human users when solving tasks. We adapt the OSWorld framework (Xie et al., 2024) to create 150+ diverse Windows tasks across representative domains that require agent abilities in planning, screen understanding, and tool usage. Our benchmark is scalable and can be seamlessly parallelized in Azure for a full benchmark evaluation in as little as 20 minutes. To demonstrate Windows Agent Arena's capabilities, we also introduce a new multi-modal agent, Navi. Our agent achieves a success rate of 19.5% in the Windows domain, compared to 74.5% performance of an unassisted human. Navi also demonstrates strong performance on another popular web-based benchmark, Mind2Web. We offer extensive quantitative and qualitative analysis of Navi's performance, and provide insights into the opportunities for future research in agent development and data generation using Windows Agent Arena.

[pdf](https://arxiv.org/pdf/2409.08264)
[Webpage](https://microsoft.github.io/WindowsAgentArena)
[Code](https://github.com/microsoft/WindowsAgentArena)

Oral presentation at NeurIPS 2024 Workshop on [Safe & Trustworthy Agents (SATA)](https://www.mlsafety.org/events/neurips/2024)

Poster presentations at NeurIPS 2024 Workshop on [Open-World Agents](https://sites.google.com/view/open-world-agents/home)
