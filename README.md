# Vibecoding 开发工作流

## 四个 Skill

| Skill | 适用场景 | 交付物 |
| --- | --- | --- |
| `$maintain-prd` | 从构想梳理需求，或同步已确认的业务与交互变更 | 主 PRD、功能 ID 和验收标准 |
| `$design-architecture` | 首次技术选型、重要架构变化或架构审查 | 架构文档与关键决策 |
| `$plan-vertical-slices` | 按完整功能链路拆分任务，或执行指定任务 | 任务卡、实现和验收结果 |
| `$design-product-ui` | 新页面、视觉优化、原型或 UI 验收 | 可交互原型、UI 规则和实际验收结果 |

UI Skill 以米哈游产品页为质量标杆，按项目定位选择风格，包含主视觉选图和裁切、字体与数字排版、动效反馈和窄屏验收规则。

## 从 GitHub 获取

有此私有仓库访问权限的账号可以用 GitHub 的 HTTPS 或 SSH 地址克隆。

```sh
git clone https://github.com/ZhouYi419/vibecoding-skill.git
```

克隆后在 Codex 打开 `vibecoding-skill` 根目录，即可使用仓库级 Skill 和 `AGENTS.md`。

## 换电脑或环境后恢复

1. 按上面的命令克隆，或从 GitHub 下载并解压仓库 ZIP。目录里应有 `AGENTS.md` 和 `.agents/skills/`。
2. **只在一个项目使用**时，将整个 `.agents/skills/` 放入该项目根目录。新项目可以复制 `AGENTS.md` 到根目录，并填写项目约定。已有项目按需合并规则到原有 `AGENTS.md`。
3. **供本机所有项目使用**时，将 `.agents/skills/` 下的四个 Skill 目录复制到用户目录下的 `.agents/skills/`。Windows 示例是 `%USERPROFILE%\.agents\skills\`，macOS 与 Linux 使用 `~/.agents/skills/`。若同名 Skill 已经可用，更新对应的现有副本即可。
4. 在 Codex 打开目标项目，通过 `$` 或 `/skills` 核对四个名称。用「按 `AGENTS.md`，把我的产品想法整理成首版 PRD」开始，或者在已有项目中指定要执行的任务卡。小改动按范围使用相关 Skill。

四个 Skill 都以各自目录中的 `SKILL.md` 为入口。可保留目录结构直接复用，或按需查看和编辑单个文件。项目自己的 PRD、架构文档和任务卡由各自的仓库管理。

[Codex Skill 目录说明](https://learn.chatgpt.com/docs/build-skills#where-codex-loads-local-skills)
