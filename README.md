# 👋 yeungtuzi

**第一关注：[Xiaotu-LLM](https://github.com/yeungtuzi/Xiaotu-LLM)** —— 面向超大 MoE 模型的推理加速架构，
以 vLLM 插件形式提供：CPU MoE 引擎（AVX512-VNNI / BF16 / MXFP4 / FP8）+ GPU 流式长 prefill，
已支持 SM80（A100）与摩尔线程 MUSA（S4000 双卡）。其余仓库多围绕 **摩尔线程 M1000（MTGPU / ARM64）**
上的系统、桌面、工具链与游戏栈展开。

## 🧠 第一关注：LLM 推理

| 项目 | 说明 |
|---|---|
| [Xiaotu-LLM](https://github.com/yeungtuzi/Xiaotu-LLM) | **XTU = X Transformers Unity**：vLLM 主线插件 + CPU MoE 引擎，混合（CPU-expert + GPU）推理加速；12 小时满载压测通过；含 MUSA 初步支持 |
| [vllm](https://github.com/yeungtuzi/vllm) | vLLM fork，承载 XTU 相关的开发线 |

## 🎮 游戏与模拟器

| 项目 | 说明 |
|---|---|
| [mtgpu-steam-fex](https://github.com/yeungtuzi/mtgpu-steam-fex) | Steam（arm64）+ FEX-Emu + Proton ARM64 跑 Windows 游戏：安装脚本、`M1000ARM64` 兼容工具、DXVK 2.3.1、720p Game Mode |
| [mtgpu-pegasus](https://github.com/yeungtuzi/mtgpu-pegasus) | Pegasus 模拟器前端：aarch64 构建、`/opt/pegasus` 安装、`Game Mode - 模拟器`（720p@60，退出恢复 2880x1800@120） |
| [reunion-lite](https://github.com/yeungtuzi/reunion-lite) | 《红色警戒2 重聚未来》战役启动器：Windows x64 / Linux arm64（原生 Qt6），0.2 起支持 ARM64 + MTGPU，可真正进任务 |

## 🖥️ 桌面与显示

| 项目 | 说明 |
|---|---|
| [mtgpu-kde](https://github.com/yeungtuzi/mtgpu-kde) | KDE Plasma 6.8 for M1000：构建记录、**EDR/HDR**（峰值亮度通告、`target_luminance` 修正）、半屏修复、fcitx5；含 `mtgpu-kwin-edr` 覆盖包 |
| [mtgpu-woa](https://github.com/yeungtuzi/mtgpu-woa) | 在 KVM/QEMU 上跑 Windows 11 ARM64：显示走 RDP/RemoteFX，M1000 vfio-pci 直通，无专有组件 |

## 🛠️ 工具链与浏览器

| 项目 | 说明 |
|---|---|
| [mtgpu-clang](https://github.com/yeungtuzi/mtgpu-clang) | aarch64 clang/LLVM（AArch64-only、`cortex-a78+nocrypto`）deb，只装到 `/opt/mtgpu-toolchain`，不动系统 clang |
| [mtgpu-rust](https://github.com/yeungtuzi/mtgpu-rust) | aarch64 Rust 1.100-nightly（Chromium 固定 commit）+ `rustc-dev` + bindgen + **crubit**，同样只装 `/opt` |
| [mtgpu-chromium](https://github.com/yeungtuzi/mtgpu-chromium) | 本机源码构建的 Chromium 157（release）：de-Googled 版与标准版，含 EDR 实测记录与补丁说明 |
| [mtgpu-woa](https://github.com/yeungtuzi/mtgpu-woa) | 同上（虚拟化） |

## ⚙️ 其他工具

| 项目 | 说明 |
|---|---|
| [btop-xtu](https://github.com/yeungtuzi/btop-xtu) | btop++ fork：MUSA（摩尔线程）等国产 GPU 支持 + 自适应 GPU 布局 |

## 🧩 相关的红警2 生态

- [vera20k](https://github.com/yeungtuzi/vera20k) — 用 Rust 重写的《红色警戒2：尤里的复仇》引擎
- [vera20k-launcher](https://github.com/yeungtuzi/vera20k-launcher) — VERA20K 的战役/地图启动器

## 🔗 主题与列表

- 仓库统一打了 [`mtgpu`](https://github.com/topics/mtgpu) / [`moore-threads`](https://github.com/topics/moore-threads) topic；
- GitHub List：**[MUSA](https://github.com/stars/yeungtuzi/lists/musa)** — `mtgpu-*`、`reunion-lite`、`Xiaotu-LLM` 的合集。

更多仓库见 [Repositories](https://github.com/yeungtuzi?tab=repositories)。
