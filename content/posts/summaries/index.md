---
title: "Literature Summaries"
date: 2022-03-15
publishdate: 2022-03-15
resources:
- name: featuredImage
  src: "cover.jpg"
---
### Finding a survey and more.

Over the past week, I have continued my research in procedural content generation in video games. To do so, I have a survey of the field, as well as two more interesting literature articles that I will summarize below.

### Survey Article:

### Procedural content generation for games: A survey

**Citation:**  Hendrikx, M., Meijer, S., Van Der Velden, J., & Iosup, A. (2013). Procedural content generation for games: A survey. ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM), 9(1), 1-22.

**Goal:**  The goal of this article was to create a comprehensive survey of the field of Procedural Content Generation in video games. This article examines the various methods that are used and surveys the methods in practice in commercial games.

 All methods surveyed in this article are tackling Procedural Content Generation in video games. The main groups of methods discussed are Pseudo-Random Number Generators, Generative Grammars, Image Filtering, Spatial Algorithms, and Modeling and Simulation of ComplexSystems. None of these groups are particularly "leading", as groups are better for generating certain content types than others. The discussion of these methods was in the context of which content types are they used to generate. This article breaks down the various content elements of games and discusses the methods for that specific type of content.

  By researching specific methods further, I could use them in my work to experiment with content generation in my own game. Since this article breaks down elements of games, it would be easy for me to find which method to look further into for a particular part of my game. By utilizing these methods, I could explore Procedural Content Generation and experiment with my own game content.

### Literature Articles:

### Search-based procedural content generation for GVG-LG

**Citation:**  Zafar, A., Mujtaba, H., & Beg, M. O. (2020). Search-based procedural content generation for GVG-LG. Applied Soft Computing, 86, 105909.

**Goal:**  The goal of this article was to use a search-based approach to procedural content generation to created 2D video game levels.

In this article, the authors use the Feasible Infeasible Two Population genetic algorithm in order to generate 2D game levels. This type of algorithm generates some content, alters it through mutation and interbreeding, then evaluates the result using a fitness function. The algorithm maintains one feasible and one infeasible population. Generated content that satisfies the constraints is placed in the feasible population, while content that violates constraints is placed into the infeasible population. For their level generation, the authors test fitness by metrics of aesthetics and difficulty. Their results were that their level generator created levels for multiple 2D games that were aesthetically appealing, playable, and challenging.

### PCGRL: Procedural content generation via reinforcement learning

**Citation:**  Khalifa, A., Bontrager, P., Earle, S., & Togelius, J. (2020, October). PCGRL: Procedural content generation via reinforcement learning. In Proceedings of the AAAI Conference on Artificial Intelligence and Interactive Digital Entertainment (Vol. 16, No. 1, pp. 95-101).

**Goal:** The goal of this article is to utilize reinforcement learning in procedural content generation for video games.

In this article, the authors use a reinforcement learning framework for generating level designs for 2D video games. This type of generation is an iterative approach, rather than generating the entirety of a level at once. Their framework begins with a level populated by random tiles. Then, their agent makes a small change in the level. Each change is judged by the system with respect to the target goal of the level. The agent then receives a reward from the system that reflects how much closer the change has brought the level to its goal. After training their agent, they found that the agent only needed to change at most 40% of the initial tiles to design a successful level.
