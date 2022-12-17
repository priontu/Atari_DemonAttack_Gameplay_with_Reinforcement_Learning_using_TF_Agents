# Atari_DemonAttack_Gameplay_with_Reinforcement_Learning_using_TF_Agents
Implementing Reinforcement Learning to develop an Agent that teaches itself to play the DemonAttack Atari Game. The Agent was developed using tensorflow, TF-Agents and OpenAI Gym.

Reinforcement learning (RL) is the area of machine learning concerned with intelligent agents that take actions in an environment in order to maximize the notion of cumulative reward.

For this project, we use the OpenAI Gym Atari environment, and we train an agent to play efficiently in this environment.

The model consists of the following components:

Agent -- The agent is the decision-maker (bot) that interacts with the environment and learns the decisions that maximize the rewards.

Environment -- The environment is the space with which the agent interacts to obtain the rewards. 

Observation space -- This is the current state of the environment that the agent observes.

Action space -- This is the decision that the robot takes at each step.

Reward -- In this case, the score of the game, that the agent will try to maximize.

Policy -- A policy defines the learning agent's way of behaving at a given time. It is a mapping from perceived states of the environment to actions to be taken when in those states.

Agent's Gameplay before training:

![myAgentPlays-7](https://user-images.githubusercontent.com/61733487/208226031-7aeaae0a-75c0-470f-b1a0-c547336cbabb.gif)

Agent's Gameplay mid-training:

![myAgentPlays_3](https://user-images.githubusercontent.com/61733487/208226207-b470cea0-9af6-451f-867c-0d6cb8543168.gif)

The agent learned some new things -- now it knows it needs to shoot the enemy bats and kill them in order to gain points, but it hasn't yet learned how to stay slive by evading the enemy fire.

Agent's Gameplay after training:

![myAgentPlays_10](https://user-images.githubusercontent.com/61733487/208226094-776275b4-0219-4a16-9f8d-9a5e26614e9b.gif)

At this point in the training, we have reached Human-Level Control in the Gameplay.

We can see that the Gameplay has improved. The agent has learned how to shoot and kill the enemy in order to earn rewards, but it has also learned to evade enemy gunfire which would allow it to earn greater rewards. However, it definitely requries some more training, since the enemy seems to have some more tricks up its sleeve, like increasing speed of movement and gunfire, which the agent hasn't adapted to yet. These would be the same setbacks a human player would face, which he would improve on by playing the game some more. The same applies to our agent. 
