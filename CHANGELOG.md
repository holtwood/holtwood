# Changelog

## 2026-11-06
- Profile README 从“仓库总目录”收敛为三层入口：身份与方向、三个公开组织、代表项目
- 组织架构定稿：`holtwood-systems`（原创系统）、`holtwood-arena`（比赛与 benchmark）、`holtwood-forks`（上游研读）
- 个人主页不再链接私有面试包，不再使用过时测试数量；`ai-infra-serving-study-plan` 作为公开学习计划
- 保留 2026-11-03 的 `kvtier` / `ai-infra-radar` / `race` 事实，但不再使用旧组织根链接
- `index.md` 与 `_config.yml` 同步新定位；Pages 入口保留为轻量路标
- 旧组织根 `open-infra-ai` / `cannjudge` 不再作为公开入口；仓库级旧 URL 仅作 301 重定向

## 2026-11-03
- 修正“AI Infra 五仓作品集”为“AI Infra 作品集”：组织已扩至六技术仓 + 治理仓，展示表补充 kvtier 与 ai-infra-radar 两仓卡片
- 移除已迁回个人私有仓的 `ai-infra-interview-prep` 外链（原 `open-infra-ai/ai-infra-interview-prep` 公开路径已失效）
- 原“AI Infra 转行计划”区块改为“Racing & Index / 性能赛事与索引”：新增 race 性能工程竞赛实验室卡片
- `index.md` 同步：作品集描述更新为“六技术仓 + 治理仓”，失效的 interview-prep 入口替换为 race

## 2026-10-19
- 账号与仓库名收敛：`LessUp` 账号更名 `holtwood`、仓库更名 `holtwood`（仓库名与账号名一致）
- `_config.yml` 同步规范地址：`repository: holtwood/holtwood`、`baseurl: /holtwood`、`title: holtwood`（修复改名后 Pages 资源路径）
- `index.md` 全部链接更新：`LessUp/*` → `holtwood/*` 或迁移后的组织地址；核心仓库表补 cuda-foundations / trifuse，替换旧名（aicl-lab / cuflash-attn / paged-infer）
- `CLAUDE.md` 同步仓库名与 Pages 地址
- 移除 `.claude/settings.local.json`（AI 工具本地配置，不应公开），`.gitignore` 增加 `.claude/`

## 2026-08-19
- 修复全部迁移前仓库链接：5 个自动重定向链接（fq-compressor、fastq-tools、micos-2024、awesome-bioinfo-algorithms、awesome-compression）与 8 个重定向失效链接（wiki-bioinfo、compress-kit、bookmarks-cleaner、graph-viewer、meta-human、mind-gym、yolo-toys、webrtc）改为规范组织地址，stars badge 同步更新
- 移除 4 个已删除仓库的展示（sgemm-optimization、the-art-of-hpc-zh、cursor-rules、awesome-claude-skills-zh），用现存仓库卡片（cudaimg、TensorTonic-Solutions、bookmarks-manager、brave-sync-notes）替换
- 新增"AI Infra 五仓作品集（open-infra-ai）"区块：cuda-foundations、cuflash-attn、triton-fused-ops、tiny-llm、paged-infer、aicl-lab
- index.md 核心仓库表更新为 open-infra-ai 作品集 + 规范链接
- 建议手动 Pin：cuflash-attn、tiny-llm、paged-infer、cuda-foundations、triton-fused-ops、fq-compressor（API 无法修改 Pinned items）

## 2026-06-03
- 修复 Signals 区贡献图显示失败：移除失效的 Streak 卡片（demolab 公共实例 API/路由异常），恢复 Activity Graph 展示公开贡献趋势

## 2026-05-18
- 修复 Profile 活动图与视觉签名“看起来不准”的问题：降低 Activity Graph 缓存、补充公开数据/UTC 口径说明
- 蛇图改为亮暗主题自适应，并将生成频率从每日一次提升为每 6 小时一次

## 2026-05-12
- 更新项目全景，新增生物信息学与开发者工具分类

## 2026-05-08
- 修复外部服务失效链接（GitHub Stats、favicon、Trophy）

## 2026-03-13
- Pages 入口与 Profile 职责分离
- Profile Workflow 清理

## 2026-03-10
- Workflow 深度标准化

## 2026-03-09
- 添加 CI workflow

## 2025-02-13
- GitHub Profile README 全面重构，项目展示扩展到 17 个
