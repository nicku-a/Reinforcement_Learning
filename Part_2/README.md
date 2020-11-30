# Part 2
This task was to create a random maze and solve it using Deep Q-learning. The agent cannot hold any memory other than the experience replay buffer, could not import anything from the environment, could not use any heuristics to solve the maze - this is a genuine Deep Q-learning solution.
### Random_environment.py
Creates a random maze to be solved, draws it and the policy, sets the rules
### Train_and_test.py
Trains the DQN for 10 minutes and then tests it
### Agent.py
Chooses actions, contains DQN and experience replay buffer
