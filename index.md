---
layout: default
title: 项目与文档入口
description: holtwood 的 AI Infra / HPC 系统工作入口：三个公开组织、代表项目与证据边界
---

# holtwood

AI Infra / HPC systems. 这个页面只做路标；完整项目索引在
[imshane.site/projects](https://imshane.site/projects)。

## 三个公开组织

| 组织 | 职责 |
|---|---|
| [holtwood-systems](https://github.com/holtwood-systems) | 原创系统工作：CUDA/Triton 算子、推理运行时、Serving 控制面与可复现证据 |
| [holtwood-arena](https://github.com/holtwood-arena) | 比赛与 benchmark 记录：CANN / FlagOS / Kunpeng / Muse，以及公开的 `race` 实验室 |
| [holtwood-forks](https://github.com/holtwood-forks) | 上游源码研读副本；不主张原创，不混入作品集 |

## 代表项目

- [paged-serving](https://github.com/holtwood-systems/paged-serving) — Rust LLM Serving 控制面
- [tiny-llm](https://github.com/holtwood-systems/tiny-llm) — CUDA/C++ 推理运行时
- [cuflash](https://github.com/holtwood-systems/cuflash) — 从零实现的 CUDA FlashAttention
- [trifuse](https://github.com/holtwood-systems/trifuse) — Triton 融合算子 + `torch.library`
- [cuda-foundations](https://github.com/holtwood-systems/cuda-foundations) — CUDA 算子工程路径
- [kvtier](https://github.com/holtwood-systems/kvtier) — KV cache tiering 实验
- [race](https://github.com/holtwood-arena/race) — 性能工程竞赛实验室

## 旧主线

- [open-genomics](https://github.com/open-genomics) — 生信系统软件，维护模式
- [holtwood-projects](https://github.com/holtwood-projects) — 早期应用与工具项目

## 入口

- [GitHub Profile](https://github.com/holtwood)
- [项目总览](https://imshane.site/projects)
- [仓库导航](https://github.com/holtwood/repos-db)
- [变更记录](CHANGELOG.md)
