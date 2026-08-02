# AI 破甲 / Jailbreak GitHub 索引

> 快照日期：2026-08-03，Asia/Shanghai。
>
> 本仓库只做公开 GitHub 项目的链接索引和元数据整理，不复制 jailbreak 提示词、绕过 payload、利用步骤或目标仓库正文。

## 适用范围

本索引收录并分类整理：

- Codex / GPT-5.6 / Claude Code / Cursor 破甲、破限、jailbreak 相关项目
- 通用 LLM jailbreak、红队测试、对抗评测项目
- Prompt injection 攻击、基准、分类法与安全研究
- 防御、检测、guardrail、agent firewall、MCP 安全工具
- 资料合集、学习路径、论文/工具清单

完整表格数据见 [data/repos.csv](data/repos.csv)，JSON 数据见 [data/repos.json](data/repos.json)。

## 总榜 Top 10

| Stars | Repository | 类型 |
|---:|---|---|
| 10712 | [LouisShark/chatgpt_system_prompt](https://github.com/LouisShark/chatgpt_system_prompt) | Prompt injection / prompt leak |
| 6696 | [superagent-ai/superagent](https://github.com/superagent-ai/superagent) | 防御 / guardrails |
| 4363 | [Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) | AI 安全平台 |
| 4281 | [MDX-Tom/gpt-5.6-instruct](https://github.com/MDX-Tom/gpt-5.6-instruct) | Codex / GPT-5.6 破甲 |
| 1517 | [protectai/rebuff](https://github.com/protectai/rebuff) | Prompt injection 检测 |
| 1073 | [trailofbits/anamorpher](https://github.com/trailofbits/anamorpher) | 多模态注入研究 |
| 1028 | [chen0416ccc-cpu/codex-windows-fast-patch-skill](https://github.com/chen0416ccc-cpu/codex-windows-fast-patch-skill) | Codex 本地补丁 |
| 938 | [scadastrangelove/awesome-ai-security-tools](https://github.com/scadastrangelove/awesome-ai-security-tools) | 安全工具合集 |
| 786 | [luckyPipewrench/pipelock](https://github.com/luckyPipewrench/pipelock) | Agent firewall |
| 777 | [toby-bridges/api-relay-audit](https://github.com/toby-bridges/api-relay-audit) | API relay 审计 |

## 分类入口

- Codex / GPT-5.6 / 破甲：见主 [README.md](README.md#codex--gpt-56--pojia)
- Codex / Agent 工具：见主 [README.md](README.md#codex--agent-tooling-and-local-patch-adjacent)
- 通用 LLM jailbreak / 红队：见主 [README.md](README.md#general-llm-jailbreak--red-team-projects)
- Prompt injection / 防御：见主 [README.md](README.md#prompt-injection-defense-and-agent-security)
- 资料合集：见主 [README.md](README.md#curated-lists-field-manuals-and-learning-resources)

## 维护规则

1. 重新执行 [docs/search-method.md](docs/search-method.md) 中的 GitHub 搜索。
2. 按 `owner/repo` 去重。
3. 每个分类内按 stars 降序排列。
4. 保持链接索引，不复制可操作的绕过内容。
