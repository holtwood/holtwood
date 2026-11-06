# Shane / holtwood

**Systems engineer working on AI infrastructure, GPU kernels, and performance-critical software.**

C++ · CUDA · Triton · Rust · HPC

I care about the part after the benchmark: whether a performance claim survives a different shape, a different machine, and a clean rebuild.

> 做 AI Infra / HPC 系统，关心性能结论能否被复现。

**Open to:** AI Infra / HPC / performance engineering roles and technical collaboration.

[Website](https://imshane.site/projects) · [Systems](https://github.com/holtwood-systems) · [Arena](https://github.com/holtwood-arena) · [Forks](https://github.com/holtwood-forks) · [Email](mailto:jiashuai.shi@qq.com)

---

## Start here

Three public organizations, each with a different job:

| | Organization | What it is |
|---|---|---|
| **Systems** | [holtwood-systems](https://github.com/holtwood-systems) | Original AI Infra / HPC work: kernels, inference runtime, serving control plane, reproducible evidence |
| **Arena** | [holtwood-arena](https://github.com/holtwood-arena) | Competition and benchmark record: CANN / FlagOS / Kunpeng / Muse, plus the public `race` lab |
| **Forks** | [holtwood-forks](https://github.com/holtwood-forks) | Upstream reading copies. No original work claimed; useful for source study and minimal repros |

The curated entry point is **[imshane.site/projects](https://imshane.site/projects)**. GitHub is the implementation layer, not the only map.

## Selected work

| Project | What it is | Signal |
|---|---|---|
| [paged-serving](https://github.com/holtwood-systems/paged-serving) | Rust LLM serving control plane: paged KV, continuous batching, OpenAI-compatible SSE, C ABI to a real CUDA backend | control/data plane boundary |
| [tiny-llm](https://github.com/holtwood-systems/tiny-llm) | CUDA/C++ inference runtime: GGUF, W8A16, tokenizer, paged KV, CUDA Graphs | end-to-end runtime |
| [cuflash](https://github.com/holtwood-systems/cuflash) | FlashAttention from scratch in CUDA C++: scalar → WMMA tensor cores, FlashDecoding / Split-KV | kernel depth |
| [trifuse](https://github.com/holtwood-systems/trifuse) | Fused Triton kernels (RMSNorm+RoPE, gated MLP, FlashAttention) registered through `torch.library` | kernel breadth + integration |
| [cuda-foundations](https://github.com/holtwood-systems/cuda-foundations) | A reproducible CUDA operator path: SGEMM ladder → reusable kernels → inference components | teaching by construction |
| [race](https://github.com/holtwood-arena/race) | Performance engineering lab: Speed Demon, 1BRC, PPC, DIMACS, AHC; every number bound to hardware and commit | competition discipline |

Full map: [holtwood-systems/portfolio](https://github.com/holtwood-systems/portfolio).

Also: [kvtier](https://github.com/holtwood-systems/kvtier) (KV cache tiering experiments) · [ai-infra-radar](https://github.com/holtwood/ai-infra-radar) (upstream contribution radar, personal).

## Competition work

I use competitions as a forcing function for measurement discipline.

- **CANNJudge / Ascend 910B2** — CANN 2026 electricity-industry operator special (10 problems) and October ladder (4 problems), plus the earlier CANN challenge. Private workspaces are retained as archives; public methodology is in [holtwood-arena](https://github.com/holtwood-arena).
- **Kunpeng HPC** — S2 convolution optimization (public, x86-verified; Kunpeng platform not re-measured) and S3 OpenFOAM static study (public, archived; not entered).
- **FlagOS S2** — SGLang kernel optimization and MiniCPM5-2B inference throughput workspaces.
- **Muse Spark Open Kernel Challenge** — kernel and serving tracks.

Public workspaces: [kunpeng-s2-conv](https://github.com/holtwood-arena/kunpeng-s2-conv) · [kunpeng-s3-openfoam](https://github.com/holtwood-arena/kunpeng-s3-openfoam) · [race](https://github.com/holtwood-arena/race).

> Competition rules and other teams' work are respected: private workspaces stay private while the rules require it; public pages carry only sanitized, reproducible material.

## Before systems

I came to AI infrastructure through genomics and real-time systems: BGI (genomic-scale data workflows), Mindray (medical imaging), ZEGO (RTC). That background is why I care about memory bounds, I/O behavior, and end-to-end latency — not just kernel microbenchmarks.

The genomics work is archived under [open-genomics](https://github.com/open-genomics) in maintenance mode. The earlier application/tooling projects remain at [holtwood-projects](https://github.com/holtwood-projects).

## How I scope claims

- **Local / CPU** correctness is not device correctness.
- **Device** correctness is not platform acceptance.
- **A benchmark** is only as useful as its hardware, shape, build, command, and variance record.
- If a claim does not survive a clean rebuild, it is not a result yet.

## Elsewhere

- Website: [imshane.site](https://imshane.site)
- GitHub: [@holtwood](https://github.com/holtwood)
- Email: [jiashuai.shi@qq.com](mailto:jiashuai.shi@qq.com)
