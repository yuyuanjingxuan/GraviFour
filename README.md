# 🔄 重力变换四子棋

[![Play Online](https://img.shields.io/badge/▶️_Play%20%20Online-GraviFour-brightgreen)](https://yuyuanjingxuan.github.io/GraviFour/)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](LICENSE)
[![CI](https://github.com/yuyuanjingxuan/GraviFour/actions/workflows/ci.yml/badge.svg)](https://github.com/yuyuanjingxuan/GraviFour/actions/workflows/ci.yml)
[![Single File](https://img.shields.io/badge/Single%20File-HTML5-blue)]()
[![No Build](https://img.shields.io/badge/No%20Build-Required-green)]()
[![Players](https://img.shields.io/badge/Players-1~2-orange)]()

**作者 / Author**: [yuyuanjingxuan](https://github.com/yuyuanjingxuan)

[English README](README.en.md)

一个独特的四子棋变体，每隔若干手重力方向会**随机变换**为新方向，棋子会随着重力重新分布！

## 💡 名字由来

**GraviFour** = **Grav**ity（重力）+ Connect **Four**（四子棋）—— 重力会随机变换方向（不只是反向）、棋子会重新分布的四子棋。

## 🎮 游戏规则

1. **基本规则**：点击棋盘投放棋子，先连成4个同色棋子（横、竖、斜）者获胜
2. **重力机制**：棋子受重力影响自动下落
3. **重力变换**：重力会变为一个**新的随机方向**（不会与当前方向相同），支持 3 种模式：固定间隔（每 N 手，可选 4/6/8/10/12）、随机间隔（每 4~12 手）、固定方向（普通四子棋）
   - ⬇️ 重力向下：从顶部投放，棋子靠底部
   - ⬆️ 重力向上：从底部投放，棋子靠顶部
   - ⬅️ 重力向左：从右侧投放，棋子靠左侧
   - ➡️ 重力向右：从左侧投放，棋子靠右侧
   - ⚠️ 变化前 **2 手**会弹出醒目的闪烁预告，告诉你何时变为哪个方向
4. **重新分布**：重力变化时，所有棋子会自动重新分布到新的重力方向
5. **胜负判定**：重力变化导致棋子重新分布后也会检测胜负——一方连成 4 子判胜；若双方都连成 4 子则判和棋
6. **限时与跳过**：每手棋限时 30 秒（界面实时倒计时，最后 5 秒变红闪烁），超时强制换人；也可点“跳过”主动放弃行棋
7. **开局锁定**：第一手棋落下后，游戏模式、棋盘大小、AI 难度即被锁定，需“重新开始”后才能更改

## 🎯 特色功能

- 🎨 精美的渐变背景和3D棋子效果
- 🎲 3 种重力变换模式（固定间隔 / 随机间隔 / 固定方向）+ 提前 2 手醒目预告
- 📐 可调节棋盘大小（6×7 / 7×7 / 7×8 / 8×8 / 8×9）
- 🤖 PVE 模式，4 档 AI 难度
- ⏱️ 每手棋 30 秒倒计时，超时强制换人
- ⏭️ 跳过（Pass）按钮
- 🔊 Web Audio 合成音效与 BGM，可一键开关音乐
- 🏆 胜利/平局提示（含重力变化后的胜负判定）
- 🌐 中英文界面
- 📱 响应式设计，支持手机和平板
- 🔄 重新开始功能

## 🚀 快速开始

### ▶️ 在线游玩（推荐）

直接打开 [https://yuyuanjingxuan.github.io/GraviFour/](https://yuyuanjingxuan.github.io/GraviFour/) 即可开始游戏，无需安装！

### 📥 本地运行

直接在浏览器中打开 `index.html` 即可开始游戏！

无需任何安装或构建工具。

## 📝 游戏示例

| 重力向下（默认）⬇️ | 重力变换后（向上）⬆️ |
|:---:|:---:|
| 顶部投放，棋子靠底部 | 底部投放，棋子靠顶部 |
| ![重力向下](images/screenshot-gravity-down.png) | ![重力向上](images/screenshot-gravity-up.png) |

## 📄 许可证

本项目采用 [GNU AGPL-3.0 许可证](LICENSE) - 详见 [LICENSE](LICENSE) 文件。

这意味着：任何人都可以自由使用、修改、分发本项目的代码（包括商用），但**修改后的版本如果部署为网络服务供他人使用，也必须公开其完整源代码**。这是为了防止有人拿走代码改一改就闭源上线运营。

另外，"GraviFour"（重力变换四子棋）这一名称及相关标识**不包含在开源授权范围内**，未经许可不得用于其他产品的宣传、命名或商店 listing——详见 LICENSE 文件末尾的附加声明。

## 🙏 致谢

经典四子棋游戏的创新变体。

---

[返回顶部](#-重力变换四子棋)