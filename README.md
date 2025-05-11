# Rogue-like Dungeon Crawler

[![Python 3.10](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Curses](https://img.shields.io/badge/UI-curses-lightgrey.svg)](https://docs.python.org/3/library/curses.html)

Terminal-based dungeon crawler with procedural generation and entity-component-system architecture.

![Victory screen](/materials/victory.jpg)

```bash
git clone https://github.com/GrabCrabD/rogue.git
cd rogue
python3.10 main.py
# Follow menu help
```

main menu:
![Menu](/materials/main_menu_screen.png)

## Key Mechanics

- 21 procedurally generated levels
- 5 enemy types with unique AI
- Inventory management system
- Fog of war implementation
- Dynamic difficulty adjustment
- Ray-casting 3D mode

## Core Architecture

```mermaid
graph TD
  A[Domain Layer] --> B(Entities)
  C[Gameplay] --> D(Combat System)
  E[Rendering] --> F(2D/3D Views)
  G[Data] --> H(JSON Saves)
```

[Explore Rogue (1980) Gameplay and Enemy Mechanics](https://en.wikipedia.org/wiki/Rogue_(video_game)).
![2D gameplay](/materials/gameplay.png)
