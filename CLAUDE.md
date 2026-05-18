# 佛说 Foshuo - Claude Code 项目

## 项目说明

这是佛说（Foshuo）——佛教哲学AI工作流skill的GitHub仓库。

## 目录结构

```
foshuo-project/
├── README.md           # 中文宣传版（访客看到）
├── README_en.md        # 英文宣传版
├── CLAUDE.md          # 本文件，项目说明
└── foshuo-skill/      # 实际skill
    ├── SKILL.md       # AI读取的skill文件
    ├── README.md      # 实用说明（给开发者）
    ├── README_CN.md   # 中文宣传版
    ├── cases/         # 12个经典案例
    └── references/    # 触发词、响应示例
```

## 使用foshuo-skill

克隆后，将 `foshuo-skill` 目录放到对应位置：
- Claude Code: `~/.claude/skills/`
- OpenClaw: `~/.agents/skills/`

详细说明见 `foshuo-skill/README.md` 或 `foshuo-skill/SKILL.md`