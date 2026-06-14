# novel-polishing

Codex 技能 —— 网络小说智能润色。

## 功能

- 分析小说题材、流派、写作手法
- 检查并修复逻辑 Bug
- 去除 AI 写作痕迹，还原真人笔触
- 增强吸引力（反差、悬念、钩子）
- 确保每章 2500 字以上
- 丰富剧情细节

## 安装

将本仓库克隆到 `~/.codex/skills/novel-polishing/`，然后在 Codex 对话中输入 `$novel-polishing` 即可调用。

## 文件结构

```
novel-polishing/
├── SKILL.md          # 核心技能指令
└── agents/
    └── openai.yaml   # UI 元数据
```