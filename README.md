# Q-Learning-Taxi-game

Game configurations:

Taxi
The taxi needs to pick up and drop passengers.
Input: actions ranging [0,1,2,3,4,5]
Observations: 500 possible states
Reward: given by the API
Done: if the game is completed

RL algorithms used:

Q learning algorithm

Modelling part:

Didn't use policy much.
All we do is create a look up table to find best actions for thoses states and update value of those (state, action) pair with every interaction

Interaction:

Make random actions. It will some times pick best action based on exploration rate.

Number of episodes played to learn: 50000
Number of episodes played to test: 100

![Snapshot](https://github.com/phaniram-sayapaneni/Simple-Q-learning-using-taxi-game/blob/master/Taxi%20game.png)