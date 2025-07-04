---
title: "PokerGPT : jouer (correctement) au poker avec un grand modèle de langage"
collection: talks
type: "Talk"
permalink: /talks/pfia25
venue: "PFIA'25"
date: 2025-06-30
location: "Dijon, France"
---

J'ai eu la chance de présenter mes travaux à Dijon lors de la [PFIA'25](https://pfia2025.u-bourgogne.fr/) au sein de l'atelier Jeux et IA / MAFTEC.

Les slides de la présentation sont [ici](/files/pfia25.html).

### Abstract  

L'émergence de l'algorithme de Counterfactual Regret Minimization (CFR) et de ses améliorations a permis la création de « pokerbots » (tels que Cepheus, DeepStack et Libratus) capables de rivaliser avec d'excellents joueurs humains en format cash game à six joueurs, voire de les surpasser en heads-up (1 contre 1). Cependant, la complexité computationnelle de ces méthodes explose dès que l'on dépasse deux joueurs. De plus, suivre un équilibre de Nash ne garantit plus une stratégie non perdante à partir de trois joueurs, limitant fortement l'applicabilité du CFR au format le plus populaire : les tournois.

Inspiré par les succès récents des grands modèles de langage (LLM) dans différents jeux comme les échecs ou Diplomacy, nous proposons PokerGPT, un modèle de langage spécifiquement optimisé pour le Texas Hold’em No Limit à 3 joueurs ou moins (format spin&go). Entraîné par fine-tuning et reinforcement learning sur plusieurs centaines de milliers de mains, PokerGPT prend des décisions directement à partir d'une description textuelle de la main en cours. Après entraînement, notre modèle arrive à reproduire environ 83% des coups joués par le pro et 78% des coups joués par le solver. De plus, moyennant un petit ajustement dû à la différence de profondeur effective entre l'entraînement et l'évaluation, notre IA a battu Slumbot, le dernier pokerbot champion du monde de poker en 2018 (13.4 BB/100 ; IC 95 % : [0.5 ; 26.3]).

