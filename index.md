---
layout: default
title: 项目与文档入口
description: holtwood 的 GitHub Profile 与项目集合入口：研究方向、推荐阅读路径与核心仓库导航
---

# holtwood

holtwood 是一个围绕 AI 基础设施、高性能计算与系统工程实践展开的公开项目集合。

## 项目定位

核心是 [open-infra-ai](https://github.com/open-infra-ai) 的 AI Infra 作品集
（CUDA 算子 → Triton → FlashAttention → 推理引擎 → 分页调度控制面，六技术仓 + 治理仓），
辅以 [open-genomics](https://github.com/open-genomics) 的生物信息与 C++ 工程、
[holtwood-projects](https://github.com/holtwood-projects) 的工具实验项目，
以及 [race](https://github.com/holtwood/race) 性能工程竞赛实验室。

## 快速入口

| 入口 | 说明 |
|------|------|
| [GitHub Profile](https://github.com/holtwood) | 个人主页，包含项目全景、经历、技术栈 |
| [项目展示页](https://github.com/holtwood#projects) | 直接跳转到项目区块 |
| [repos-db](https://github.com/holtwood/repos-db) | 全部仓库的盘点、分类与深读导航 |
| [race](https://github.com/holtwood/race) | 性能工程竞赛实验室：Speed Demon / 1BRC / PPC / DIMACS / AHC |
| [全部仓库](https://github.com/holtwood?tab=repositories) | 浏览所有公开仓库 |

## 核心仓库

| 仓库 | 说明 |
|------|------|
| [open-infra-ai/open-infra-ai](https://github.com/open-infra-ai/open-infra-ai) | AI Infra 作品集入口与证据包 |
| [open-infra-ai/cuda-foundations](https://github.com/open-infra-ai/cuda-foundations) | CUDA 算子工程学习路径（SGEMM 起步） |
| [open-infra-ai/trifuse](https://github.com/open-infra-ai/trifuse) | Triton 算子库（RMSNorm+RoPE / SwiGLU / FlashAttention / SGEMM） |
| [open-infra-ai/cuflash](https://github.com/open-infra-ai/cuflash) | 从零实现的 CUDA FlashAttention 前后向（WMMA） |
| [open-infra-ai/tiny-llm](https://github.com/open-infra-ai/tiny-llm) | C++ 原生推理引擎：GGUF / W8A16 / 分页 KV |
| [open-infra-ai/paged-serving](https://github.com/open-infra-ai/paged-serving) | 分页 KV + Continuous Batching 控制面（Rust） |
| [holtwood/race](https://github.com/holtwood/race) | 性能工程竞赛实验室：真题练习 + 成绩台账 |
| [open-genomics/fq-compressor](https://github.com/open-genomics/fq-compressor) | 高性能 FASTQ 压缩（C++23，3.97x，O(1) 随机访问） |
| [awesome-cursorrules-zh](https://github.com/holtwood/awesome-cursorrules-zh) | Cursor AI 规则精选集合 |

完整项目列表请查看 [GitHub Profile 项目区块](https://github.com/holtwood#projects)。

## 归档

- [CHANGELOG.md](CHANGELOG.md) — Profile 与 Pages 调整记录
