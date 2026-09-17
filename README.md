# Awesome Autonomous Driving AI

**Astra’s daily research radar for autonomous driving — tracking the most important advances in VLA, world models, and end-to-end driving.**

由 Astra 每日筛选最值得读的自动驾驶论文，重点关注 **World Models × VLA**，兼顾端到端规划、几何表征、闭环评测和部署效率。中文解读，保留英文原题与一手来源。

目标：每天北京时间 **09:00** 更新 **3–5 篇未收录的新论文**。优先最近 7 天，必要时扩展到 30 天；高质量论文不足时少收或空缺，不用旧论文和低价值工作凑数。

## 最新一期 · 2026-09-17

[阅读今日日报](daily/2026-09-17.md) · [完整去重索引（15 篇）](data/papers.json) · [筛选与更新规范](CURATION.md)

| 论文 | arXiv v1 / 最新版本 | 一作或团队单位 | 为什么读 | 解读 |
| --- | --- | --- | --- | --- |
| SV-WAM | 09-03 / v1 09-03 | 中科院自动化所 + Chongqing Changan Technology | 未来视频只参与训练监督，推理保留环视并只输出动作 | [🔥 World-Action](papers/World-Models/2609.03602-sv-wam.md) |
| DriveZero | 09-05 / v1 09-05 | Xiaomi EV，L3 Team（团队署名） | 视觉表征与 RL 教师分工，目标增强生成日志外监督 | [🔥 E2E / 部分开源](papers/End-to-End-Driving/2609.06055-drivezero.md) |
| Comfort by Construction | 09-11 / v1 09-11 | 共同一作均为 University of Freiburg | 动态可行动作网格，审查仿真急动作带来的指标虚高 | [⭐ 动作接口 / 评测](papers/Evaluation/2609.13011-comfort-by-construction.md) |

以上为 **2026 年、arXiv UTC 日期**。本期扩展到最近 30 天；并非全部最近 7 天首发。DriveZero 另有 09-04 的 Git 报告记录，当前已发布的实现/权重限 DriveRL 教师。三篇均未独立复现；时延范围、舒适性与碰撞的取舍详见卡片。

## 如何理解推荐

- **🔥 Must Read**：方法价值与实验证据都值得优先研究。
- **⭐ Recommended**：有明确启发，需注意证据或适用范围。
- **📦 Code**：已核实可访问的官方实现入口；不代表本仓库已复现。
- **🚗 Production Relevant**：Astra 判断对工程落地有价值；不表示已经量产。

SOTA 优先，但只在相同数据、指标与评测协议下讨论。每篇都写清楚 **为什么选、方法亮点、证据、局限、一作与共同一作单位、时间线、发表状态、代码状态和建议验证动作**。不以热度、作者单位或摘要中的 SOTA 宣称单独决定入选。

## 归档

- [2026-09-17：未来监督裁剪、RL 教师与可执行动作约束](daily/2026-09-17.md)
- [2026-09-16：主干内规划、风险接口与有依据的推理](daily/2026-09-16.md)
- [2026-09-14：候选未来、慢快分工与辅助监督](daily/2026-09-14.md)
- [2026-09-13：世界表征、动作接口与跨车型泛化](daily/2026-09-13.md)

每日更新由本地 Codex 定时任务执行，检索并核实来源后提交到 GitHub。运行机器和应用须保持可用；执行失败会明确报告。仓库内仅存原创解读、元数据和来源链接，不镜像论文全文。
