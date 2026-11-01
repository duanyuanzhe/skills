# 飞书 Skills

这里收录 28 个基于 `lark-cli` 的飞书/Lark Skills，包括消息、日历、任务、文档、云空间、表格、多维表格、会议、审批、妙搭及相关工作流。每个 `lark-*` 目录都是独立 Skill；`references/`、`scripts/` 和其他配套文件与 `SKILL.md` 一起保留。跨 Skill 的相对引用依赖这些目录位于同一层级。

## 来源与版本

- 来源：[Lark CLI 的 `skills/lark-*` 目录](https://github.com/larksuite/cli/tree/main/skills)。
- 这是从本机 `~/.agents/skills/lark-*` 复制的快照，并修正了少量失效的文档链接；复制时本机 `lark-cli` 版本为 `1.0.91`。本仓库不会自动跟随上游更新。
- 上游采用 MIT License，许可证文本见本目录的 [LICENSE](LICENSE)。

## 使用

需要先安装 `lark-cli`，并按照 `lark-shared/SKILL.md` 完成认证和权限配置。使用时将所需的 `lark-*` 目录放入 Agent 的 Skills 目录；涉及跨 Skill 调用时，同时放入被引用的目录。不要将本机的登录态、配置文件或令牌提交到仓库。
