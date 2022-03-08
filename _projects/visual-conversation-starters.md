---
layout: post
title: Visual Conversation Starters
description: Generating visually-grounded conversation-starting questions for Human-Robot Interaction
---

Imagine if a robot would come up to you and say "Hey, that's a cool T-shirt, where did you get that?" We created a system that makes this a reality.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/DPTqGCBiMwE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Conversational agents for social robots are not yet sufficiently aware of their environment. Users expect that a social robot sees them and their shared environment, and that it understands all of that. That's why we explored how to get a robot to integrate visual information into its dialogue.

We created a system that generates questions for a robot to start a conversation with someone they haven't met before. The questions refer to something the robot can see - like the user's apparel or their environment.

To solve this problem, we collected a **dataset** of 4000 HRI-appropriate images, each with three visual conversation-starting questions. The images - or the robot's camera feed in a live interaction - were first textually described using a captioning model, which was then used to **generate the questions**. We let real humans **evaluate** those questions: they found them to be interesting and appropriate. We also **demonstrated** the system with a Furhat social robot, showing it works in a real-world live interaction!

If you want to know more about this research, [read our paper](https://dl.acm.org/doi/abs/10.5555/3523760.3523884), which was presented at the 2022 Human-Robot Interaction conference! You can also watch our [presentation](https://www.youtube.com/watch?v=FRgBgRJhXTA) just below. Finally, we have published the [full dataset and code](https://github.com/rubenjanss/visual-conversation-starters) on GitHub.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/FRgBgRJhXTA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Feel free to get in touch if you have any other questions or want to know more! You can use any of the channels at the bottom of this page, or send an email to rmajanss[dot]janssens[at]ugent[dot]be.

If you use our work in any future research, please use the following citation:

~~~~
@inproceedings{janssens2022cool,
  title={“Cool glasses, where did you get them?” Generating Visually Grounded Conversation Starters for Human-Robot Dialogue},
  author={Janssens, Ruben and Wolfert, Pieter and Demeester, Thomas and Belpaeme, Tony},
  booktitle={Proceedings of the 2022 ACM/IEEE International Conference on Human-Robot Interaction},
  pages={821--825},
  year={2022}
}
~~~~