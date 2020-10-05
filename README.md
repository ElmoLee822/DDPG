# DDPG
Deep Deterministic Policy Gradient. \
It is an enhanced version of actor-critic, combined with the DQN algorithm. It is a combination of value-based and policy-based methods. When selecting an action, \
Deterministic changes the original policy gradient selection action process. Deterministic only selects continuous actions. An output is used as an action. \
The policy network is an actor, which outputs an action (action-selection). The value network is a critic (evaluator), used to evaluate the actor's network selected actions (action value estimated).
