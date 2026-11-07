# 👋 yeungtuzi

主要折腾 **摩尔线程 M1000（MTGPU / ARM64）** 上的系统、桌面、虚拟化与游戏栈。
下面这些项目都和 MTGPU 有关，名字里不一定带 `mtgpu`。

## 🎮 游戏与模拟器

| 项目 | 说明 |
|---|---|
| [mtgpu-steam-fex](https://github.com/yeungtuzi/mtgpu-steam-fex) | Steam（arm64）+ FEX-Emu + Proton ARM64 跑 Windows 游戏：安装脚本、`M1000ARM64` 兼容工具、DXVK 2.3.1、720p Game Mode |
| [mtgpu-pegasus](https://github.com/yeungtuzi/mtgpu-pegasus) | Pegasus 模拟器前端：aarch64 构建、`/opt/pegasus` 安装、`Game Mode - 模拟器`（720p@60，退出恢复 2880x1800@120） |
| [reunion-lite](https://github.com/yeungtuzi/reunion-lite) | 《红色警戒2 重聚未来》战役启动器：Windows x64 / Linux arm64（原生 Qt6），0.2 起支持 ARM64 + MTGPU，可真正进任务 |

## 🖥️ 桌面与虚拟化

| 项目 | 说明 |
|---|---|
| [mtgpu-kde](https://github.com/yeungtuzi/mtgpu-kde) | KDE Plasma 6.8 for M1000（实验性，未做稳定性验证）：构建记录、EDR、半屏修复、fcitx5 配置 |
| [mtgpu-woa](https://github.com/yeungtuzi/mtgpu-woa) | 在 KVM/QEMU 上跑 Windows 11 ARM64：显示走 RDP/RemoteFX，M1000 vfio-pci 直通，无专有组件 |

## ⚙️ 工具

| 项目 | 说明 |
|---|---|
| [btop-xtu](https://github.com/yeungtuzi/btop-xtu) | btop++ fork：MUSA（摩尔线程）等国产 GPU 支持 + 自适应 GPU 布局 |

## 🧩 相关的红警2 生态

- [vera20k](https://github.com/yeungtuzi/vera20k) — 用 Rust 重写的《红警2：尤里的复仇》引擎
- [vera20k-launcher](https://github.com/yeungtuzi/vera20k-launcher) — VERA20K 的战役/地图启动器

## 🔗 主题

- 仓库统一打了 [`mtgpu`](https://github.com/topics/mtgpu) / [`moore-threads`](https://github.com/topics/moore-threads) topic；
- GitHub List：**[MUSA](https://github.com/yeungtuzi/lists)** — `mtgpu-*`、`reunion-lite`、`Xiaotu-LLM` 的合集。

更多仓库见 [Repositories](https://github.com/yeungtuzi?tab=repositories)。
