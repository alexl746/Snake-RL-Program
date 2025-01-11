# Exploring-ML
The snake reinforcement learning program I created as a result of watching David Silver's lectures on RL and tutorials online. Run agent.py to run the program.

Model does not save in-between sessions, it trains in real-time.
Note that sometimes the program runs poorly even if you leave it for a while, this is due to the epsilon greedy approach to the machine learning, where the program will act either randomly or take an action from the neural network. As the program goes through more iterations the proportion of random to calculated actions goes towards more calculated actions, but if it doesn't hit enough apples in the beginning the neural network will not get sufficient data so it won't return very good calculated actions. If it's not performing well, it is better to just restart the program.
