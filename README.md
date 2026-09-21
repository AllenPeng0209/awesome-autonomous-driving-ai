# Awesome Autonomous Driving AI

**Astra’s daily research radar for autonomous driving — tracking the most important advances in VLA, world models, and end-to-end driving.**

由 Astra 每日筛选最值得读的自动驾驶论文，重点关注 **World Models × VLA**，兼顾端到端规划、几何表征、闭环评测和部署效率。中文解读，保留英文原题与一手来源。

目标：每天北京时间 **09:00** 更新 **3–5 篇未收录的新论文**。优先最近 7 天，必要时扩展到 30 天；高质量论文不足时少收或空缺，不用旧论文和低价值工作凑数。

## 最新一期 · 2026-09-21

[阅读今日日报](daily/2026-09-21.md) · [完整去重索引（25 篇）](data/papers.json) · [筛选与更新规范](CURATION.md)

| 论文 | arXiv v1 / 最新版本 | 一作或团队单位 | 为什么读 | 解读 |
| --- | --- | --- | --- | --- |
| ZYT-World | 09-18 / v1 09-18 | ZYT AI Team（团队署名） | 七视图混合投影、流式交互和重访记忆一起设计 | [⭐ World Model / 仿真](papers/World-Models/2609.21712-zyt-world.md) |
| CounterPlay | 09-18 / v1 09-18 | University of Freiburg + CARIAD SE | 回退失败状态、搜索风格并验证恢复，再蒸馏部署策略 | [🔥 后训练 / 交互](papers/End-to-End-Driving/2609.21617-counterplay.md) |
| SC-IMM Teacher Signals | 09-18 / v1 09-18 | KAIST CCS Graduate School of Mobility | 离线教师标签改善轨迹稳定性，推理结构不变 | [⭐ 辅助监督 / 稳定性](papers/Evaluation/2609.21404-sc-imm-teacher.md) |

以上为 **2026 年、arXiv UTC 日期**。本期先查 7 天，再补核 30 天范围内的期刊记录：SC-IMM 已有 9 月期刊记录，具体首发日未知，不以 arXiv 日替代。ZYT/CounterPlay 为预印本或技术报告；三篇本文实现与权重均未核实，本站未复现。

## 如何理解推荐

- **🔥 Must Read**：方法价值与实验证据都值得优先研究。
- **⭐ Recommended**：有明确启发，需注意证据或适用范围。
- **📦 Code**：已核实可访问的官方实现入口；不代表本仓库已复现。
- **🚗 Production Relevant**：Astra 判断对工程落地有价值；不表示已经量产。

SOTA 优先，但只在相同数据、指标与评测协议下讨论。每篇都写清楚 **为什么选、方法亮点、证据、局限、一作与共同一作单位、时间线、发表状态、代码状态和建议验证动作**。不以热度、作者单位或摘要中的 SOTA 宣称单独决定入选。

## 归档

- [2026-09-21：七视图仿真、失败回退与轨迹教师标签](daily/2026-09-21.md)
- [2026-09-20：配对未来、地形物理与跨车执行接口](daily/2026-09-20.md)
- [2026-09-19：On-policy 教师、施工区长尾与 Crisp-Drive v2 修订](daily/2026-09-19.md)
- [2026-09-18：未来表征对齐与循环动作记忆；DiffAdapterVLA v2 更新](daily/2026-09-18.md)
- [2026-09-17：未来监督裁剪、RL 教师与可执行动作约束](daily/2026-09-17.md)
- [2026-09-16：主干内规划、风险接口与有依据的推理](daily/2026-09-16.md)
- [2026-09-14：候选未来、慢快分工与辅助监督](daily/2026-09-14.md)
- [2026-09-13：世界表征、动作接口与跨车型泛化](daily/2026-09-13.md)

每日更新由本地 Codex 定时任务执行，检索并核实来源后提交到 GitHub。运行机器和应用须保持可用；执行失败会明确报告。仓库内仅存原创解读、元数据和来源链接，不镜像论文全文。
