# 🔄 Gravity Reversal Connect Four

[![CI](https://github.com/yuyuanjingxuan/GraviFour/actions/workflows/ci.yml/badge.svg)](https://github.com/yuyuanjingxuan/GraviFour/actions/workflows/ci.yml)
[MIT License](LICENSE) | [中文 README](README.md)

A unique variant of Connect Four where gravity direction reverses every few turns, causing pieces to redistribute!

## 🎮 Game Rules

1. **Basic Rules**: Click on columns to drop pieces. First player to connect 4 same-color pieces (horizontally, vertically, or diagonally) wins
2. **Gravity Mechanism**: Pieces fall automatically due to gravity
3. **Gravity Reversal**: Gravity direction reverses every 6 turns
   - ⬇️ Gravity Down: Drop from top, pieces settle at bottom
   - ⬆️ Gravity Up: Drop from bottom, pieces settle at top
4. **Redistribution**: When gravity reverses, all pieces automatically redistribute to the new gravity direction

## 🎯 Features

- 🎨 Beautiful gradient background and 3D pieces
- 🔄 Innovative gravity reversal mechanism
- 📱 Responsive design, supports mobile and tablet
- 🏆 Win/Draw notifications
- 🔄 Restart functionality

## 🚀 Quick Start

Simply open `index.html` in your browser to start playing!

No installation or build tools required.

## 📝 Game Example

```
Gravity Down (Default)  After Reversal (Gravity Up)
⬇️                      ⬆️
┌─────┐                ┌─────┐
│     │                │●●●│
│●●●  │                │○○ │
│○○   │    →Reverse→   │   │
│     │                │   │
│     │                │   │
└─────┘                └─────┘
Drop from top           Drop from bottom
```

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

An innovative variant of the classic Connect Four game.

---

[Back to Top](#-gravity-reversal-connect-four)