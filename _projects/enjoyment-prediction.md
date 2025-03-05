---
layout: post
title: Enjoyment Prediction
description: Large Language Models can predict how much a user will enjoy a human-robot dialog before seeing the user's response.
---

Large Language Models (LLMs) are impressive at driving **open-domain dialogue** for social robots. We finally have an AI system that can respond to anything a user says with very natural-seeming language.

However, they're not yet perfect. Sometimes for example, LLM-driven dialogue remaines very superficial, repetitive, or the robot says something that doesn't invite any further conversation.

What if the robot could actually reason about how much the user would enjoy what it's about to say? If that were possible, we could let the robot choose from a number of possible utterances, based on what it'd think would be the most enjoyable for users. We could even use this prediction as a feedback signal for the LLM to improve itself, to become more enjoyable in human-robot dialogue.

>**We showed that LLMs can be used to do this: predicting a user's enjoyment of a robot utterance in dialogue, before the user has even reacted.**

The system we built uses GPT-4o as predictor. As you can see in the image below, we provide it one "exchange" (a user utterance and the robot's response to it), along with the history of the dialogue before the exchange. We also give it information about the enjoyment scale we're using (HRI CUES), with descriptions of each of the five points on the 1 through 5 scale as well as labelled dialogue examples. The system then outputs a predicted enjoyment score, along with a reasoning for that score.

<img src="../../enjoyment-prediction/poster-fullsystem.PNG" width="400">

We evaluated the performance of this system. Using a dataset of 175 minutes of Swedish human-robot chit-chat conversations, we compared the scores our system predicted against what a similar system that does have access to the user's response outputs, and with scores given by human expert annotators.

>**Our results show that our system performs similarly to human expert annotators and even performs similarly when it does not have access to the user's response to when it does have access to the user's response.**

Even more so, this sytem still achieves significant correlation with the user's own reports of their enjoyment of the dialogue when applied to a completely different type of dialogue in a different language.

>**These results enable future work in developing adaptive conversational systems, as the robot could choose an utterance that has a higher predicted user enjoyment, or train itself to generate more enjoyable conversation.**

We also plan to further analyse the reasoning that the model outputs, as well as integrating multimodal information in the model's predictions.

If you want to know more about this research, [read our paper](../../enjoyment-prediction/enjoyment-prediction-lbr.pdf), which will be presented at the 2025 ACM/IEEE International Conference on Human-Robot Interaction!

Feel free to get in touch if you have any other questions or want to know more! You can use any of the channels at the bottom of this page, or send an email to ruben[dot]janssens[at]ugent[dot]be.

If you use our work in any future research, please use the following citation:

~~~~
@inproceedings{janssens2025online,
  title={Online Prediction of User Enjoyment in Human-Robot Dialogue with LLMs},
  author={Janssens, Ruben and Pereira, André and Skantze, Gabriel and Irfan, Bahar and Belpaeme, Tony},
  booktitle={Proceedings of the 2025 ACM/IEEE International Conference on Human-Robot Interaction},
  year={2025}
}
~~~~