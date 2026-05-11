---
layout: post
title: Expressive Furhat
description: LLMs can generate real-time custom facial expressions
---

Enabling natural robot communication through dynamic, context-aware facial expressions remains a key challenge in human-robot interaction. The field lacks a system that can generate facial expressions in real time and can be easily adapted to different contexts. Early work in this area considered inherently limited rule-based systems or deep learning-based models, requiring large datasets. Recent systems using large language models (LLMs) could not yet generate context-appropriate facial expressions in real time. This paper introduces Expressive Furhat, an open-source algorithm and Python library that leverages LLMs to generate real-time, adaptive facial gestures for the Furhat robot. Our modular approach separates gesture rendering, new gesture generation, and gaze aversion, ensuring flexibility and seamless integration with the Furhat API. User studies demonstrate significant improvements in user perception over a baseline system, with participants praising the system's emotional responsiveness and naturalness.

# Library

A Python library that enhances the Furhat robot's expressiveness through AI-generated gestures and natural gaze aversion. This implementation is a drop-in replacement for the standard furhat-remote-api library.

<a href="https://www.github.com/giubots/expressive-furhat" class="button">Check out the library</a>

# Paper

If you want to know more about this research, [read our paper](../../expressive-furhat/expressive-furhat-crv.pdf), which will be presented at HRI 2026!

<a href="../../expressive-furhat/expressive-furhat-crv.pdf" class="button">Read our paper (PDF)</a>

Feel free to get in touch if you have any other questions or want to know more! You can use any of the channels at the bottom of this page, or send an email to ruben[dot]janssens[at]ugent[dot]be.

If you use our work in any future research, please use the following citation:

~~~~
@inproceedings{abbo2026expressive,
  title={Expressive Furhat: Generating Real-Time Facial Expressions
for Human-Robot Dialogue with LLMs},
  author={Abbo, Giulio Antonio and Janssens, Ruben and Van de Vreken, Seppe and Belpaeme, Tony},
  booktitle={Companion Proceedings of the
21st ACM/IEEE International Conference on Human-Robot Interaction (HRI
Companion ’26)},
  year={2026}
}
~~~~