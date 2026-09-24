# Bomberman

A multiplayer **Bomberman-inspired game** developed as a university project. The game focuses on local **player-versus-player (PvP)** gameplay, where players compete against each other using bombs, destructible environments, and strategic movement.

> 🎮 **No AI is used in this project — the game is designed specifically around PvP gameplay.**

## 🎯 Project Overview

The goal of the project was to recreate the core gameplay experience of classic Bomberman while implementing the game mechanics and interactions from scratch.

Players navigate through a destructible map, place bombs, avoid explosions, and try to eliminate their opponent.

### Main Features

* 👥 **Player vs Player gameplay**
* 💣 Bomb placement and explosion mechanics
* 🧱 Destructible blocks
* 🗺️ Grid-based game map
* 💥 Explosion propagation
* ❤️ Player elimination
* 🎮 Keyboard-based player controls
* 🏆 Competitive multiplayer gameplay
* 🔄 Real-time game state updates

## 🕹️ Gameplay

Each player starts on the game map and must use bombs strategically to defeat the opponent.

Bombs explode after a short delay and their explosion propagates through the map. Destructible blocks can be destroyed, while indestructible blocks stop explosions.

The game requires players to balance **offensive strategies** with **careful positioning and timing**.

## 🛠️ Technologies

The project was developed as part of a university software engineering project.

**Technologies & Concepts:**

* Java
* Object-Oriented Programming
* Game development fundamentals
* Event-driven programming
* Collision detection
* Game state management
* GUI development

## 📂 Project Structure

```text
Bomberman/
└── SZFM-Bomberman-main/
    ├── src/
    └── ...
```

The project source code and implementation details can be found in the repository.

## 🎮 Controls

| Player   | Movement        | Bomb    |
| -------- | --------------- | ------- |
| Player 1 | `W` `A` `S` `D` | `Space` |
| Player 2 | Arrow Keys      | `Enter` |

> Controls may depend on the current game configuration.

## 🧩 Game Mechanics

### Bombs

Players can place bombs on the map. After the countdown expires, the bomb explodes in multiple directions.

### Destructible Environment

Bomb explosions can destroy designated blocks, opening new paths through the map.

### Explosion Detection

Explosion areas are calculated based on the bomb's position and the surrounding map elements. Solid obstacles prevent the explosion from continuing further.

### PvP

The game is designed around two-player competition. Players must use the environment and bomb placement to outmaneuver their opponent.

## 🎓 University Project

This project was created as part of a **University of Debrecen** university project and was developed to practice software engineering and object-oriented programming concepts in a larger application.

The project provided practical experience with:

* Designing a game architecture
* Implementing interactive game mechanics
* Managing application state
* Handling user input
* Working with multiple interacting objects
* Developing and debugging a larger Java application

## 📌 Project Status

The project was developed as a university project and represents an implementation of the core Bomberman gameplay concept with a focus on **local PvP gameplay**.

## 👤 Author

**Attila Tasnadi & Kis Ábel**

Computer Science BSc
University of Debrecen

[GitHub](https://github.com/TasnadiAttila)
