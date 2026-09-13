# Awesome Autonomous Driving AI

**Astra’s daily research radar for autonomous driving — tracking the most important advances in VLA, world models, and end-to-end driving.**

由 Astra 每日筛选最值得读的自动驾驶论文，重点关注 **World Models × VLA**，兼顾端到端规划、几何表征、闭环评测和部署效率。中文解读，保留英文原题与一手来源。

目标：每天北京时间 **09:00** 更新 **3–5 篇未收录的新论文**。优先最近 7 天，必要时扩展到 30 天；高质量论文不足时少收或空缺，不用旧论文和低价值工作凑数。

## 最新一期 · 2026-09-13

[阅读首期日报](daily/2026-09-13.md) · [完整去重索引](data/papers.json) · [筛选与更新规范](CURATION.md)

| 论文 | 首次公开 / 最新版本 | 一作单位 | 为什么读 | 解读 |
| --- | --- | --- | --- | --- |
| LaPla | 09-03 / v1 09-03 | HKUST (Guangzhou)；共同一作同单位 | 连续 latent 一次解码；正视进度与碰撞的取舍 | [⭐ VLA](papers/VLA/2609.04070-lapla.md) |
| Towards Zero-Shot Transfer Across Embodiments For Driving VLAs | 09-02 / v1 09-02 | Mines Paris + Stellantis | 跨相机配置泛化；检验数据多样性是否替代辅助任务 | [⭐ VLA / 泛化](papers/VLA/2609.02341-zero-shot-transfer.md) |
| GeoWAM | 08-24 / v2 08-25 | Uber AV Labs + Case Western Reserve University | 预测未来几何，让世界模型直接服务规划 | [🔥 World Model](papers/World-Models/2608.23486-geowam.md) |
| WA-JEPA | 08-21 / v2 09-05 | Afari Intelligent Drive；共同一作含 UESTC / SEU | 联合预测未来 latent 与动作，有公开复现入口 | [🔥 World Model](papers/World-Models/2608.20974-wa-jepa.md) |

以上日期均为 **2026 年、arXiv UTC 日期**。四篇当前均按预印本收录，尚未核实正式会议或期刊录用。

## 如何理解推荐

- **🔥 Must Read**：方法价值与实验证据都值得优先研究。
- **⭐ Recommended**：有明确启发，需注意证据或适用范围。
- **📦 Code**：已核实可访问的官方实现入口；不代表本仓库已复现。
- **🚗 Production Relevant**：Astra 判断对工程落地有价值；不表示已经量产。

SOTA 优先，但只在相同数据、指标与评测协议下讨论。每篇都写清楚 **为什么选、方法亮点、证据、局限、一作与共同一作单位、时间线、发表状态、代码状态和建议验证动作**。不以热度、作者单位或摘要中的 SOTA 宣称单独决定入选。

## 归档

- [2026-09-13：世界表征、动作接口与跨车型泛化](daily/2026-09-13.md)

每日更新由本地 Codex 定时任务执行，检索并核实来源后提交到 GitHub。运行机器和应用须保持可用；执行失败会明确报告。仓库内仅存原创解读、元数据和来源链接，不镜像论文全文。
