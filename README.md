# web-design-platform

Build high-quality visual Web artifacts with AI agents using HTML, CSS, JavaScript, and React.

使用 AI Agent 基于 HTML、CSS、JavaScript 和 React 构建高质量的可视化 Web 产物。

## What It Is

`web-design-platform` is an Agent Skill for design-centric front-end work. It helps an AI coding agent move beyond "functional enough" output and produce polished, intentional, visually strong deliverables.

`web-design-platform` 是一个面向设计型前端工作的 Agent Skill。它的目标不是只让 AI 产出“能用”的页面，而是推动 Agent 交付更精致、更有审美判断、更适合展示与落地的作品。

Typical outputs include:

常见交付物包括：

- web pages / marketing pages / landing pages
- dashboards / design systems / UI explorations
- interactive prototypes / UI mocks
- HTML slide decks / presentations
- animated demos / motion-driven visual artifacts
- data visualizations

- 网页 / 落地页 / 营销页
- 仪表盘 / 设计系统 / UI 探索
- 交互原型 / UI Mock
- HTML 幻灯片 / 演示稿
- 动效 Demo / 视觉化演示页面
- 数据可视化

## When To Use

Use this skill when the user asks for something visual, interactive, front-end, or presentation-oriented.

当用户需求是“可视化的、可交互的、偏前端的、偏展示型的交付物”时，就应使用这个 Skill。

Good fits:

适合的任务：

- "Build a beautiful landing page from this PRD"
- "Turn this screenshot into an interactive prototype"
- "Create an HTML presentation for this report"
- "Design a dashboard for this dataset"
- "Make a polished animated product demo"

- “根据这份 PRD 做一个漂亮的落地页”
- “把这张截图做成交互原型”
- “把这份报告做成 HTML 演示稿”
- “基于这份数据设计一个仪表盘”
- “做一个精致的产品动效 Demo”

Not a fit:

不适合的任务：

- pure back-end APIs
- CLI tools
- non-visual scripts
- pure logic or infrastructure work

- 纯后端 API
- 命令行工具
- 非可视化脚本
- 纯逻辑或基础设施类任务

## Core Philosophy

The standard is **stunning, not merely functional**.

标准是 **“惊艳”，而不只是“能用”**。

This skill encourages the agent to:

这个 Skill 会引导 Agent：

- understand product and design context before coding
- declare a design system before implementation
- show a v0 early instead of disappearing for too long
- avoid generic AI-looking UI patterns
- treat motion, typography, spacing, and composition as first-class design decisions

- 编码前先理解产品与设计上下文
- 实现前先声明设计系统
- 尽早给出 v0，而不是长时间“憋大招”
- 主动避开常见的“AI 味”视觉套路
- 把动效、字体、留白、构图当作一等设计决策

## Repository Contents

- [`SKILL.md`](./SKILL.md): the main skill definition and working methodology
- [`references/advanced-patterns.md`](./references/advanced-patterns.md): advanced UI patterns and reusable code templates

- [`SKILL.md`](./SKILL.md)：主技能定义与工作方法论
- [`references/advanced-patterns.md`](./references/advanced-patterns.md)：高级 UI 模式与可复用代码模板

## Installation

Clone this repository into your agent skill directory.

把这个仓库克隆到你的 Agent Skill 目录中。

### Trae / Claude Code style

```bash
mkdir -p .trae/skills
git clone https://github.com/yuyang-lion/web-design-platform-skill.git .trae/skills/web-design-platform
```

### SSH

```bash
mkdir -p .trae/skills
git clone git@github.com:yuyang-lion/web-design-platform-skill.git .trae/skills/web-design-platform
```

If your agent scans a different skills directory, copy or symlink this repository there.

如果你的 Agent 使用的不是 `.trae/skills`，把这个仓库复制或软链接到对应技能目录即可。

## How It Works

At a high level, the skill asks the agent to follow this workflow:

整体上，这个 Skill 要求 Agent 按下面的顺序工作：

1. Understand the task and ask only necessary questions
2. Gather design context from code, screenshots, product references, or brand systems
3. Declare the design system before coding
4. Show an early v0 draft
5. Build the full artifact with polished states and motion
6. Verify quality with a pre-delivery checklist

1. 理解任务，只问必要的问题
2. 从代码、截图、产品参考、品牌系统中收集设计上下文
3. 写代码前先声明设计系统
4. 先给出早期 v0 草稿
5. 完整实现，并补齐状态与动效细节
6. 用交付前清单做质量验证

## Design Principles

This skill strongly pushes the agent to avoid:

这个 Skill 会强烈约束 Agent 避免：

- purple-pink-blue gradient clichés
- generic rounded-card-plus-accent-bar layouts
- fake data and meaningless dashboard filler
- overused AI-default fonts like Inter / Roboto / Arial / system-ui
- black-box decision-making in visual design choices

- 紫粉蓝渐变等陈词滥调
- “圆角卡片 + 强调色边条”的模板化布局
- 虚构数据和无意义的看板填充
- Inter / Roboto / Arial / system-ui 这类 AI 默认味很重的字体
- 对设计选择缺乏解释、只堆结果的黑箱式输出

## Advanced Patterns

The included advanced reference file provides code templates for:

内置的高级参考文件提供了以下代码模板：

- responsive slide engines
- device frames
- tweaks panels
- animation timeline helpers
- design canvases
- dark mode toggles
- visualization templates
- color and typography recommendations

- 响应式幻灯片引擎
- 设备框
- Tweaks 调参面板
- 动画时间轴辅助工具
- 设计画布
- 暗黑模式切换
- 可视化模板
- 配色与字体建议

## Best For

This repository is especially useful for:

这个仓库尤其适合：

- AI coding agent users who build visual front-end deliverables
- teams that want more consistent taste in AI-generated UI
- people making HTML presentations, prototypes, and polished demos
- designers or PMs collaborating with code-oriented agents

- 使用 AI coding agent 产出前端视觉页面的人
- 希望提升 AI 产出 UI 审美一致性的团队
- 制作 HTML 演示稿、原型、精致 Demo 的人
- 与代码型 Agent 协作的设计师或产品经理

## License / 许可

Add your preferred license here if you plan to open-source it publicly.

如果你打算公开开源，请在这里补充你希望使用的许可证。
