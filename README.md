# FlappyBirdNEAT
Project Title: AI-Driven Flappy Bird Desktop Game
Introduction
This project embodies a desktop rendition of the popular Flappy Bird game, empowered by artificial intelligence (AI). The game employs the NeuroEvolution of Augmenting Topologies (NEAT) algorithm to train the AI. NEAT incrementally evolves a population of neural network topologies, meaning it starts with small, simple networks and expands the network structure as it discovers better solutions. The objective is to evolve an AI agent capable of proficiently navigating through the game environment.

Technologies Used
Pygame: Utilized for rendering the game environment and graphical interface.
numpy: Employs numerical operations essential for data handling and neural network operations.
neat-python: The driving force behind the neural network and genetic algorithm used to train the AI.
graphviz: Employed for visualizing the neural network topologies during the evolution process.
matplotlib: Utilized for plotting performance metrics and analysis.
File Structure
main.py: Contains the primary game logic, NEAT algorithm implementation, and the event handling required for game execution.
config-feedforward.txt: Configuration file for NEAT-python detailing the parameters for the neural network evolution.
assets/: Folder containing graphical assets required for rendering the game environment.
Implementation
The core of the project lies in integrating the NEAT algorithm (via neat-python) with the game logic coded using Pygame. The main.py script initializes the game, and the NEAT algorithm evolves a population of AI agents across generations to improve gameplay performance. Performance metrics are visualized using graphviz and matplotlib to provide insights into the evolution process and the learning curve of the AI agents.

Usage
Ensure all the mentioned libraries are installed.
Run main.py to launch the game and commence the AI training process.
Monitor the evolution of AI performance across generations and visualize neural network topologies using the provided visualization scripts.
Acknowledgement
The initial codebase and learning resources were predominantly contributed by TechWithTim, aiding in the foundational understanding of integrating NEAT with Pygame. This project was revisited and adapted years later, reflecting on the continuous allure and educational value of AI in gaming.
