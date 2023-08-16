# Reinforcement Learning

Reinforcement Learning is a feedback-based Machine learning technique in which an agent learns to behave in an environment by performing the actions and seeing the results of actions. For each good action, the agent gets positive feedback, and for each bad action, the agent gets negative feedback or penalty.

In Reinforcement Learning, the agent learns automatically using feedbacks without any labeled data, It is Unsupervised learning. Since there is no labeled data, so the agent is bound to learn by its experience only.

The agent interacts with the environment and explores it by itself. The primary goal of an agent in reinforcement learning is to improve the performance by getting the maximum positive rewards.

The agent learns with the process of hit and trial, and based on the experience, it learns to perform the task in a better way. Hence, we can say that **"Reinforcement learning is a type of machine learning method where an intelligent agent (computer program) interacts with the environment and learns to act within that."** How a Robotic dog learns the movement of his arms is an example of Reinforcement learning.

### Upper Confidence Bound (UCB) [Code](https://github.com/anupam215769/Reinforcement-Learning-ML/blob/main/Upper%20Confidence%20Bound%20(UCB)/upper_confidence_bound.ipynb) OR <a href="https://colab.research.google.com/github/anupam215769/Reinforcement-Learning-ML/blob/main/Upper%20Confidence%20Bound%20(UCB)/upper_confidence_bound.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

### Thompson Sampling [Code](https://github.com/anupam215769/Reinforcement-Learning-ML/blob/main/Thompson%20Sampling/thompson_sampling.ipynb) OR <a href="https://colab.research.google.com/github/anupam215769/Reinforcement-Learning-ML/blob/main/Thompson%20Sampling/thompson_sampling.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

> Don't forget to add Required Data files in colab. Otherwise it won't work.


## Upper Confidence Bound (UCB)

UCB is a deterministic algorithm for Reinforcement Learning that focuses on exploration and exploitation based on a confidence boundary that the algorithm assigns to each machine on each round of exploration. These boundary decreases when a machine is used more in comparison to other machines.

#### Algorithm

![algo](https://i.imgur.com/43phpVi.png)

![algo](https://i.imgur.com/fAkZbip.png)

![algo](https://i.imgur.com/dW3U9St.png)

## Thompson Sampling

Thompson Sampling (also sometimes referred to as the Bayesian Bandits algorithm) takes a slightly different approach; rather than just refining an estimate of the mean reward it extends this, to instead build up a probability model from the obtained rewards, and then samples from this to choose an action.

In this way, not only is an increasingly accurate estimate of the possible reward obtained, but the model also provides a level of confidence in this reward, and this confidence increases as more samples are collected. This process of updating your beliefs as more evidence becomes available is known as **Bayesian Inference**.

![bay](https://i.imgur.com/f1AGrqN.png)

#### Bernoulli Thompson Sampling

Now, instead of each socket returning a varying amount of charge, each socket will either return some charge or no charge; the rewards have only two possible values: 1 when the chosen socket supplies a charge and 0 when it doesn’t. When a random variable has only two possible outcomes its behaviour can be described by the **Bernoulli distribution**.

So now, instead of the amount of charge varying per socket, the probability of a socket producing a charge varies with each socket. We want to find the socket with the highest probability of returning a charge, rather than the socket that gives the most charge.

#### Algorithm

![algo](https://i.imgur.com/ixek7ur.png)


![algo](https://i.imgur.com/stKw5kH.png)


## Comparison

![comp](https://i.imgur.com/WpE8GKl.png)

## Related Repositories

### [Data Preprocessing](https://github.com/anupam215769/Data-Preprocessing-ML)

### [Regression](https://github.com/anupam215769/Regression-ML)

### [Classification](https://github.com/anupam215769/Classification-ML)

### [Clustering](https://github.com/anupam215769/Clustering-ML)

### [Association Rule Learning](https://github.com/anupam215769/Association-Rule-Learning-ML)






