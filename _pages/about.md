---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 6th Year PhD student at Purdue University working with [Professor Dan Goldwasser](https://www.cs.purdue.edu/homes/dgoldwas/), originally from California. I am currently looking for full time positions, starting in Summer 2024. I have completed internships at Microsoft Research, Amazon Science, Fujitsu, and several startups (Loom.ai and UnifyID). I have also published 5 first author papers (along with several workshop papers), and have been accepted at top NLP conferences like ACL, NAACL, and AACL.

Broad Research Interests
======

My research focus is in the space of Interactive Learning, Large Language Models (LLMs), and Computational Social Science. I'm broadly interested in building an artificial agent that can interact with humans to comprehend Natural Language instructions and use them to do better, especially without being re-trained. I have been working on solving this problem in [Fake News Detection](https://arxiv.org/abs/2309.07384), [Robotics](https://aclanthology.org/N19-1195.pdf), and [Grounded Language Learning](https://arxiv.org/abs/2304.10750). 

General Motivation: When AI agents make mistakes, they usually have to be re-trained. However, instead, humans should be able to help the agent via natural language, and the agent should be able to take advantage of this knowledge to do better in the future, especially in a similar situation. Enabling this would allow agents to continually improve when deployed in the wild, and be more interactive. Particularly with diffcult to train/access LLMs, this can be useful.

I tackled this approach most recently in Computational Social Science, where after building a [state-of-the-art graph model](https://aclanthology.org/2022.acl-long.97/), we showed how minimal human interaction can [significantly improve it](https://arxiv.org/abs/2309.07384). Specifically, humans interact with the AI model, and then LLMs are used to "amplify" the interactions, to get the most impact from each interaction. 

More recently, I've been working on training smaller LLMs to better prompt bigger ones to solve important tasks. This involves using Reinforcement Learning and human interactions to design reward functions to improve the prompt the smaller LLM creates, like RLHF but better! 

In the past at an internship at Microsoft research, I also worked on [Grounded Language Learning](https://arxiv.org/abs/2304.10750), where I built an end-to-end interactive agent. The agent could receive interactions from humans and also interact back with humans by asking clarification questions, and we showed both setups were very useful. Further, the agent could predit it's own response to it's own question, and do well with that as well!

At Amazon, I worked on an innovative graph-based solution to improve how users can find their favorite products via Amazon search! And also a better way to detect entities in Alexa utterances!
