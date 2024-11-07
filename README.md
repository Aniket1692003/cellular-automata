# Conway's Game of Life

## Introduction

Conway's Game of Life is a cellular automaton devised by the British mathematician John Horton Conway in 1970. It is a zero-player game, meaning its evolution is determined by its initial state, requiring no further input from human players. The game consists of a grid of cells that can live, die, or multiply based on a few mathematical rules.

## Rules

1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

## Implementation

This project implements Conway's Game of Life using Python and Pygame. Pygame is a set of Python modules designed for writing video games. It includes computer graphics and sound libraries.

### Prerequisites

- Python 3.x
- Pygame

### Installation

To install Pygame, use pip:

```bash
pip install pygame
