# 🔄 Gravity Reversal Connect Four

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![CI](https://github.com/yuyuanjingxuan/GraviFour/actions/workflows/ci.yml/badge.svg)](https://github.com/yuyuanjingxuan/GraviFour/actions/workflows/ci.yml)

[中文 README](README.md)

A unique variant of Connect Four where gravity direction reverses every few turns, causing pieces to redistribute!

## 🎮 Game Rules

1. **Basic Rules**: Click the board to drop pieces. First player to connect 4 same-color pieces (horizontally, vertically, or diagonally) wins
2. **Gravity Mechanism**: Pieces fall automatically due to gravity
3. **Gravity Reversal**: Gravity direction reverses every 6 turns (down→up→left→right cycle)
   - ⬇️ Gravity Down: Drop from top, pieces settle at bottom
   - ⬆️ Gravity Up: Drop from bottom, pieces settle at top
   - ⬅️ Gravity Left: Drop from the right side, pieces settle at the left
   - ➡️ Gravity Right: Drop from the left side, pieces settle at the right
4. **Redistribution**: When gravity reverses, all pieces automatically redistribute to the new gravity direction

## 🎯 Features

- 🎨 Beautiful gradient background and 3D pieces
- 🔄 Innovative gravity reversal mechanism (all four directions)
- 📐 Adjustable board size (6×7 / 7×8 / 8×9)
- 🤖 PVE mode with 4 AI difficulty levels
- 🔊 Web Audio synthesized sound effects and BGM
- 🌐 Chinese / English interface
- 📱 Responsive design, supports mobile and tablet
- 🏆 Win/Draw notifications
- ⏱️ Per-turn timer (30s timeout auto-switches player)
- 🔄 Restart functionality

## 🚀 Quick Start

Simply open `index.html` in your browser to start playing!

No installation or build tools required.

## 📝 Game Example

| Gravity Down (Default) ⬇️ | After Reversal (Gravity Up) ⬆️ |
|:---:|:---:|
| Drop from top, pieces settle at bottom | Drop from bottom, pieces settle at top |
| ![Gravity Down](images/screenshot-gravity-down.png) | ![Gravity Up](images/screenshot-gravity-up.png) |

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

An innovative variant of the classic Connect Four game.

---

[Back to Top](#-gravity-reversal-connect-four)