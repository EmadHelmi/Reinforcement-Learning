# Reinforcement-Learning

[![N|Logo](http://emadhelmi.com/files/SmallTrans.png)](http://emadhelmi.com)

I have developed two famous [Reinforcement-Learning](https://en.wikipedia.org/wiki/Reinforcement_learning) algorithms: [Q Learning](https://en.wikipedia.org/wiki/Q-learning) and [SARSA](https://en.wikipedia.org/wiki/State-Action-Reward-State-Action).
**This was one of my HomeWorks at the university.**

### Files Description

In the project there are some files which i  explain them here:

| File | Description |
| ------ | ------ |
| map.csv | Map File of the grid in `csv` format |
| q_learning.py | Implementation of `Q-Learning algorithm` |
| q_learning_q.csv | The `Q` matrix after all episodes of the `Q-Learning algorithm` algorithm  |
| sarsa.py | Implementation of `SARSA algorithm` |
| sarsa_q.csv | The `Q` matrix after all episodes of the `SARSA` algorithm  |
| ProblemDefinition.pdf | Definition of the problem and the grid in `Persian` |


### Map File

Here is the grid which i mapped it into the `map.csv` file:

![N|Grid](http://emadhelmi.com/files/reinforcement_problem_grid.png)

For each cell in this grid you must define the reward to each other cells. if you have no route to a cell from another cell, you must set the equivalent cell in the map file with a number **less than** `-1`. and for each cell to the black cells i have considered `-1` reward. and for others you can consider any **positive** reward.
