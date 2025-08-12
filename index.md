---
title: CS 5955/6955 Advanced Artificial Intelligence
---


# CS 5955/6955 Advanced Artificial Intelligence

## Navigation
- [Canvas Class Page](https://utah.instructure.com/courses/1027622/assignments/syllabus)
- [Piazza](https://piazza.com/utah/spring2025/cs6955001spring2025/home)
- [Schedule](#schedule)
- [Resources](#resources)

## Class Overview

## Class Schedule
| Date | Topic | Slides | Readings | Assignment |
| --- | --- | --- | --- | --- |
| Jan 6 | Class Intro | [Slides](slides/intro.pdf) | [Python Notes (Alan Kuntz)](readings/Python_Tips.pdf) | [Python Tutorial (Berkeley AI Class)](https://inst.eecs.berkeley.edu/~cs188/fa24/projects/proj0/) |
| Jan 8 | Behavioral Cloning | [Slides](slides/bc.pdf) | [Behavioral Cloning from Observation](https://arxiv.org/abs/1805.01954) | [Behavior Cloning in PyTorch](https://github.com/dsbrown1331/imitation_learning) |
| Jan 13 | Intro to Advanced Behavior Cloning | [Slides](slides/advanced-bc-slides.pdf) | [Implicit Behavioral Cloning](https://arxiv.org/abs/2109.00137) |  |
| Jan 15 | More Advanced Behavior Cloning | [Slides](slides/advanced-bc-slides.pdf) |  |  |
| Jan 22 | Multi-Armed Bandits and Evaluative Feedback | [Slides](slides/bandits.pdf) | [Sutton and Barto 2.1-2.5](http://incompleteideas.net/book/ebook/node14.html) | [Multi-Armed Bandits](https://docs.google.com/document/d/1HsvielgBPUZA-MiO3Y2m4pEE5iXndgOi7TWyEZyvPpE/edit?usp=sharing) |
| Jan 27 | More Bandits | [Slides](slides/bandits.pdf) |  |  |
| Jan 29 | Intro to Markov Decision Processes | [Slides](slides/mdps.pdf) |  |  |
| Feb 3 | Solving MDPs | [Slides](slides/mdps.pdf) | [Exact Solution Methods for MDPs](http://incompleteideas.net/book/ebook/node40.html) | [Homework 3](https://github.com/dsbrown1331/solving-mdps) |
| Feb 5 | Value-Based RL and Temporal Difference Leanring | [Slides](slides/dqn.pdf) | [Intro to RL](http://incompleteideas.net/book/ebook/node27.html) |  |
| Feb 10 | Q-Learning and DQN | [Slides](slides/dqn.pdf) | [Q-Learning](http://incompleteideas.net/book/ebook/node65.html) |  |
| Feb 12 | Intro to Policy-Gradients for RL | [Slides](slides/vpg.pdf) | [Read Intro Parts 1-3](https://spinningup.openai.com/en/latest/spinningup/rl_intro.html) | [Homework 4: Q-Learning and DQN (due Feb 25)](https://github.com/dsbrown1331/q-learning-homework) |
| Feb 19 | Policy Gradients and REINFORCE |  |  |  |
| Feb 24 | Alpha Go | [Slides](slides/alphaGo.pdf) | [Alpha Go](readings/alphaGo.pdf) |  |
| Feb 26 | No Class: Do Reading Assignment Instead |  |  | [Alpha Go Zero](readings/alphaGoZero.pdf) |
| Mar 3 | Special Topics: Shared Control, Early Failure Detection for Robot Surgery |  | [VOSA](https://arxiv.org/abs/2501.08389) | Pick one paper from the readings for today and submit reading report before class. |
| Mar 5 | Special Topics: RLHF for Robot Surgery, Explainable Reward Learning, Adversarial Attacks on Behavioral Cloning |  | [RLHF for Surgery](https://arxiv.org/abs/2404.07185) | Pick one paper from the readings for today and submit reading report before class. |
| Mar 10-14 | Spring Break |  |  | Final project team selection due. |
| Mar 17 | Actor Critic Algorithms | [Slides](slides/ac.pdf) | [A3C](https://arxiv.org/abs/1602.01783) | [here](https://docs.google.com/document/d/11IqTbuJrvu5esMOVrQMxtfG7F3IoS5a5G6zdUOVmN-g/edit?tab=t.0) |
| Mar 19 | PPO | [Slides](slides/ac.pdf) | [A3C](https://arxiv.org/abs/1602.01783) |  |
| Mar 24 | DDPG, TD3, and SAC | [Slides](slides/sac.pdf) | [DDPG](https://arxiv.org/abs/1509.02971) |  |
| Mar 26 | Multi-Agent RL | [Slides](slides/marl.pdf) | [MARL book (chapter 5)](https://www.marl-book.com/download/marl-book.pdf#page=118.10) | [Homework 5](https://github.com/dsbrown1331/policy_gradient_homework/) |
| Mar 31 | Model Based RL | [Slides](slides/mbrl.pdf) | [World Models](https://worldmodels.github.io/) | Read one of the above papers/posts and submit a reading report before class. |
| Apr 2 | Inverse RL and Reward Learning | [Slides](slides/irl.pdf) |  | [Final Project Lit Review and Full Proposal](https://docs.google.com/document/d/1Zs3T6rpvUoD_Of6vPbWDmN0BZ0ACgvpdJ1GLx2EgpDs/edit?usp=sharing) |
| Apr 7 | RLHF | [Slides](slides/rlhf.pdf) |  |  |
| Apr 9 | LLM Agents and RL | [Slides](slides/llms.pdf) |  |  |
| Apr 14 | Final project presentations | [Schedule](https://docs.google.com/spreadsheets/d/1dLdfva2XMdq0dy3vKuOLGT9II3VtTkRq-UzfmU0GHDA/edit?usp=sharing) | [Apr 14 Shared Slide Deck](https://docs.google.com/presentation/d/1LKzyLF9cdSfQmqAcbbSo9_HZk2HUHtKiyIW5Fbw2sF0/edit?usp=sharing) |  |
| Apr 16 | Final project presentations | [Schedule](https://docs.google.com/spreadsheets/d/1dLdfva2XMdq0dy3vKuOLGT9II3VtTkRq-UzfmU0GHDA/edit?usp=sharing) | [Apr 16 Shared Slide Deck](https://docs.google.com/presentation/d/1HLtQOK4Wm_JlWetw-JRgXuZHHfPAyNmbol4z6lFXZtc/edit?usp=sharing) |  |
| Apr 21 | Final project presentations | [Schedule](https://docs.google.com/spreadsheets/d/1dLdfva2XMdq0dy3vKuOLGT9II3VtTkRq-UzfmU0GHDA/edit?usp=sharing) | [Apr 21 Shared Slide Deck](https://docs.google.com/presentation/d/1JchzGIfJp3yoEgmDnnv2ka-7yc1c1k5No3gc_w-ctB4/edit?usp=sharing) |  |
| Apr 30 | Final project reports due |  | [Instructions](https://docs.google.com/document/d/1dPOIV5jSvPTkgVJgV6b7HqZDdUD6ZODHJE9hbDEHwnI/edit?usp=sharing) | [this](https://www.overleaf.com/project/636c0de65de98308dfee6a61) |

## Additional Resources
- Sutton and Barto RL books [First Edition (html)](http://incompleteideas.net/book/ebook/the-book.html) , Second Edition (pdf) Berkeley Intro AI Lectures (Scroll down to earlier years since links at top seem to be broken) Berkeley Deep RL Class and Videos My Human-AI Alignment Class Reading List David Silver RL Lectures
- [Berkeley Intro AI Lectures (Scroll down to earlier years since links at top seem to be broken)](https://ai.berkeley.edu/lecture_videos.html)
- [Berkeley Deep RL Class](https://rail.eecs.berkeley.edu/deeprlcourse/) and Videos
- My Human-AI Alignment Class [Reading List](https://users.cs.utah.edu/~dsbrown/cs6960.html)
- [David Silver RL Lectures](https://www.youtube.com/playlist?list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ)
- [60 minute blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)
- [Regression and Classification](https://clemsonciti.github.io/rcde_workshops/pytorch/03-regression_and_classification.html)
- [Regression](https://machinelearningmastery.com/building-a-regression-model-in-pytorch/)
- [Classification](https://www.geeksforgeeks.org/classification-using-pytorch-linear-function/)
