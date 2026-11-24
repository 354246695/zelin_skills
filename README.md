# zelin_skills

个人 skill 收集仓。一个 skill 一个目录，入口为各目录下的 `SKILL.md`。

## 收录清单

| skill | 作用 |
| --- | --- |
| [bilingual-doc](./bilingual-doc/SKILL.md) | 把外文技术文件（SKILL.md、提示词、协议或配置文档）做成单文件中英对照 HTML：左列原文照录并标注行区间，右列忠实中文翻译，带来源基线页头、出处标注和结构自检 |

## 安装

把对应 skill 目录复制到 agent 的用户级 skill 目录（如 `~/.agents/skills/` 或 `~/.claude/skills/`）：

```powershell
Copy-Item -Recurse ./bilingual-doc ~/.agents/skills/
```

## 维护约定

- 本仓为源头，安装目录为生效副本：修改先改本仓，再同步到安装目录。
- 提交信息用中文，Conventional Commit 前缀（feat / fix / docs / refactor）。
