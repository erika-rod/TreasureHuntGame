# TreasureHuntGame
## Overview
This project involved creating an intelligent agent, a pirate NPC, that learns to navigate a maze to find hidden treasure. The agent uses deep Q-learning, a reinforcement learning algorithm, to determine optimal routes through the maze based on rewards for reaching the treasure and penalties for encountering obstacles. The primary objective was to develop an agent that can consistently find the shortest path to the treasure, balancing exploration and exploitation during training. 

## Code Summary 
 - Given Code: The initial project framework provided code to set up the environment, manage epusodes, and handle rewards and penalties for the agent's actions. This included basic setup for rewards in response to reaching or missing the target.
 - Code Created: I implemented the deep Q-learning model from scratch, designing the neural network architecture and creating the logic for exploration versus exploitation decisions. I configured the training loop, handled memory storage, and optimized hyperparameters like the epsilon value, epochs, and batch sizes to ensure efficient learning.

## Reflection on Learning
### Connecting Course Learnings to Computer Science
Throughout this course, I’ve gained hands-on experience with concepts central to reinforcement learning, neural networks, and the broader field of artificial intelligence (AI) within computer science. Computer scientists focus on designing and optimizing algorithms that solve problems efficiently, often working with data-driven models and systems that impact various fields, from AI to cybersecurity. Projects like this one reveal the importance of creating solutions that can learn from data and improve over time, ultimately solving real-world problems with minimal human intervention.

### Problem-Solving Approach as a Computer Scientist
Approaching this project as a computer scientist required careful analysis and iterative testing. I began by breaking down the problem into manageable components: defining the environment, establishing agent rewards, and then training the agent over several episodes to optimize its performance. Each stage demanded a balance between theoretical understanding and practical experimentation—testing various neural network configurations, modifying learning rates, and monitoring the results to fine-tune the model. This analytical, step-by-step approach is fundamental in computer science, where problem-solving often requires patience and an ability to adapt.

### Ethical Responsibilities to the End User and the Organization
When developing intelligent agents or any computational models, we bear a responsibility to both the end users and the organizations deploying our solutions. For end users, it’s critical to ensure that algorithms operate transparently and predictably, minimizing potential harm. In the context of this project, although a game agent may seem low-stakes, similar technology applied in high-stakes scenarios like medical diagnostics or autonomous driving must prioritize safety, accuracy, and fairness. For organizations, delivering reliable, well-tested code and being honest about its limitations are essential. Ethical responsibilities in computer science extend to creating robust, trustworthy systems that prioritize the welfare of users and the integrity of data.
