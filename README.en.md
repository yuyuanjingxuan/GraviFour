# 🔄 Gravity Change Connect Four

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![CI](https://github.com/yuyuanjingxuan/GraviFour/actions/workflows/ci.yml/badge.svg)](https://github.com/yuyuanjingxuan/GraviFour/actions/workflows/ci.yml)
[![Single File](https://img.shields.io/badge/Single%20File-HTML5-blue)]()
[![No Build](https://img.shields.io/badge/No%20Build-Required-green)]()
[![Players](https://img.shields.io/badge/Players-1~2-orange)]()

**Author**: [yuyuanjingxuan](https://github.com/yuyuanjingxuan)

[中文 README](README.md)

A unique variant of Connect Four where gravity direction **randomly changes** to a new direction every few moves, causing pieces to redistribute!

## 💡 Name Origin

**GraviFour** = **Grav**ity + Connect **Four** — Connect Four where gravity randomly changes direction (not just flips) and pieces redistribute.

## 🎮 Game Rules

1. **Basic Rules**: Click the board to drop pieces. First player to connect 4 same-color pieces (horizontally, vertically, or diagonally) wins
2. **Gravity Mechanism**: Pieces fall automatically due to gravity
3. **Gravity Change**: Gravity changes to a **new random direction** (never the same as the current one), with 3 modes: Fixed Interval (every N moves, 4/6/8/10/12), Random Interval (every 4~12 moves), Fixed Direction (normal Connect Four)
   - ⬇️ Gravity Down: Drop from top, pieces settle at bottom
   - ⬆️ Gravity Up: Drop from bottom, pieces settle at top
   - ⬅️ Gravity Left: Drop from the right side, pieces settle at the left
   - ➡️ Gravity Right: Drop from the left side, pieces settle at the right
   - ⚠️ A prominent flashing warning appears **2 moves in advance**, telling you when and to which direction gravity will change
4. **Redistribution**: When gravity changes, all pieces automatically redistribute to the new gravity direction
5. **Win Detection**: After a gravity change redistributes the pieces, wins are checked again — if one player connects 4, they win; if **both** players connect 4, it's a draw
6. **Timer & Pass**: Each move has a 30-second limit (live countdown, turns red and flashes in the last 5 seconds); timeout forces a switch. You can also press "Pass" to skip your move
7. **Locked After Start**: Once the first piece is dropped, game mode, board size, and AI difficulty are locked — press "Restart" to change them

## 🎯 Features

- 🎨 Beautiful gradient background and 3D pieces
- 🎲 3 gravity change modes (Fixed Interval / Random Interval / Fixed Direction) with a 2-move advance warning
- 📐 Adjustable board size (6×7 / 7×7 / 7×8 / 8×8 / 8×9)
- 🤖 PVE mode with 4 AI difficulty levels
- ⏱️ 30-second per-move countdown, timeout forces a switch
- ⏭️ Pass button
- 🔊 Web Audio synthesized sound effects and BGM, with a one-click music toggle
- 🏆 Win/Draw notifications (including post-gravity-change win detection)
- 🌐 Chinese / English interface
- 📱 Responsive design, supports mobile and tablet
- 🔄 Restart functionality

## 🚀 Quick Start

Simply open `index.html` in your browser to start playing!

No installation or build tools required.

## 📝 Game Example

| Gravity Down (Default) ⬇️ | After Change (Gravity Up) ⬆️ |
|:---:|:---:|
| Drop from top, pieces settle at bottom | Drop from bottom, pieces settle at top |
| ![Gravity Down](images/screenshot-gravity-down.png) | ![Gravity Up](images/screenshot-gravity-up.png) |

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

An innovative variant of the classic Connect Four game.

---

[Back to Top](#-gravity-change-connect-four)