# My-Skills

个人可复用的 Claude Code skills 汇总。每个 skill 一个独立子目录，目录内放 `SKILL.md`（带 `name` / `description` frontmatter）以及可选的 `references/`、`scripts/`、`templates/`。

| Skill | 用途 |
|---|---|
| [modeling-contest-orchestration](modeling-contest-orchestration/) | 用「人 + 多个 AI」组队打数学建模 / 大数据竞赛的完整打法 |

## 新增一个 skill

1. 新建目录 `<skill-name>/`
2. 放入 `SKILL.md`，frontmatter 写 `name` 与 `description`（description 要写清触发场景）
3. 按需添加 `references/`、`scripts/`、`templates/`
4. 在上表补一行

## 安装

把子目录复制到 `~/.claude/skills/` 下，例如：

```bash
cp -R modeling-contest-orchestration ~/.claude/skills/
```
