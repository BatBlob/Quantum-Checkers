# Quantum-Checkers

## Project Description

Strategy games such as chess, Go and Tic-tac-toe have proved to be an excellent medium of introducing quantum phenomenons to the general public in a fun way. These games introduce a quantum twist into these age old games and allow the players to experiment with quantum phenomenons such as superposition, entanglement etc. In this project we aim to bring this fun twist to the game of Checkers.

The aims of the project are listed below:
- Implement and simulate the quantum mechanical effects of entanglement and superposition in the pieces of checker board game.
- Attempt to give an intuitive sense of quantum mechanical effects of entanglement and superposition by:
    - Letting players of the game to play a split move resulting in superposition of states.
    - Letting players interact their pieces in superposition to create entangled states.
- Understand the present available quantum chess implementations to help with building the circuit for checkers.
- Implement the circuit for checkers game with a 6x6 board with 6 pieces for each player.

Some special elements in our Quantum Checkers are as follows:
- Player has a choice to make either a split move (giving superposition states of a piece) or a classical move.
- A piece in superposition or in a classical state can capture the pieces of the other player.
-  When a classical piece $p_0$ tries to capture another piece(s), $p_1$, either in superposition or entangled state, then the classical state of $p_1$ is determined and $p0$ either captures $p_1$ by jumping over it, or occupies $p_1's$ position.
- When a piece in superposition, $p_0$, tries to capture another piece, $p_1$, in superposition then the two pieces are entangled together. The state is only resolved when a third classical piece $p_2$ tries to interact with the entangled pieces.