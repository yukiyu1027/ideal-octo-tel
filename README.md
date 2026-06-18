# ideal-octo-tel

WorkBuddy 用户数据备份仓库，包含技能（skills）、记忆（memory）、用户配置和自动化配置。

## 目录结构

```
├── user-profile/          # 用户身份与记忆
│   ├── MEMORY.md         # 用户级长期记忆
│   ├── SOUL.md           # AI 助手人格定义
│   ├── IDENTITY.md       # AI 助手身份信息
│   └── USER.md           # 用户信息
├── skills/               # 已安装的 WorkBuddy 技能
├── experts/              # 专家包配置
├── connectors-meta/      # 连接器技能元数据
├── automations/          # 自动化任务配置（从 DB 导出）
└── .gitignore
```

## 说明

- 此仓库不含数据库文件、会话记录、日志等运行时数据
- 不含任何 API Key、Token 等敏感凭据
- 如需恢复，将对应目录复制回 `~/.workbuddy/` 即可

## 更新

手动推送或由 WorkBuddy 助手协助更新。
