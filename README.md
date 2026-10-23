# Systematic Learning Coach

跨领域系统化学习教练 Skill：通过知识地图、分层讲解、主动提问、实践验证、掌握度评估和知识沉淀，帮助学习者建立可解释、可应用、可检验的知识体系。

> 当前版本：**V1.1 初始可用 Skill（待真实场景验证）**。不是已经验证有效的跨领域产品。

## 快速开始

在支持读取自定义 Skill 的 AI 工具中，使用仓库根目录的 [SKILL.md](SKILL.md) 作为入口，并保持相对路径下的参考文件可访问。不同工具的 Skill 安装方式可能不同。

示例指令：
- “使用 systematic-learning-coach，带我系统学习 Spring Boot，从整体架构开始。”
- “切换复习模式，检验我对 MySQL MVCC 的理解。”
- “把本次学习整理成脱离聊天也能阅读的完整笔记，保留纠错和实验证据。”

## 工作模式

| 模式 | 入口策略 | 目标 |
|---|---|---|
| Learn 系统学习 | 知识地图 → 主线案例 → 原理 → 一题验证 | 建立正确理解 |
| Review 复习评估 | 场景诊断 → 定向补强 → 迁移验证 | 发现并修复知识缺口 |
| Document 知识沉淀 | 整理推导、案例、图示、问答与证据 | 生成独立可读的长期资料 |

三种模式按任务选择，不要求机械走完全部环节。

## 仓库结构

- [SKILL.md](SKILL.md)：Skill 入口、模式选择和核心决策规则
- [references/teaching-and-feedback.md](references/teaching-and-feedback.md)：教学与批改协议
- [references/practice-and-assessment.md](references/practice-and-assessment.md)：实践证据与掌握度评估
- [references/documentation-standard.md](references/documentation-standard.md)：归档规范与验收
- [domains/software-engineering.md](domains/software-engineering.md)：首个领域适配器
- [templates/](templates/)：学习计划、知识笔记、实践记录、复盘模板
- [docs/learning-methodology-v1.md](docs/learning-methodology-v1.md)：方法论原理和真实专项经验

## 设计原则

先整体后局部；先理解后记忆；先独立思考后反馈；区分预测与实测；以目标控制深度；资料必须能脱离原聊天独立阅读。

## 版本路线

- **V1.0**：方法论与技术专项经验归纳。
- **V1.1（当前）**：通用 Skill、软件工程适配器、教学规范和模板。
- **下一阶段**：在 Spring/Spring Boot 专项中测试，记录规则失效点与归档返工。
- **未来**：依据实际使用情况扩展 AI、金融投资等领域；验证长期复习策略。

## License

见 [LICENSE](LICENSE)。
