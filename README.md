# Awesome Autonomous Driving AI

**Astra’s daily research radar for autonomous driving — tracking the most important advances in VLA, world models, and end-to-end driving.**

由 Astra 每日筛选最值得读的自动驾驶论文，重点关注 **World Models × VLA**，兼顾端到端规划、几何表征、闭环评测和部署效率。中文解读，保留英文原题与一手来源。

目标：每天北京时间 **09:00** 更新 **3–5 篇未收录的新论文**。优先最近 7 天，必要时扩展到 30 天；高质量论文不足时少收或空缺，不用旧论文和低价值工作凑数。

## 最新一期 · 2026-09-16

[阅读今日日报](daily/2026-09-16.md) · [完整去重索引（12 篇）](data/papers.json) · [筛选与更新规范](CURATION.md)

| 论文 | 首次公开 / 最新版本 | 一作单位 | 为什么读 | 解读 |
| --- | --- | --- | --- | --- |
| DiffAdapterVLA | 09-14 / v1 09-14 | 武汉大学 | 让轨迹在 VLM 后层逐步形成 | [🔥 VLA / 效率](papers/VLA/2609.15322-diffadaptervla.md) |
| READ | 09-11 / v1 09-11 | 共同一作均为清华大学 | 用匹配消融检验规划相关风险监督 | [⭐ 风险表征](papers/Generative-Planning/2609.12371-read.md) |
| CorrRisk-WM | 09-15 / v1 09-15 | Texas A&M University | 候选走廊查询未来侵入与 near-miss | [⭐ World Model](papers/World-Models/2609.16724-corrrisk-wm.md) |
| GRAVA | 09-14 / v1 09-14 | 北京理工大学及深圳汽车研究院、Shenzhen Jiguangzhijie Technology | 将有物理依据的推理接到可执行动作 | [⭐ VLA / 推理](papers/VLA/2609.15169-grava.md) |

以上日期均为 **2026 年、arXiv UTC 日期**。本期四篇均在最近 7 天内首发，无需扩大窗口。GRAVA 页眉注明 TPAMI 投稿，尚非录用；官方主页仅 README/展示资源。四篇均未独立复现，批量时延、开环风险评估和驾驶闭环的证据边界见卡片。

## 如何理解推荐

- **🔥 Must Read**：方法价值与实验证据都值得优先研究。
- **⭐ Recommended**：有明确启发，需注意证据或适用范围。
- **📦 Code**：已核实可访问的官方实现入口；不代表本仓库已复现。
- **🚗 Production Relevant**：Astra 判断对工程落地有价值；不表示已经量产。

SOTA 优先，但只在相同数据、指标与评测协议下讨论。每篇都写清楚 **为什么选、方法亮点、证据、局限、一作与共同一作单位、时间线、发表状态、代码状态和建议验证动作**。不以热度、作者单位或摘要中的 SOTA 宣称单独决定入选。

## 归档

- [2026-09-16：主干内规划、风险接口与有依据的推理](daily/2026-09-16.md)
- [2026-09-14：候选未来、慢快分工与辅助监督](daily/2026-09-14.md)
- [2026-09-13：世界表征、动作接口与跨车型泛化](daily/2026-09-13.md)

每日更新由本地 Codex 定时任务执行，检索并核实来源后提交到 GitHub。运行机器和应用须保持可用；执行失败会明确报告。仓库内仅存原创解读、元数据和来源链接，不镜像论文全文。
