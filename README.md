# Rogue-like Dungeon Crawler

[![Python 3.10](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Curses](https://img.shields.io/badge/UI-curses-lightgrey.svg)](https://docs.python.org/3/library/curses.html)

Terminal-based dungeon crawler with procedural generation and entity-component-system architecture.

## Features

### Core Architecture

```mermaid
graph LR
  A[Domain Layer] --> B(Entities/Components)
  C[Game Layer] --> D(AI/Combat Systems)
  E[Rendering] --> F(Curses/3D Raycasting)
  G[Data] --> H(JSON Save/Load)
