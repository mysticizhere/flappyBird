# Flappy Bird AI using NEAT

## Overview

This project implements an AI-controlled Flappy Bird game using NEAT (NeuroEvolution of Augmenting Topologies), a popular genetic algorithm for evolving artificial neural networks. The AI learns to play the game by training multiple generations of bird agents using NEAT, improving their performance over time to achieve higher scores.

The game is built using the Pygame library, and NEAT is used to optimize the neural network controlling the birds' movements. The AI learns to avoid the pipes and score points by flying through the gaps between the pipes.

## How to Use

1. **Installation**: Before running the Flappy Bird AI, make sure you have Python installed on your system. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/flappy-bird-ai.git
   cd flappy-bird-ai
   ```

2. **Install Dependencies**: Install the required dependencies using pip:

   ```bash
   pip install pygame
   pip install neat-python
   ```

3. **Run the AI**: Start the Flappy Bird AI by running the `run.py` script:

   ```bash
   python run.py
   ```

4. **Gameplay**: The AI will start training the bird agents to play Flappy Bird. Observe how the birds improve their performance in each generation to achieve higher scores.

5. **Watching the AI**: You can observe the AI in action as it plays Flappy Bird. The birds will use the learned neural network to control their movements and avoid the pipes.

6. **Stopping the AI**: To stop the AI and exit the game, simply close the game window.

## How NEAT Works

NEAT is an evolutionary algorithm used to optimize artificial neural networks. It starts with a population of random neural networks (genomes) and evolves them over generations by applying genetic operations such as mutation and crossover. The AI uses NEAT to improve the neural networks controlling the bird's movements, allowing them to learn to play the game more effectively.

## Customization

You can experiment with different parameters to customize the behavior and performance of the AI:

- **Neural Network Complexity**: Adjust the complexity of the neural network by modifying the configuration file (`config-feedforward.txt`). You can change the number of hidden layers, nodes per layer, activation functions, etc.

- **Population Size**: Change the number of bird agents in each generation by modifying the `main` function in `run.py`.

- **Training Generations**: You can specify the number of generations the AI will train in the `run` function in `run.py`.

## Contributions and Issues

Contributions and feedback are welcome! If you encounter any issues or have suggestions for improvements, please open an issue in the GitHub repository. If you'd like to contribute to the project, feel free to submit pull requests.

## Credits

This project is inspired by the original Flappy Bird game and the NEAT algorithm developed by Kenneth O. Stanley. Special thanks to the Pygame and NEAT-Python communities for providing valuable tools and libraries that make this project possible.
