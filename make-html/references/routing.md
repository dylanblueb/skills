# Make HTML Routing

用这张表做第一轮结构选择。它不是硬性模板；若简单结构更清楚，优先简单结构。

| 用户目标 | 首选结构 | 备选结构 |
|---|---|---|
| 文章、教程、长文档 | 单栏文章 + 章节导航 | Concept Explainer |
| 解释概念或机制 | Concept Explainer（15） | Feature Explainer（14） |
| 展示系统流程、请求链路 | Annotated Flowchart（13） | Module Map（04） |
| 生成周报或项目状态 | Status Report（11） | Implementation Plan（16） |
| 写事故复盘 | Incident Report（12） | Timeline + action items |
| 代码评审或 diff | Code Review（03） | PR Writeup（17） |
| 解释陌生代码库 | Module Map（04） | Feature Explainer（14） |
| 展示设计 token 和组件 | Living Design System（05） | Component Variants（06） |
| 做交互原型 | Clickable Flow（08） | Animation Sandbox（07） |
| 做幻灯片或提案 | Arrow-Key Slide Deck（09） | Visual Directions（02） |
| 管理大量任务 | Ticket Triage Board（18） | Status Report（11） |
| 编辑配置或开关 | Feature Flag Editor（19） | Prompt Tuner（20） |
| 调试提示词或模板 | Prompt Tuner（20） | 单栏编辑器 |
| 只做视觉展示 | Visual Directions（02） | SVG Figure Sheet（10） |

## 选择规则

- 内容类型决定 layout；项目或品牌风格决定 theme；真实状态变化决定 interaction。
- 短内容优先单栏，不自动加入卡片、目录、tabs 或动画。
- 多对象比较使用比较结构；有关系和方向使用图；有状态变化才使用控件。
- 需要复制、下载、导出或编辑时，交互必须有真实结果。
- 主题选择顺序：源项目风格 → 用户点名主题 → 保存的匹配主题 → fallback theme。
