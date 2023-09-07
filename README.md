Project name: AlphaPong

Description:

AlphaPong is a pong game where the AI agent learns to play the game by
competing against itself using a technique called self-play
reinforcement learning. The game combines the excitement of Pong with
the power of artificial intelligence to create a challenging and
adaptive gameplay experience. In AlphaPong, you have the opportunity to
witness the AI agent evolve and improve its gameplay skills over time.
The AI opponent is trained using a Deep Q-Learning Network (DQN)
algorithm, which enables it to make intelligent decisions based on past
experiences and learned strategies.
During gameplay, the AI agent controls one paddle, while its opponent is also controlled by the same AI agent. The game objective remains the same: score more points than your opponent by hitting the ball past their paddle. However, what makes AlphaPong unique is that the AI agent learns from its own gameplay experiences to continuously refine its decision-making process.
The AI agent starts with limited knowledge about the game and makes random moves in the initial stages. As the game progresses, the AI agent collects data about its actions and their outcomes, building a memory buffer of experiences. It then uses this data to train its DQN model and improve its future gameplay.
The training process involves adjusting the DQN model's weights to maximize the expected rewards obtained from the game. By using a technique called experience replay, the AI agent samples and learns from a batch of past experiences, enhancing its decision-making capabilities and optimizing its gameplay strategy.
Throughout the training process, the AI agent gradually refines its understanding of the game dynamics, such as ball trajectory and opponent behavior. As a result, it becomes more adept at predicting the ball's movement, strategically positioning its paddle, and outsmarting its own AI-controlled opponent.
AlphaPong provides an exciting opportunity to observe the remarkable ability of reinforcement learning algorithms to learn and adapt through self-play.
