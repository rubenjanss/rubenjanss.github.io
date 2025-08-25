---
layout: post
title: Miscommunication Detection
description: Why robots are bad at detecting their mistakes
---

Detecting miscommunication in human-robot interaction is a critical function for maintaining user engagement and trust. While humans effortlessly detect communication errors in conversations through both verbal and non-verbal cues, robots face significant challenges in interpreting non-verbal feedback, despite advances in computer vision for recognizing affective expressions.

This research evaluates the effectiveness of machine learning models in detecting miscommunications in robot dialogue. Using a multi-modal dataset of 240 human-robot conversations, where four distinct types of conversational failures were systematically introduced, we assess the performance of state-of-the-art computer vision models. After each conversational turn, users provided feedback on whether they perceived an error, enabling an analysis of the models' ability to accurately detect robot mistakes.

Despite using state-of-the-art models, the performance barely exceeds random chance in identifying miscommunication, while on a dataset with more expressive emotional content, they successfully identified confused states. To explore the underlying cause, we asked human raters to do the same. They could also only identify around half of the induced miscommunications, similarly to our model.

These results uncover a fundamental limitation in identifying robot miscommunications in dialogue: even when users perceive the induced miscommunication as such, they often do not communicate this to their robotic conversation partner. This knowledge can shape expectations of the performance of computer vision models and can help researchers to design better human-robot conversations by deliberately eliciting feedback where needed.

If you want to know more about this research, [read our paper](../../miscommunication-detection/roman-miscommunication-detection.pdf), which will be presented at the 2025 IEEE International Conference on Robot-Human Interactive Communication (RO-MAN)!

<a href="../../miscommunication-detection/roman-miscommunication-detection.pdf" class="button">Read our paper (PDF)</a>

Feel free to get in touch if you have any other questions or want to know more! You can use any of the channels at the bottom of this page, or send an email to ruben[dot]janssens[at]ugent[dot]be.

If you use our work in any future research, please use the following citation:

~~~~
@inproceedings{janssens2025robots,
  title={Why Robots Are Bad at Detecting Their Mistakes: Limitations of Miscommunication Detection in Human-Robot Dialogue},
  author={Janssens, Ruben and De Bock, Jens and Labat, Sofie and Verhelst, Eva and Hoste, Veronique and Belpaeme, Tony},
  journal={2025 IEEE International Conference on Robot-Human Interactive Communication},
  year={2025}
}
~~~~