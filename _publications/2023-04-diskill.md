---
title: 'Acquiring Diverse Skills using Curriculum Reinforcement Learning with Mixture of Experts'
collection: publications
permalink: /publication/diskill
date: 2024-07-22
venue: 'ICML'
authors: '<b>Onur Celik</b>, Aleksandar Taranovic, Gerhard Neumann'
paperurl: 'https://openreview.net/pdf?id=9ZkUFSwlUH'
codeurl: 'https://alrhub.github.io/di-skill-website/'
tag: "rl"
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
#paperurl: 'http://academicpages.github.io/files/paper1.pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

<p>
<h3> Abstract: </h3>
Reinforcement learning (RL) is a powerful approach for acquiring a good-performing policy. However, learning diverse skills is challenging in RL due to the commonly used Gaussian policy parameterization. We propose Diverse Skill Learning (Di-SkilL), an RL method for learning diverse skills using Mixture of Experts, where each expert formalizes a skill as a contextual motion primitive. Di-SkilL optimizes each expert and its associate context distribution to a maximum entropy objective that incentivizes learning diverse skills in similar contexts. The per-expert context distribution enables automatic curricula learning, allowing each expert to focus on its best-performing sub-region of the context space. To overcome hard discontinuities and multi-modalities without any prior knowledge of the environment's unknown context probability space, we leverage energy-based models to represent the per-expert context distributions and demonstrate how we can efficiently train them using the standard policy gradient objective. We show on challenging robot simulation tasks that Di-SkilL can learn diverse and performant skills.</p>