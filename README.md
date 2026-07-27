# 嘉豪 skill：全栈老兵实证审查

想要嘉豪的技能吗？想要成为嘉豪吗？这里是嘉豪训练营让你成为嘉豪，豪到爽豪到爆，豪情在天！

一个兼容 GPT/Codex 与 Claude Code 的通用 Agent Skill。

它把“全栈老兵”的有效方法抽成可执行规则：不迷信年龄、培训班、学历、头衔、截图和收入叙事，回到可验证的代码、运行结果、部署、排障、测试、维护和持续交付。

## 适用场景

- 全栈项目和代码审查
- 培训班项目、实习生项目和老兵经验对比
- AI 辅助开发能力判断
- 面试准备、职业路线和收入叙事分析
- 架构、部署、排障、测试和维护能力评估

## 安装

### Codex / GPT 类 Agent Skills

把整个目录复制到：

```text
$CODEX_HOME/skills/
```

Skill 名称：`fullstack-veteran-lens`

### Claude Code

把整个目录复制到用户级或项目级 skills 目录：

```text
~/.claude/skills/
.claude/skills/
```

Claude Code 直接读取 `SKILL.md`。`agents/openai.yaml` 是 GPT/Codex 的可选 UI 元数据，Claude 会忽略它，不影响兼容性。

## 设计原则

1. 年龄、工龄、培训经历和头衔是背景，不是能力证据。
2. UI 截图、简历、聊天记录和收入截图不能替代可复现交付。
3. AI 生成代码不自动等于低级；能否解释、修改、测试和排障才是关键。
4. 讽刺技术行为和论据，不攻击年龄、身份、外貌或家庭。
5. 每次审查都要落到证据边界、最小验证和下一步动作。

## 文件结构

```text
fullstack-veteran-lens/
├── SKILL.md
├── README.md
├── LICENSE
└── agents/
    └── openai.yaml
```

## 许可证

本项目使用 MIT License，详见 `LICENSE`。
## 致谢

感谢 QQ `1842841029` 与 QQ `3268237072` 提供聊天记录，并允许将其中可复用的工程判断方法整理为开源 skill。

聊天记录中的观点、语气和具体对话仅作为整理素材；本项目只抽取可复用的工程审查原则，不代表提供者对本项目全部文字、实现或后续版本承担责任。
