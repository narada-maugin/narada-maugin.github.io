---
title: "PokerGPT: Playing (Correct) Poker with a Large Language Model"
collection: talks
type: "Talk"
permalink: /talks/pfia25
venue: "PFIA'25"
date: 2025-06-30
location: "Dijon, France"
---

I presented a preliminary version of my work on large language models for poker at [PFIA'25](https://pfia2025.u-bourgogne.fr/), in the "Jeux et IA / MAFTEC" workshop in Dijon.

The talk introduces PokerGPT, a large language model specifically optimized for three-player-or-less No-Limit Texas Hold’em (Spin & Go format). Building on earlier pokerbots based on Counterfactual Regret Minimization (CFR), PokerGPT aims to handle settings where traditional equilibrium-based methods become computationally expensive and less relevant, especially as soon as more than two players are involved.

Trained with a combination of supervised fine-tuning and reinforcement learning on several hundred thousand hands, PokerGPT takes decisions directly from a textual description of the current hand. After training, it reproduces a high proportion of the actions played by both a professional player and a solver, and—after a small adjustment for effective stack depth—manages to beat Slumbot, the 2018 world-champion pokerbot.

The slides of the talk are available [here (french)](/files/pfia25.html).
