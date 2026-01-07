---
layout: post
title: L2 Speaking Proficiency Assessment
description: Automatically detecting speaking proficiency in a second language.
---

Social robots have been shown to benefit learning and in particular language learning. However, existing language learning robots are limited in their dialogue and adaptation capabilities: many systems use pre-scripted lessons and adaptation options. As large language models enable open-domain dialogue, a conversation practice robot now becomes feasible. Such a robot should adapt its speech to the learner's language proficiency to make the learning more effective. For this, the robot must first accurately detect that proficiency.

This study contributes to this capability by presenting a system that automatically assesses students' speaking proficiency. Based on expert knowledge and related literature, we extract relevant features from a graded student speech dataset. We train a machine learning model on this dataset, paying particular attention to its learned weights to inform future research.
We then validate the model in a human-robot interaction setting, assessing how well it generalizes from human-only training data. Our findings show that a model relying on a limited set of feature types performs sufficiently well for adaptation, with minimal degradation when applied to a human-robot interaction scenario. Future work includes further automating the proposed system and integrating it into an adaptation system, enabling a fully adaptive conversational social robot for language learning.

If you want to know more about this research, [read our paper](../../speaking-proficiency-assessment/ICSR25___Automatic_Assessment_of_Speaking_Proficiency_for_Language_Practice_Robots.pdf), which has been presented at the 2025 International Conference on Social Robotics!

Feel free to get in touch if you have any other questions or want to know more! You can use any of the channels at the bottom of this page, or send an email to ruben[dot]janssens[at]ugent[dot]be.

If you use our work in any future research, please use the following citation:

~~~~
@inproceedings{verhelst2025automatic,
  title={Automatic Assessment of Speaking Proficiency for Language Practice Robots},
  author={Verhelst, Eva and Lecompte, Pieter and Janssens, Ruben and De Wilde, Vanessa and Belpaeme, Tony},
  booktitle={International Conference on Social Robotics},
  pages={400--412},
  year={2025},
  organization={Springer}
}
~~~~