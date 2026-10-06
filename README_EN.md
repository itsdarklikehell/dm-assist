# DM Assist

**A tool for Dungeon Masters (DM/GM) of tabletop role-playing games**

[![Version](https://img.shields.io/github/v/release/Technohamster-py/dm-assist)](https://github.com/Technohamster-py/dm-assist/releases)
[![C++ Standard](https://img.shields.io/badge/C%2B%2B-17-blue)](https://github.com/Technohamster-py/dm-assist)
[![Qt Version](https://img.shields.io/badge/Qt-6.0%2B-brightgreen.svg)](https://www.qt.io/)

**DM Assist** is a modern, intuitive application designed to make running games easier and more engaging. The project started as a convenient music player for switching tracks with one click, but grew into a full system for managing music, combat, maps, and campaigns.

## Features

| Module | Description |
|--------|-------------|
| Music | Multi-channel player with independent volume, playlists, and hotkeys |
| Initiative Tracker | Combat management: HP, AC, statuses, sorting, player access |
| Map with Tools | Fog of war, dynamic lighting, drawing tools |
| Campaign Manager | Campaign notes, NPC tracking, session history |

## Supported Systems

- D&D 5e
- Pathfinder
- Call of Cthulhu
- Custom systems

## Installation

### From Source

```bash
git clone https://github.com/itsdarklikehell/dm-assist.git
cd dm-assist
mkdir build && cd build
cmake ..
cmake --build .
```

### Requirements

- C++17 compiler
- Qt 6.0+
- CMake 3.16+

## Usage

Run the executable after building:

```bash
./dm-assist
```

## License

MIT
