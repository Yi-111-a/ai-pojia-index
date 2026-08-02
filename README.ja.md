# AI Pojia / Jailbreak GitHub インデックス

> スナップショット日：2026-08-03、Asia/Shanghai。
>
> このリポジトリは公開 GitHub プロジェクトへのリンク索引です。jailbreak プロンプト、回避 payload、実行手順、対象リポジトリ本文はコピーしません。

## 対象範囲

この索引は以下を分類します。

- Codex / GPT-5.6 / Claude Code / Cursor の pojia、制限解除、jailbreak 関連
- 一般的な LLM jailbreak、レッドチーム、対抗評価
- Prompt injection の攻撃、ベンチマーク、分類法、研究
- 防御、検出、guardrail、agent firewall、MCP セキュリティ、スキャナ
-  curated list、ハンドブック、論文、学習資料

完全な表データは [data/repos.csv](data/repos.csv)、JSON は [data/repos.json](data/repos.json) にあります。

## 総合 Top 10

| Stars | Repository | 種類 |
|---:|---|---|
| 10712 | [LouisShark/chatgpt_system_prompt](https://github.com/LouisShark/chatgpt_system_prompt) | Prompt injection / prompt leak |
| 6696 | [superagent-ai/superagent](https://github.com/superagent-ai/superagent) | 防御 / guardrails |
| 4363 | [Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) | AI セキュリティ基盤 |
| 4281 | [MDX-Tom/gpt-5.6-instruct](https://github.com/MDX-Tom/gpt-5.6-instruct) | Codex / GPT-5.6 jailbreak |
| 1517 | [protectai/rebuff](https://github.com/protectai/rebuff) | Prompt injection 検出 |
| 1073 | [trailofbits/anamorpher](https://github.com/trailofbits/anamorpher) | マルチモーダル注入研究 |
| 1028 | [chen0416ccc-cpu/codex-windows-fast-patch-skill](https://github.com/chen0416ccc-cpu/codex-windows-fast-patch-skill) | Codex ローカルパッチ |
| 938 | [scadastrangelove/awesome-ai-security-tools](https://github.com/scadastrangelove/awesome-ai-security-tools) | セキュリティツール集 |
| 786 | [luckyPipewrench/pipelock](https://github.com/luckyPipewrench/pipelock) | Agent firewall |
| 777 | [toby-bridges/api-relay-audit](https://github.com/toby-bridges/api-relay-audit) | API relay 監査 |

## カテゴリリンク

- Codex / GPT-5.6 / pojia：[README.md](README.md#codex--gpt-56--pojia)
- Codex / agent tooling：[README.md](README.md#codex--agent-tooling-and-local-patch-adjacent)
- 一般 LLM jailbreak / red team：[README.md](README.md#general-llm-jailbreak--red-team-projects)
- Prompt injection / defense：[README.md](README.md#prompt-injection-defense-and-agent-security)
- 資料集：[README.md](README.md#curated-lists-field-manuals-and-learning-resources)

## メンテナンス

1. [docs/search-method.md](docs/search-method.md) の検索を再実行します。
2. `owner/repo` で重複を除きます。
3. 各カテゴリを stars 降順で並べます。
4. 実用的な回避内容はコピーせず、リンク索引に保ちます。
