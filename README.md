# Pirate_Intelligent_Agent_Design_Defense

## Overview

This project implements a reinforcement learning solution using deep Q-learning to train a pirate agent to find treasure in a maze. The environment is structured in a grid format, where the agent must learn an optimal path through trial and error. The project was completed in a Jupyter Notebook as part of an academic course on artificial intelligence.

## What I Did

I was provided with Python files that defined the maze environment and utility classes. My task was to complete the code for the intelligent agent using a deep Q-learning algorithm. I created the model architecture, implemented the experience replay mechanism, and wrote the training loop. I used neural networks to estimate Q-values and incorporated an epsilon-greedy strategy to balance exploration and exploitation.

## Technologies Used

- Python 3
- Jupyter Notebook
- NumPy
- TensorFlow / Keras
- Custom environment provided in `.py` files

## How to Run

1. Upload the provided zipped folder into your Jupyter Notebook environment (e.g., in Apporto).
2. Unzip the folder and open the Jupyter Notebook file.
3. Run the notebook sequentially to train and test the pirate agent.
4. Do **not** modify the original `.py` environment files.

---

## Reflection

### Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?

I was given a set of `.py` files that created the maze environment and handled rendering and state transitions. I wrote the deep Q-learning code in the Jupyter Notebook, including the model structure, replay buffer, training loop, and evaluation logic. I also handled hyperparameter tuning and policy control for exploration.

### Connect your learning from throughout this course to the larger field of computer science:

#### What do computer scientists do and why does it matter?

Computer scientists solve real-world problems using algorithms, data structures, and logic. Their work drives innovation in fields like AI, cybersecurity, healthcare, and finance. By designing efficient and ethical systems, they help improve the way we live and work.

#### How do I approach a problem as a computer scientist?

I break down complex problems into smaller, manageable pieces. I define inputs, outputs, and edge cases, then design and iterate on algorithms to solve them. I also rely on data-driven testing to refine my solutions.

#### What are my ethical responsibilities to the end user and the organization?

My ethical responsibilities include ensuring fairness, transparency, and security in the systems I build. I must consider how users interact with the software and ensure it doesn’t unintentionally cause harm. I’m also accountable to the organizations that trust my work to meet business goals safely and responsibly.

---

## License

This project is for educational purposes and is not intended for commercial use.
