---
layout: schedule
title: Schedule
---
 
<!--- 
New sections start with 2 stars:  ** Section Title
New units start with 3 stars:     *** {Unit Metadata}
-----------------------------start example
** Section-I
*** { @unit = "15th Nov", @title = "Course Overview", @reading, @lecture, @assignment, @foldout }
-----------------------------end example
Unit Metadata is comprised of:
@unit - date or number
@title - unit name
@reading - turn on reading icon
@assignment - turn on lecture icon
@lecture - turn on lecture icon
@foldout - activate unit content (allow foldout)
-->



** Computational Game Theory with Applications to AI and ML

*** { @unit = "2nd Apr", @title = "Lecture 1: Introduction to game theory", @reading, @lecture, @foldout}

Introduction and logistics. Basics of game theory, equilibria, zero-sum games, Minimax theorem.

Presentation: [Lecture 1](https://raw.githubusercontent.com/stanford-msande233/spring24/master/assets/presentations/Lecture1.pdf)

Readings:
- [Chapters 1-2 of AI, Games and Markets](https://www.columbia.edu/~ck2945/files/main_ai_games_markets.pdf)
- [Lecture Notes](https://www.vsyrgkanis.com/6853sp19/lec2.pdf)

*** { @unit = "4th Apr", @title = "Lecture 2: Online (no-regret) learning", @reading, @lecture, @foldout}

Basics of online learning algorithms and theoretical foundations.

Presentation: [Lecture 2](https://raw.githubusercontent.com/stanford-msande233/spring24/master/assets/presentations/Lecture2.pdf)

Readings:
- [Lecture Notes](https://www.vsyrgkanis.com/6853sp19/lecture3.pdf)
- [Lecture Notes, First Half](https://www.vsyrgkanis.com/6853sp19/lecture4.pdf)

Further Reading
- [Online Learning and Online Convex Optimization, Chapters 1-2](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=cbc4aa545290536e2a10726ed7d7673226ca00d9)

*** {@unit = "5th Apr", @title = "Python Tutorial", @lecture, @foldout}

Presentation [Python Tutorial](https://raw.githubusercontent.com/stanford-msande233/spring24/master/assets/presentations/PythonTutorial.pdf)

*** { @unit = "9th Apr", @title = "Homework 1 (due 16th Apr)", @assignment}


*** { @unit = "9th Apr", @title = "Lecture 3: Solving zero-sum games with no-regret", @reading, @lecture, @foldout}

Solving zero-sum games using no-regret dynamics. 

Presentation: [Lecture 3](https://raw.githubusercontent.com/stanford-msande233/spring24/master/assets/presentations/Lecture3.pdf)

Readings:
- [Lecture Notes](https://www.vsyrgkanis.com/6853sp19/lecture4.pdf)


*** { @unit = "11th Apr", @title = "Lecture 4: Applications of zero-sum games to ML and AI", @reading, @lecture, @foldout}

Applications of zero-sum games in machine learning and AI: boosting, adversarial robustness, distributional robustness, fairness, GANs, Imitation learning, Reinforcement learning from human feedback, NPIV (causal machine learning).

Presentation: [Lecture 4](https://raw.githubusercontent.com/stanford-msande233/spring24/master/assets/presentations/Lecture4.pdf)

Readings:
- [Game Theory, Online Prediction and Boosting](https://www.cs.cmu.edu/~ninamf/LGO10/wm-minimax.pdf)
- [Tutorial on GANs, Especially Sections 3.2, 5.1, 8.2](https://arxiv.org/pdf/1701.00160.pdf)
- [Robust Optimization for Non-Convex Objectives](https://arxiv.org/abs/1707.01047)
- [Distributionally Robust Neural Networks](https://arxiv.org/abs/1911.08731)
- [Adversarial Training for Causal ML](https://arxiv.org/abs/2006.07201)
- [Zero-Sum Games for RLHF](https://arxiv.org/abs/2401.04056)
- [Zero-Sum Games for Imitation Learning](https://proceedings.mlr.press/v139/swamy21a.html)
- [Zero-Sum Games for Fair ML](https://arxiv.org/abs/1809.04198)

*** { @unit = "16th Apr", @title = "Homework 2 (due 23rd Apr)", @assignment}

Due: April 23rd

*** { @unit = "16th Apr", @title = "Lecture 5: Extensive-form games", @reading, @lecture, @foldout}

Extensive form games of complete and incomplete information.

Presentation: [Lecture 5](https://raw.githubusercontent.com/stanford-msande233/spring24/master/assets/presentations/Lecture5.pdf)

Readings:
- [Chapter 8-9, AI, Games and Markets](https://www.columbia.edu/~ck2945/files/main_ai_games_markets.pdf)

Videos:
- [Noam Brown, Superhuman AI for heads-up no-limit poker: Libratus beats top professionals](https://www.youtube.com/watch?v=2dX0lwaQRX0)

Further Reading:
- [Stratego AI](https://www.science.org/doi/10.1126/science.add4679)
- [Poker AI](https://www.science.org/doi/10.1126/science.aao1733)
- [Chess, Shogi and Go AI](https://www.science.org/doi/10.1126/science.aar6404)
- [Optimistic FTRL for Extensive Games](https://arxiv.org/pdf/1910.10906.pdf)

*** { @unit = "18th Apr", @title = "Lecture 6: No-regret learning for extensive form games", @reading, @lecture, @foldout}

Presentation: [Lecture 6](https://raw.githubusercontent.com/stanford-msande233/spring24/master/assets/presentations/Lecture6.pdf)

Readings:
- [Chapter 8-9, AI, Games and Markets](https://www.columbia.edu/~ck2945/files/main_ai_games_markets.pdf)

Videos:
- [Noam Brown, Superhuman AI for heads-up no-limit poker: Libratus beats top professionals](https://www.youtube.com/watch?v=2dX0lwaQRX0)

Further Reading
- [Chapter 5, AI, Games and Markets](https://www.columbia.edu/~ck2945/files/main_ai_games_markets.pdf)
- [Lectures 11-15, CMU Computational Game Solving Course](https://www.cs.cmu.edu/~sandholm/cs15-888F21/)

Further Videos:
- [Noam Brown, Deep Learning and Search for Imperfect Information Games](https://www.youtube.com/watch?v=mCldyXOYNok)

*** { @unit = "23rd Apr", @title = "Homework 3 (due 30th Apr)", @assignment}

Due: April 30th

*** { @unit = "23rd Apr", @title = "Lecture 7: General games", @reading, @lecture, @foldout}

No-regret learning in general games and coarse correlated equilibria. No-swap regret and correlated equilibria. 

Readings:
- [Lecture Notes](https://www.vsyrgkanis.com/6853sp19/lecture06.pdf)

Further Readings:
- [Quality of Learning Outcomes Lecture Note](https://vsyrgkanis.com/lecture_notes/lecture08.pdf)

*** { @unit = "25th Apr", @title = "Lecture 8: Learning in General Games", @reading, @lecture, @foldout}

Reduction from no-regret to no-swap regret. Multi-agent RL. Algorithms and applications.

Readings:
- [Lecture Notes](https://www.vsyrgkanis.com/6853sp19/lecture06.pdf)

Further Readings:
- [Noah Golowich, Lecture Notes on Stochastic Games, Part I](https://www.mit.edu/~gfarina/6S890/lecture11.pdf)
- [Grandmaster Level AI Agent for Starcraft](https://www.nature.com/articles/s41586-019-1724-z)

*** { @unit = "30th Apr", @title = "Homework 4 (due 7th May)", @assignment}

Due: May 7th

** Data Science for Auctions and Mechanisms

*** { @unit = "30th Apr", @title = "Lecture 9: Auctions and mechanisms", @reading, @lecture, @foldout}

Basics (truthfulness, Vickrey auction) and applications (GSP, GFP, VCG etc). Sponsored search. Procurement auctions (oil lease, government procurement, energy grid). Budgets.

*** { @unit = "2nd May", @title = "Lecture 10: Learning in auctions", @reading, @lecture, @foldout}

*** { @unit = "7th May", @title = "Homework 5 (due 14th May)", @assignment}

*** { @unit = "7th May", @title = "Lecture 11: Mechanism design", @reading, @lecture, @foldout}

*** { @unit = "9th May", @title = "Lecture 12: Simple vs optimal mechanisms", @reading, @lecture, @foldout}

*** { @unit = "14th May", @title = "Homework 6 (due 21st May)", @assignment}

*** { @unit = "14th May", @title = "Lecture 13: Learning mechanisms from samples", @reading, @lecture, @foldout}

*** { @unit = "16th May", @title = "Lecture 14: Online optimization of mechanisms", @reading, @lecture, @foldout}

*** { @unit = "21st May", @title = "Homework 7 (due 28th May)", @assignment}

** Further Topics

*** { @unit = "21st May", @title = "Lecture 15: Econometrics in games and auctions", @reading, @lecture, @foldout}

*** { @unit = "23rd May", @title = "Lecture 16: A/B testing in markets", @reading, @lecture, @foldout}

*** { @unit = "28th May", @title = "Homework 8 (due 5th Jun)", @assignment}

** Guest Lectures

*** { @unit = "28th May", @title = "Mechanism Design for LLMs (Renato Paes Leme; Google)", @reading, @lecture, @foldout}

*** { @unit = "30th May", @title = "Autobidding and Sponsored Search (Kshipra Bhawalkar; Google)", @reading, @lecture, @foldout}

*** { @unit = "4th Jun", @title = "TBA", @reading, @lecture, @foldout}




